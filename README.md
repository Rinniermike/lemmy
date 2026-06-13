# Chozi

A community platform powered by Lemmy — a federated link aggregator and forum for the fediverse.

> This is the backend server for the Chozi community platform, forked from [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy).

## About

Chozi is a self-hosted community platform. Users can subscribe to communities, post links and discussions, vote, and comment. The platform is federated via ActivityPub, meaning Chozi can connect with other Lemmy and Fediverse instances.

## Configuration

See `config/defaults.hjson` for all configuration options.

Key settings for your Chozi instance:
- `hostname`: Set to your domain (e.g. `chozi.app`)
- `setup.site_name`: Set to "Chozi"
- `setup.admin_username`: Your admin account username
- `setup.admin_password`: **Change before deploying**
- `database.connection`: PostgreSQL connection string

## Development & Deployment

### Prerequisites
- Rust (latest stable)
- PostgreSQL
- Docker (recommended for deployment)

### Docker (Recommended)
```bash
cd docker
docker compose up -d
```

### Local Development
See the [Lemmy contributing docs](https://join-lemmy.org/docs/en/contributing/contributing.html) for full setup instructions.

## License

AGPL-3.0 — see [LICENSE](LICENSE) for details.

---
*Powered by [Lemmy](https://github.com/LemmyNet/lemmy)*
