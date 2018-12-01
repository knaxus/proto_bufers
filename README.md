# Learning proto-bufers

Protocol buffers are a language-neutral, platform-neutral extensible mechanism for serializing structured data.

## Quick Notes

If you want to compile proto files to **golang** and you're using **zhs** instead of **bash** in Ubuntu/MacOS, add the following lines in you `.zshrc`. Follow the steps:

- `vim ~/.zhsrc`
- Add the following:
  - `export GOPATH=$HOME/go`
  - `export GOBIN=$GOPATH/bin`
  - `export PATH=$PATH:$GOPATH/bin`
