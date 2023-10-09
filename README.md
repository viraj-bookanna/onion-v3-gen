# onion-v3-gen
V3 onion address generator (with keys brute forcing)

## prerequisites

install golang if not
```
sudo apt install golang
```

install requirements
```
go mod init main.go
go mod tidy
```


## Usage

```
go run main.go <regex> <number>

    regex   regex pattern addresses should match, consisiting of: A-Z, 2-7
    number  number of matching addresses to generate before exiting
```

## implemented from: https://github.com/rdkr/oniongen-go