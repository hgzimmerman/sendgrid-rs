# sendgrid-rs
Unofficial Rust library for SendGrid API

You must download an API key in order to use this library. I made it this way
to keep you more secure by using environment variables instead of including
sensitive information in your source code.

To create an API key for your SendGrid account see this [page](https://sendgrid.com/docs/API_Reference/Web_API_v3/API_Keys/index.html).

Then set that key as an environment variable as such (works with Bash and ZSH).

```shell
export SENDGRID_API_KEY="my.API.KEY"
```

See the examples directory on how to use environment variables in Rust.

# License
MIT
