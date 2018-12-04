# iptrest
REST front-end for iptables-based por redirection

## Usage

You can use the `iptrest` app to maintain your iptables tables, for port redirection from one DMZ host to nodes in the internal network.

Please use `iptrest --help` to obtain information on how to use it.

### REST server

If you plan to use the REST fron-end, you can use `iptrestd` application.

1. Install https://github.com/grycap/autorest
2. Install the python-bottle package
3. Adjust the variable `IPTREST_APP` in `iptrestd` to point to `iptrest`
4. Execute iptrestd and enjoy.
