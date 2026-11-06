# quick-binder-lite

Graphics engineer @Shopify

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

## 安装

```bash
git clone https://github.com/USER/quick-binder-lite.git
cd quick-binder-lite
cargo build --release
```

## 待办

- [ ] 支持从文件参数读入
- [ ] 加个输出格式选项
- [ ] 补点测试

## 备注

就是给自己省点事，没做太多抽象。

## License

MIT
