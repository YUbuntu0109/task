<p align="center">
	<a href=""><img src="https://ishacker.net/2020/06/21/image-repo/task.go.v1.0.logo.png" width="666"></a>
<p align="center">

![Go](https://github.com/YUbuntu0109/task/workflows/Go/badge.svg?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/YUbuntu0109/task)](https://goreportcard.com/report/github.com/YUbuntu0109/task)

# Task.go
> It's not only a todo list but also a notebook and file mangage system, which base on vue, gin framework and sqlite3 database. so no complicated configurations and run it by one command !
* `go` v1.14.5
* `vue` v2.0
* `gin` v1.6.3
* ~`docker` v2.5.0.1~
* `gorm` v1.20.1
* `gopkg` v1.62.0
* `sqlite3` v3.33.0

## How To Run
### build
```shell script
go build
```

### run
```shell script
# Mac / Unix
./task conf/config.ini

# Windows
task.exe conf/config.ini
```

finally, open your browser and input the url : *http://127.0.0.1:9000/*, please modify the content of config.ini file if you want to custom the configuration information bro.
