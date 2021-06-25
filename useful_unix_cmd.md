# Useful Unix Commands

## Watch

### Options

* `-n, --interval seconds` Specify update interval.  The command will not allow quicker than 0.1 second interval
* `-t, --no-title` Turn off the header showing the interval, command, and current time at the top of the display
* `-c, --color` Interpret ANSI color and style sequences

### Some Commands

* Watching a network interface come up: `watch -n 0.5 ip a`
* Showing the most CPU intensive processes: `watch "ps aux | sort -nrk 3,3 | head -n 5"`
