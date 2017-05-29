# [CI server with Dashboard](docs/ci.md)

# Installations
- [Superdesk for users](https://github.com/superdesk/fireq/tree/master/files/superdesk)
- [Superdesk for developers](https://github.com/superdesk/fireq/tree/master/files/superdesk#development)
- [Liveblog for users](https://github.com/superdesk/fireq/tree/master/files/liveblog)
- [Liveblog for developers](https://github.com/superdesk/fireq/tree/master/files/liveblog#development)

# Generate files
To test install scripts:
```sh
./fire gen-files

# superdesk
./fire lxc-init sd
cat files/superdesk/install | ./fire lxc-ssh sd
```
