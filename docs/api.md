# API Reference

[简体中文](api.zh-CN.md) | [Docs Index](README.md)

This inventory is generated from `go doc -short` for the packages in this repository. It is a quick public-surface map; source files and tests remain the authority for exact semantics.

## Packages

### `gnalloy.org/handler-flow`

Package name: `flow`

```text
var ErrInvalidConfig = errors.New("gnalloy/handler/flow: invalid config") ...
func MessageSize(msg any) int
type Config struct{ ... }
type Handler struct{ ... }
    func NewHandler(cfg Config) (*Handler, error)
type Snapshot struct{ ... }
```
