# Welcome PDX DevOps-ers!

These are the slides I showed at [PDX DevOps on March 25, 2020](https://www.meetup.com/Portland-DevOps-GroundUp/events/djhzznybcfbhc/).

To see slides, make sure you have [Caddy v2](https://caddyserver.com) installed (if you need to install caddy, see [below](./installing-caddy)) and run the following:

```console
$ caddy run
```

Fire up your browser of choice and go to http://localhost:8000. Then press `f` to enter full screen.

## Installing Caddy

Run the following to install caddy on 64 bit Linux:

```bash
$ curl -L -o caddy https://github.com/caddyserver/caddy/releases/download/v2.0.0-beta.19/caddy2_beta19_linux_amd64
$ chmod +x ./caddy
$ mv caddy /usr/local/bin/caddy
```

>You may need to use `sudo` on the final `mv` command, depending on the configuration of your system
