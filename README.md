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



This repository contains configuration files and documentation for Headwind MDM...




| Type                  | Purpose                                                                 | Payload                                      |
|-----------------------|-------------------------------------------------------------------------|----------------------------------------------|
| configUpdated         | Notify the device about the configuration update                       | none                                         |
| runApp                | Start an application                                                   | `{pkg: "app.package.id"}`                   |
| uninstallApp          | Uninstall an application                                               | `{pkg: "app.package.id"}`                   |
| deleteFile            | Delete a file (the path is relative to the external storage)           | `{path: "/path/to/file"}`                   |
| deleteDir             | Delete a directory recursively                                         | `{path: "/path/to/dir"}`                    |
| purgeDir       

| Constant (UserManager)                  | Constant Value                     | Summary/Description |
|-----------------------------------------|------------------------------------|---------------------|
| DISALLOW_ADD_WIFI_CONFIG                | "no_add_wifi_config"               | Impide al usuario agregar nuevas configuraciones WiFi |
| DISALLOW_CHANGE_WIFI_STATE              | "no_change_wifi_state"             | Bloquea cambios en el estado WiFi (activar/desactivar) |
| DISALLOW_CONFIG_WIFI                    | "no_config_wifi"                   | Restringe cualquier configuración de redes WiFi |
| DISALLOW_SHARING_ADMIN_CONFIGURED_WIFI  | "no_sharing_admin_configured_wifi" | Evita compartir WiFi configurado por el administrador |
| DISALLOW_BLUETOOTH                      | "no_bluetooth"                     | Desactiva completamente Bluetooth |
| DISALLOW_CONFIG_BLUETOOTH               | "no_config_bluetooth"              | Bloquea la configuración de Bluetooth |
| DISALLOW_BLUETOOTH_SHARING              | "no_bluetooth_sharing"             | Impide compartir archivos via Bluetooth |
| DISALLOW_AIRPLANE_MODE                  | "no_airplane_mode"                 | Evita que el usuario active el modo avión |
| DISALLOW_DATA_ROAMING                   | "no_data_roaming"                  | Desactiva roaming de datos móviles |
| DISALLOW_NETWORK_RESET                  | "no_network_reset"                 | Bloquea el restablecimiento de configuraciones de red |
| DISALLOW_CONFIG_MOBILE_NETWORKS         | "no_config_mobile_networks"        | Restringe configuración de redes móviles |
| DISALLOW_CONFIG_TETHERING               | "no_config_tethering"              | Impide configurar anclaje a red (tethering) |
| DISALLOW_CONFIG_VPN                     | "no_config_vpn"                    | Bloquea configuración de VPN |
| DISALLOW_THREAD_NETWORK                 | "no_thread_network"                | Restringe redes Thread (IoT) |
| DISALLOW_FACTORY_RESET                  | "no_factory_reset"                 | Impide el restablecimiento de fábrica |
| DISALLOW_MODIFY_ACCOUNTS                | "no_modify_accounts"               | Bloquea añadir/eliminar cuentas |
| DISALLOW_REMOVE_MANAGED_PROFILE         | "no_remove_managed_profile"        | Evita eliminar perfiles gestionados |
| DISALLOW_SHARING_INTO_PROFILE           | "no_sharing_into_profile"          | Restringe compartir datos al perfil |
| DISALLOW_ADD_MANAGED_PROFILE            | "no_add_managed_profile"           | Impide crear nuevos perfiles gestionados |
| DELEGATION_BLOCK_UNINSTALL              | "delegation-block-uninstall"       | Bloquea desinstalación delegada |
| DISALLOW_CONTROL_APPS                   | "no_control_apps"                  | Restringe control sobre apps |
| DISALLOW_INSTALL_APPS                   | "no_install_apps"                  | Impide instalar aplicaciones |
| DISALLOW_UNINSTALL_APPS                 | "no_uninstall_apps"                | Bloquea desinstalar apps |
| DISALLOW_CONFIG_DEFAULT_APPS            | "disallow_config_default_apps"     | Restringe cambiar apps predeterminadas |
| DISALLOW_SIM_GLOBALLY                   | "no_sim_globally"                  | Desactiva funciones SIM globalmente |
| ENSURE_VERIFY_APPS                      | "ensure_verify_apps"               | Fuerza verificación de apps |
| DISALLOW_ASSIST_CONTENT                 | "no_assist_content"                | Restringe contenido de asistentes |
| DISALLOW_PHYSICAL_MEDIA                 | "no_physical_media"                | Bloquea medios físicos (USB/SD) |
| DISALLOW_SET_WALLPAPER                  | "no_set_wallpaper"                 | Impide cambiar el fondo de pantalla |
| DISALLOW_DEBUGGING_FEATURES             | "no_debugging_features"            | Desactiva opciones de depuración |
| DISALLOW_GRANT_ADMIN                    | "no_grant_admin"                   | Evita conceder privilegios de admin |
| DISALLOW_INSTALL_UNKNOWN_SOURCES        | "no_install_unknown_sources"       | Bloquea instalar desde orígenes desconocidos |
| DISALLOW_INSTALL_UNKNOWN_SOURCES_GLOBALLY| "no_install_unknown_sources_globally" | Versión global de la restricción anterior |
| DISALLOW_SYSTEM_ERROR_DIALOGS           | "no_system_error_dialogs"          | Oculta diálogos de error del sistema |
| DISALLOW_SAFE_BOOT                      | "no_safe_boot"                     | Impide el arranque seguro |
