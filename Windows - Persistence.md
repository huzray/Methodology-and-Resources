
# Windows - Persistence

:warning: Content of this page has been moved to [InternalAllTheThings/redteam/persistence/windows](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/)

- [Tools](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#tools)
- [Hide Your Binary](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#hide-your-binary)
- [Disable Antivirus and Security](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#disable-antivirus-and-security)
    - [Antivirus Removal](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#antivirus-removal)
    - [Disable Windows Defender](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#disable-windows-defender)
    - [Disable Windows Firewall](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#disable-windows-firewall)
    - [Clear System and Security Logs](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#clear-system-and-security-logs)
- [Simple User](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#simple-user)
    - [Registry HKCU](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#registry-hkcu)
    - [Startup](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#startup)
    - [Scheduled Tasks User](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#scheduled-tasks-user)
    - [BITS Jobs](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#bits-jobs)
- [Serviceland](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#serviceland)
    - [IIS](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#iis)
    - [Windows Service](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#windows-service)
- [Elevated](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#elevated)
    - [Registry HKLM](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#registry-hklm)
        - [Winlogon Helper DLL](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#)
        - [GlobalFlag](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#)
    - [Startup Elevated](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#startup-elevated)
    - [Services Elevated](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#services-elevated)
    - [Scheduled Tasks Elevated](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#scheduled-tasks-elevated)
    - [Binary Replacement](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#binary-replacement)
        - [Binary Replacement on Windows XP+](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#binary-replacement-on-windows-xp)
        - [Binary Replacement on Windows 10+](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#binary-replacement-on-windows-10)
    - [RDP Backdoor](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#rdp-backdoor)
        - [utilman.exe](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#utilman.exe)
        - [sethc.exe](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#sethc.exe)
    - [Remote Desktop Services Shadowing](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#remote-desktop-services-shadowing)
    - [Skeleton Key](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#skeleton-key)
    - [Virtual Machines](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#virtual-machines)
    - [Windows Subsystem for Linux](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#windows-subsystem-for-linux)
- [Domain](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#domain)
    - [Golden Certificate](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#golden-certificate)
    - [Golden Ticket](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#golden-ticket)
- [References](https://swisskyrepo.github.io/InternalAllTheThings/redteam/persistence/windows-persistence/#references)
