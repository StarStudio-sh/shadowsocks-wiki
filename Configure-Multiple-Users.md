You can use different passwords on different ports like this:

    {
        "server": "127.0.0.1",
        "server_port": 8381,
        "local_port": 1081,
        "password": "foobar1",
        "port_password": {
            "8381": "foobar1",
            "8382": "foobar2",
            "8383": "foobar3",
            "8384": "foobar4"
        },
        "timeout": 60,
        "method": "aes-256-cfb"
    }