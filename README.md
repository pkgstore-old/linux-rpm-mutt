# Mutt

**Mutt** is a text-based email client for Unix-like systems. It was originally written by Michael Elkins in 1995 and released under the GNU General Public License version 2 or any later version.

The Mutt slogan is "All mail clients suck. This one just sucks less."

## Install

### Fedora COPR

```
$ dnf copr enable pkgstore/mutt
$ dnf install -y mutt
```

### Open Build Service (OBS)

```
# Work in Progress
```

## Update

```
$ dnf upgrade -y mutt
```

## How to Build

1. Get source from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/mutt).
2. Write last commit SHA from [src.fedoraproject.org](https://src.fedoraproject.org/rpms/mutt) to [CHANGELOG](CHANGELOG).
3. Modify & update source (and `*.spec`).
4. Build SRPM & RPM.
