# grpc-go-sample

grpcをgoで動かすサンプルです。

## 事前準備

protobufをインストールしましょう。
[公式](https://github.com/protocolbuffers/protobuf/releases)からダウンロードしてPATHを通しましょう。
macなら`brew install protobuf`で入ります

※goが1.13以下の人は`export GO111MODULE=on`してから

```
$ git clone https://github.com/s-take/grpc-go-sample.git
$ cd grpc-go-sample
$ go mod download
```

### サーバ側実行

```
$ go run server/main.go
```

### クライアント側実行

```
$ go run client/main.go
```
