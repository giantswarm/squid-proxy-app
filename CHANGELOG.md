# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Add `cronitor.io` to allowed domains.

## [0.6.2] - 2025-10-03

### Added

- Add `api.eu.pagerduty.com` to allowed domains.
- Add `.grafana.net` to allowed domains.

### Removed

- Remove auth0 (`giantswarm.eu.auth0.com`).
- Removed redundant domains.

## [0.6.1] - 2024-10-03

### Added

- Allow `xpkg.upbound.io` in order to allow downloading the crossplane providers.

## [0.6.0] - 2024-05-02

### Changed

- Allow `.slack.com` in order to allow Alertmanager to use new Slack API (at `https://slack.com/api`) and also keep backward compatibility with the old Slack Webhooks API (at `https://hooks.slack.com`).

## [0.5.5] - 2024-02-14

### Added

- Allow `.gigantic.io` and `.grafana.org` domains and subdomains.

## [0.5.4] - 2024-02-13

### Fixed

- Fix `external-dns.alpha.kubernetes.io/hostname` annotation.

## [0.5.3] - 2024-02-09

### Added

- Missing required domains from allowlist

## [0.5.2] - 2024-02-08

### Fixed

- Fix loading of custom config files.

## [0.5.1] - 2024-02-08

### Fixed

- Fix volumeMount indentation in deployment.

## [0.5.0] - 2024-02-08

### Added

- Add `sts.eu-north-1.amazonaws.com` to allowed domains.

## [0.4.0] - 2023-12-07

### Added

- Add `global.podSecurityStandards.enforced` value for PSS migration.

### Changed

- Configure `gsoci.azurecr.io` as the default container image registry.

## [0.3.4] - 2023-07-18

### Changed

- Fix PSP permissions for the pod

## [0.3.3] - 2023-07-18

### Changed

- Update squid docker image and adjust setting in order to run on Flatcar.

## [0.3.2] - 2023-07-13

## [0.3.1] - 2023-07-12

## [0.3.0] - 2023-06-27

### Added

- Add allowlist configuration
- Add necessary values for PSS policy warnings.

## [0.2.1] - 2022-11-29

## [0.2.0] - 2022-11-23

- Add network policy to helm templates.

## [0.1.3] - 2022-11-02

## [0.1.2] - 2022-09-26

## [0.1.1] - 2022-09-16

### Changed

- Add external dns annotation on the service.

## [0.1.0] - 2022-09-16

- add base template
- changed: `app.giantswarm.io` label group was changed to `application.giantswarm.io`

[Unreleased]: https://github.com/giantswarm/squid-proxy-app/compare/v0.6.2...HEAD
[0.6.2]: https://github.com/giantswarm/squid-proxy-app/compare/v0.6.1...v0.6.2
[0.6.1]: https://github.com/giantswarm/squid-proxy-app/compare/v0.6.0...v0.6.1
[0.6.0]: https://github.com/giantswarm/squid-proxy-app/compare/v0.5.5...v0.6.0
[0.5.5]: https://github.com/giantswarm/squid-proxy-app/compare/v0.5.4...v0.5.5
[0.5.4]: https://github.com/giantswarm/squid-proxy-app/compare/v0.5.3...v0.5.4
[0.5.3]: https://github.com/giantswarm/squid-proxy-app/compare/v0.5.2...v0.5.3
[0.5.2]: https://github.com/giantswarm/squid-proxy-app/compare/v0.5.1...v0.5.2
[0.5.1]: https://github.com/giantswarm/squid-proxy-app/compare/v0.5.0...v0.5.1
[0.5.0]: https://github.com/giantswarm/squid-proxy-app/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/giantswarm/squid-proxy-app/compare/v0.3.4...v0.4.0
[0.3.4]: https://github.com/giantswarm/squid-proxy-app/compare/v0.3.3...v0.3.4
[0.3.3]: https://github.com/giantswarm/squid-proxy-app/compare/v0.3.2...v0.3.3
[0.3.2]: https://github.com/giantswarm/squid-proxy-app/compare/v0.3.1...v0.3.2
[0.3.1]: https://github.com/giantswarm/squid-proxy-app/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/giantswarm/squid-proxy-app/compare/v0.2.1...v0.3.0
[0.2.1]: https://github.com/giantswarm/squid-proxy-app/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/giantswarm/squid-proxy-app/compare/v0.1.3...v0.2.0
[0.1.3]: https://github.com/giantswarm/squid-proxy-app/compare/v0.1.2...v0.1.3
[0.1.2]: https://github.com/giantswarm/squid-proxy-app/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/giantswarm/squid-proxy-app/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/squid-proxy-app/releases/tag/v0.1.0
