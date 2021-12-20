initial file, still need to actually write useful stuff

The /etc/unifi/api.json file looks like:

    { 
        "user": "USERNAME",
        "server": "HOSTNAME",
        "pass": "PASSWORD",
        "site": "default",
        "port": 8443,
        "cert_valid": true
    }

`cert_valid` should be set to true if you have a legitimate, signed SSL
cert for the host (say, via letsencrypt), false otherwise (self-signed).
