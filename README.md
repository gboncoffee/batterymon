# Batterymon

A simple Python program to run commands whenever the system's battery reaches
a state. By default it runs a notification with `notify-send`. (Probably)
cross-platform, only tested on Linux.

# Installing

Batterymon can be used just placing the `batterymon` script anywhere in your
`$PATH`.

Batterymon depends on the Python library [psutil](https://github.com/giampaolo/psutil).

# Configuration

Configuration is stored in `$HOME/.config/batterymon/config.ini`, and the
default file is stored in `/etc/batterymon/config.ini`. Copy the default file
and edit following the instructions on the comments.
