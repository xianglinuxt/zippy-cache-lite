# zippy-cache-lite

gRPC · Kafka · Go

给自己省点事的小工具

## 用法

```bash
cat data.txt | cargo run
```

输出：

```
   3  error: timeout
   1  warn: retry
---
2 unique / 4 lines
```

## 为什么写

现有的工具都太重，就想要个能管道拼接的小东西。

## 安装

```bash
git clone https://github.com/USER/zippy-cache-lite.git
cd zippy-cache-lite
cargo build --release
```

## License

MIT
