# puppy

## Create go module named as git repo at the root of my puppy package

go mod init github.com/hasanashik/puppy

## Clean Go’s module cache

go clean -modcache

## get dog package

go get github.com/hasanashik/dog@latest
go mod tidy
go get github.com/hasanashik/dog@v1.2.1
