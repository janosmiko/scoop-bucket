# scoop-bucket

Scoop bucket for [janosmiko](https://github.com/janosmiko)'s CLI tools.

## Usage

```powershell
scoop bucket add janosmiko https://github.com/janosmiko/scoop-bucket
scoop install lfk
```

## Available manifests

Manifests live under `bucket/`. Each is auto-generated and updated by [GoReleaser](https://goreleaser.com) on each release of the corresponding tool's repo.

| Tool | Source repo | Description |
|---|---|---|
| `lfk` | [janosmiko/lfk](https://github.com/janosmiko/lfk) | Lightning Fast Kubernetes navigator |
