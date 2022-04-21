# Update Files

## Structure
The update is contained within a password protected zip file with a signature appended to it. The last 256 bytes of update file is SHA256 signature, that is verified against publisher_cert.pem.

The zip contains the following

| File Path                                     | Optional | Description                                                            |
| --------------------------------------------- | -------- | ---------------------------------------------------------------------- |
| jci_subord_cert.pem                           | No       | Subordinate Certificate                                                |
| publisher_cert.pem                            | No       | Publisher Certificate                                                  |
| [main_instructions.ini](#maininstructionsini) | No       | Update instructions                                                    |
| versions.ini.gz                               | Unknown  | Versions of update, versions the update is compatible with             |
| bootstrap/                                    | Yes      | Update for bootstrap section of SPI-NOR                                |
| cleandatapersist/                             | Yes      | Script to cleanup /mnt/data_persist/                                   |
| compactwnn/                                   | Yes      | Unknown                                                                |
| getnewflavour/                                | Yes      | Unknown                                                                |
| gps/                                          | Yes      | Update for GPS firmware                                                |
| ibc1/                                         | Yes      | Update for IBC1 SPI-NOR:0x020000                                       |
| linux1/                                       | Yes      | Update for the main Linux Kernel                                       |
| passwdupdate/                                 | Yes      | Scripts to "update" the passwd file as well as authorized_keys         |
| preloaddata/                                  | Yes      | Unknown                                                                |
| resources/                                    | Yes      | Unknown                                                                |
| rootfs1upd/                                   | Yes      | rootfs files                                                           |
| usersettingsbackup/                           | Yes      | Unknown                                                                |
| usersettingscleanup/                          | Yes      | Unknown                                                                |
| usersettingsrestore/                          | Yes      | Unknown                                                                |
| vip/                                          | Yes      | Update for the microcontroller that is used for CAN/LIN communications |
| checksumoption/                               | Yes      | Unknown                                                                |
| [fail-safe/](failsafe-boot.md)                | Yes      | Failsafe image for SPI-NOR:0x0E0000                                    |
| [ibc2/](failsafe-boot.md)                     | Yes      | Update for IBC2 SPI-NOR:0x040000                                       |







## Certificate Chain
- /jci/certificates/jci_root_cert.pem
- update.zip/jci_subord_cert.pem
- update.zip/publisher_cert.pem


## Validation
1. Root certificate integrity is validated.
2. Subordinate certificate is checked against Root certificate
3. Publisher certificate is checked against Subordinate certificate
4. Signature is validated against Publisher certificate


## main_instructions.ini

### [Settings]
#### Fields:
- PackageID
- CompressionType
- TotalStepsCount

### [Instructions]
#### Fields
| Keys                    | Details                                                                                                                                                                                                                                           |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Count                   | Contains the number of instructions                                                                                                                                                                                                               |
| 1 <br/> ... <br/> Count | Contains the instruction details which are comma delimited in the format <br/>                          Operation, Directory, step INI file, Count of instructions in step INI file <br>Available operations are Execute, ImageUpdate, FileUpdate |
|                         |



### [DataStorage]
#### Fields
- Count
- UPType
- ReTransmit


