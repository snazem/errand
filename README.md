# errand

Run time-limited jobs as a platform-specific service with a portable time-based
job scheduler.

## Build Instructions

``` shell
$ git clone https://github.com/shanebarnes/errand $GOPATH/src/github.com/shanebarnes/errand
$ cd $GOPATH/src/github.com/shanebarnes/errand
$ go get -v ./...
$ go build -v
```

## Run Instructions

``` shell
$ sudo ./errand -service install
$ sudo ./errand -service start
$ sudo ./errand -service stop
$ sudo ./errand -service uninstall
```
