# blaharch-repo 

the official package repository for the blahArch linux distribution and the `haj` package manager. 

hosted natively via github pages. view the [web interface](https://asitos.github.io/blaharch-repo/).

## installation

append the following configuration to the bottom of your `/etc/pacman.conf`:

```ini
[blaharch]
SigLevel = Optional TrustAll
Server = https://asitos.github.io/blaharch-repo/$arch
```

## usage

sync your local databases and install packages directly:
```bash
sudo pacman -Sy haj
```

## links
- [haj source code](https://github.com/asitos/haj)
- [blahArch repo landing page](https://asitos.github.io/blaharch-repo/)
