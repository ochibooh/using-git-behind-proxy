# Using GIT behind a proxy network
We are going to look at how to configure git to work behind a proxy network.

## Setup proxy
### Configure
Setup proxy for global use. This will be used by all repos.

```bash
git config --global http.proxy http://user-name:password@server-ip:port
```
or
```bash
git config --global http.proxy http://server-ip:port
```
