# Changelog
All notable changes to the image will be documented in this file.

## [1.22.1-patch.1] - 2025-06-11

### Changed

- Updated Alpine Linux base image to `3.20` to address CVE-2025-1094 vulnerability

## [1.22.1-patch.0] - 2024-04-24

### Changed

- Updated PgBouncer to version `1.22.1`
- Updated Alpine Linux to `3.19` branch

## [1.18.0-patch.1] - 2023-04-06

### Added

- Added `openssl` to image (for generating self-signed certificates)

## [1.18.0-patch.0] - 2023-04-05

### Changed

- Updated PgBouncer to version `1.18.0`
- Updated Alpine Linux to `3.15` branch

## [1.17.0-patch.0] - 2022-03-28

### Added
- Build images for `linux/arm64` (in addition to `linux/amd64`)

### Changed
- Updated PgBouncer to version `1.17.0`
- Updated Alpine Linux to `3.14` branch

## [1.15.0-patch.0] - 2021-07-27

### Added
- Initial release of Dockerfile with PgBouncer version `1.15.0`

[1.22.1-patch.0]: https://github.com/airflow-helm/charts/tree/images/pgbouncer-1.22.1-patch.0/images/pgbouncer
[1.18.0-patch.1]: https://github.com/airflow-helm/charts/tree/images/pgbouncer-1.18.0-patch.1/images/pgbouncer
[1.18.0-patch.0]: https://github.com/airflow-helm/charts/tree/images/pgbouncer-1.18.0-patch.0/images/pgbouncer
[1.17.0-patch.0]: https://github.com/airflow-helm/charts/tree/images/pgbouncer-1.17.0-patch.0/images/pgbouncer
[1.15.0-patch.0]: https://github.com/airflow-helm/charts/tree/images/pgbouncer-1.15.0-patch.0/images/pgbouncer
