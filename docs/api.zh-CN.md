# API 参考

[English](api.md) | [文档索引](README.zh-CN.md)

本清单由本仓库 package 的 `go doc -short` 生成，用于快速查看公共面。精确语义以源码和测试为准。

## 包

### `gnalloy.org/handler-flow`

包名：`flow`

```text
var ErrInvalidConfig = errors.New("gnalloy/handler/flow: invalid config") ...
func MessageSize(msg any) int
type Config struct{ ... }
type Handler struct{ ... }
    func NewHandler(cfg Config) (*Handler, error)
type Snapshot struct{ ... }
```
