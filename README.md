A simple HTTP static file server written in Rust with
[rotor-http](https://github.com/tailhook/rotor-http).

[The source is simple, and commented for easy comprehension](src/main.rs).


```
USAGE:
        basic-http-server [FLAGS] [OPTIONS] [ARGS]

FLAGS:
    -h, --help       Prints help information
    -V, --version    Prints version information

OPTIONS:
    -a, --addr <ADDR>    Sets the IP:PORT combination (default "127.0.0.1:4000")

ARGS:
    ROOT    Sets the root dir (default ".")

```

## License

MIT/Apache-2.0
