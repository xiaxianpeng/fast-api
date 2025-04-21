### 新建app目录

```shell

<!-- uv-fastapi-example -->

https://github.com/astral-sh/uv-fastapi-example
```
### uv与此应用程序一起使用
```shell

uv init --app
```

### 添加对 FastAPI 的依赖
```shell

<!-- 1.基础依赖 -->
uv add "fastapi>=0.110.0" "uvicorn>=0.34.2"

<!-- 2.性能优化组件 -->
uv add fastapi --extra standard
```


### 一致的开发环境
```shell

uv venv

uv sync
```

### 运行 FastAPI 应用程序
```shell

uv run fastapi dev
```

### 测试应用程序
```shell

http://127.0.0.1:8000/?token=jessica
```


