# SSH to Hosts

SSH to multiple hosts in different terminal windows
via [`itermocil`](https://github.com/TomAnthony/itermocil)

## Install

```
brew install gamechanger/brews/sshtohosts
mkdir ~/.teamocil/
```

## Usage

Hosts are provided via `stdin` which makes it easy to use with pipes.
Useful with infrastructure toolks like
[`awsprey`](https://github.com/agamdua/awsprey).

```
cat hosts.txt | sshtohosts
awsprey list service:production | sshtohosts
```
