

## Google Authenticator
Forked from https://github.com/tilaklodha/google-authenticator

A small go program to generate the google authenticator code.

- Setup go
    - Make sure that the executable `go` is in your shell's path.
    - Add the following in your .zshrc or .bashrc: (where `<workspace_dir>` is the directory in
        which you'll checkout your code)

```
GOPATH=<workspace_dir>
export GOPATH
PATH="${PATH}:${GOPATH}/bin"
export PATH
```

- Clone the repo in your GOPATH
- Provide your 16-digit secret token in `~/.vpn_secrets.pem` file
- Run below commands in repo dir: 
   `go build -o otp google_authenticator.go`
   `go install`


- Start using otp :-)
