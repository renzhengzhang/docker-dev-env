# docker-dev-env

A Docker Compose / Podman Compose setup for quickly initializing a local development environment.

## Services

* MySQL 8.0
* PostgreSQL 18.0
* Redis 7.2

## Usage

Copy the environment configuration:

```bash
cp .env.example .env
```

Start the services:

```bash
podman compose up -d
```

Check service status:

```bash
podman compose ps
```

View logs:

```bash
podman compose logs -f
```

Stop the services:

```bash
podman compose down
```

---

# 中文

用于快速初始化本地开发环境的 Docker Compose / Podman Compose 配置。

## 服务

* MySQL 8.0
* PostgreSQL 18.0
* Redis 7.2

## 使用方式

复制环境变量配置：

```bash
cp .env.example .env
```

启动服务：

```bash
podman compose up -d
```

查看服务状态：

```bash
podman compose ps
```

查看日志：

```bash
podman compose logs -f
```

停止服务：

```bash
podman compose down
```
