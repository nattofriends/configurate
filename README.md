# configurate
`configurate` is a set of shell scripts for server configuration, ensuring the appearance of propriety by using the LSB init functions.

## Usage
    [06/22 17:11:00] ~/configurate (master) $ ./configurate ~/Runfile.dev
    [info] configurate starting....
    
    [info] Module output available at /tmp/configurate_201506221711_nd8m.log.
    [info] Running module set_locale "America/Los_Angeles" "en_US.UTF-8".
    [ ok ] Setting locale and timezone...done.
    [info] Running module aptitude/update.
    [ ok ] Updating package lists...done.
    [info] Running module aptitude/install htop git ntp ntpdate.
    [ ok ] Installing packages: htop git ntp ntpdate...done.
    [info] Running module aptitude/install vim-nox tmux.
    [ ok ] Installing packages: vim-nox tmux...done.
    [info] Running module aptitude/install python2 python3.
    [ ok ] Installing packages: python2 python3...done.
    [info] Running module aptitude/install build-essential.
    [ ok ] Installing packages: build-essential...done.
