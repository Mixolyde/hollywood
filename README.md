# About
_Hollywood_ is a utility that will split a computer console into multiple panes of 
genuine technical melodrama, perfectly suitable for busy-looking computers in the background of a tv show or movie.

# Installation
## On Ubuntu or Debian
```
sudo apt install -y hollywood --install-recommends && hollywood
```

## Run in Docker
```
docker run -it --rm jess/hollywood
```

## View the [Source Code](https://github.com/dustinkirkland/hollywood)
```
git clone https://github.com/dustinkirkland/hollywood.git
```

# Features

* Launch Byobu
* Open a random number of splits, random sizes
* In each split, run a noisy text app

# Modules
## Rules for Modules

 - Must work as a non-root user
 - Must display information indefinitely (a la "watch", or cmatrix)
   - Can use a while/true + a timeout
 - Must not Out Of Memory a system
 - Must not over load a system
 - Must not be too egregious with I/O
 - Must not require outbound internet access

## Completed Modules
 - apg
 - atop - Works as a regular user, but with less info
 - bmon - DONE
 - cmatrix - DONE
 - code - DONE
 - errno
 - hexdump
 - htop
 - jp2a
 - logs
 - man
 - map
 - mplayer - converts soundwave video go ascii, performance hog
 - speedometer - network traffic monitor
 - sshart - generates ssh keys
 - stat
 - tree


