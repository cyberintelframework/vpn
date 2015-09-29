# VPN
[vpn-user-portal](https://github.com/eduVPN/vpn-user-portal) since version 1.0.3, 
supports Basic authentication to obtain configurations.

```
$ curl -u foo:bar -d 'name=agent007' http://localhost/vpn-user-portal/config/
$ curl -u foo:bar http://localhost/vpn-user-portal/config/agent007/ovpn
...
... OpenVPN config
...
```

Also supported is retrieving a ZIP version of the configuration by specifying `/zip` instead of `/ovpn`.
