![Build Status](https://github.com/team-gary/asdf-golang/workflows/CI/badge.svg)

# asdf-golang
golang plugin for [asdf version manager](https://github.com/asdf-vm/asdf)


## Requirements
**Ubuntu 16.04+** `curl`


## Install

```
asdf plugin-add golang https://github.com/team-gary/asdf-golang.git
```

## Use

Check the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of go.

## When using `go get`

After using `go get` to install a package you need to run `asdf reshim golang` to get any new shims.

## Contributing

Feel free to create an issue or pull request if you find a bug.

## License
MIT License
