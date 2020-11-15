# Rehost

A tool I wrote to use in CTFs (TryHackMe, HackTheBox, etc.) to host files to transfer to target machines that aren't connected to the internet.

Written in rust so it's probably secure or something like that blah blah but like don't use this in production dummy

## To install:
There's binaries in the releases

## To build:
To install cargo if you don't have it already:

`curl https://sh.rustup.rs -sSf | sh` 

If you're using windows, then go to [https://www.archlinux.org]() and install a real operating system

Then:

`cargo install rehost`

## To run: 
`rehost examples/example.toml`

## Replace vars:
`IP=1.2.3.4 rehost examples/example.toml -o`

## Bind to custom host ip and port:
`rehost examples/example.toml -h 192.168.1.42 -p 80`
