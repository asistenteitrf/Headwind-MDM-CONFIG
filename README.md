# Headwind MDM Configuration

![Logo](https://h-mdm.com/wp-content/uploads/2019/07/neew-logo.png "Headwind MDM Logo")

**Headwind MDM Configuration Repository**  
This repository contains configuration files and documentation for Headwind MDM...




| Type                  | Purpose                                                                 | Payload                                      |
|-----------------------|-------------------------------------------------------------------------|----------------------------------------------|
| configUpdated         | Notify the device about the configuration update                       | none                                         |
| runApp                | Start an application                                                   | `{pkg: "app.package.id"}`                   |
| uninstallApp          | Uninstall an application                                               | `{pkg: "app.package.id"}`                   |
| deleteFile            | Delete a file (the path is relative to the external storage)           | `{path: "/path/to/file"}`                   |
| deleteDir             | Delete a directory recursively                                         | `{path: "/path/to/dir"}`                    |
| purgeDir              | Delete all files in the directory (optionally delete subdirectories)   | `{path: "/path/to/dir", recursive: "1"}`    |
| permissiveMode        | Turn on permissive mode (do not block anything)                        | none                                         |
| reboot                | Reboot a device                                                        | none                                         |
| custom                | Specify a custom type and payload (for testing third-party apps)       | Application-specified                       |
| exitKiosk             | Turn off kiosk mode on a device                                        | none                                         |
| clearDownloadHistory  | Clear download history (when apps fail to download on mobile networks) | none 
