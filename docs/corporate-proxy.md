# Using a Corporate Proxy

When running kpack behind a corporate proxy, you can configure the controller to proxy communications with external services, such as Git servers and container registries.

```yaml
proxy:
  http_proxy: "proxy.kadras.io"
  https_proxy: "proxy.kadras.io"
  no_proxy: ".svc, .cluster.local"
```
