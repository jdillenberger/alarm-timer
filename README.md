# alarm-timer

Simple linux command line timer for Linux.

# Installation

Preconditions:

- Linux system
- GIT installed
- Python3 installed
- (sound-theme-freedesktop installed)

> Instead of the sound-theme-freedesktop sounds you could use another sound. To do that just change the soundfile path in `alarm`.

If you met those requirements you just need to enter the following commands:
```
git clone git@github.com:jdillenberger/alarm-timer.git
cd alarm-timer
pip3 -r requirements.txt
ln -s "$(pwd)/alarm" "/usr/local/bin/alarm"
```

# Usage

After the alarm-timer is installed you can use it as follows:

```
alarm 0d 2h 0m 15s
```

But you do not need to enter all of these parts. Therefore you can shorten the command to

```
alarm 2h 15s
```

Additionally you do not need to specifiy that the seconds are seconds - if you want to run the timer for 15 seconds you could write:

```
alarm 15
```

