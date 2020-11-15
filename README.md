# Rehost

A tool I wrote to use in CTFs (TryHackMe, HackTheBox, etc.) to host tools to transfer to target machines.

### To install:
`cargo install rehost`

### To run: 
`rehost examples/example.toml`

### Replace vars:
`IP=1.2.3.4 rehost examples/example.toml -o`

### Bind to custom host ip and port:
`rehost examples/example.toml -h 192.168.1.42 -p 80`