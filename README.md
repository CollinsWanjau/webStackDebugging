# Web Stack Debugging

## Test and verify your assumptions

* Check the service manager, also process list.
* Check your web server configuration.
* `nestat -ldpn` - run as `root` to see the process for each listening
port.
* Is firewall enabled?
* `/var/log` and `tail -f`

## Get a quick overview of the machine state
