# multidownload
go multidownload

基于go编写的多线程（协程）下载器

## 下载方式

1. 项目执行go build 打包为.exe可执行文件

   ```go
   go build . 
   ```

2. 源码目录执行

   ```go
   > go mod tidy
   > go run main.go download.go --url xxxxx
   ```

## 传入参数

```
可执行 --help查看具体参数
1. --url  （必传，下载地址）
2. --output filename   （非必传，输出文件名称）
3. --concurrency number  （非必传， 并发数量）
```

