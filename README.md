# nso-access

Access Port provisioning service powered by Cisco Network Services Orchestrator(NSO)


More documentation will be coming soon!

# Supported Platforms
Any IOS device
Any NX-OS device


# Instructions
1. Clone this package (`access`) into your NSO server's or project's packages directory.
2. In your NSO's command line (ncs_cli -C), perform a packages reload.
3. Now the package will appear in the modules menu as `access` in your NSO's native UI.


# sample usage
The following commands can be used to interact with NCS in this directory:

```
ncs -c ./ncs.conf                         -- to start NCS as a daemon
ncs -c ./ncs.conf --foreground --verbose  -- start NCS in foregound
ncs --stop                                -- stop NCS
ncs_cli -u admin                          -- start a CLI into NCS
ncs-setup --eclipse-setup                 -- create eclipse dev files here
```
