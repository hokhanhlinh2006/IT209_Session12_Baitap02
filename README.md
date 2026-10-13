# Docker Release Demo

## Mục tiêu
Tự động build và phát hành Docker Image lên GHCR
khi push Git Tag theo định dạng v*.*.*.

## Công nghệ
- Java 21
- Gradle
- Docker
- GitHub Actions
- GitHub Container Registry (GHCR)

## Phát hành phiên bản

```bash
git tag v1.0.0
git push origin v1.0.0