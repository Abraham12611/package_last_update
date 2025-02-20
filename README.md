# package_last_update
An utility to get informations about a package last update

# usage:
    $ last_update <package_name>

so you can decide which packages needs to take care of :)

# examples:
    ./last_update direnv                                                  
    - direnv last version on openSUSE:Factory is 2.32.2 changed on Dec 07 2022
    
    ./last_update gzip                                                                                                                      master!?
    - gzip last version on openSUSE:Factory is 1.12 changed on Jan 03 10:44

    ./last_update k3sup                                                                                                                      master!?
    - k3sup last version on openSUSE:Factory is 0.12.7 changed on Oct 05 2022
      Other 4 repos may have newer versions, consider updating!

    ./last_update kicad                                                                                                              master
    - kicad last version on openSUSE:Factory is 6.0.9 changed on Nov 05 2022
      Other 33 repos may have newer versions, consider updating!

## requirements:
- a working configuration of [osc](https://en.opensuse.org/openSUSE:OSC), with authentication setup
- `pip3 install requests types-requests cmp_version`


