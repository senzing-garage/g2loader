# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
[markdownlint](https://dlaa.me/markdownlint/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.2.6] - 2023-12-14

### Changed in 2.2.6

- Replaced deprecated `G2ModuleLicenseException` with `G2LicenseException`
  
## [2.2.5] - 2023-10-02

### Changed in 2.2.5

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.7.1`
- In `requirements.txt`, updated:
  - psycopg2-binary==2.9.8

## [2.2.4] - 2023-05-08

### Changed in 2.2.4

- Records not found for redo are no longer considered errors and are not reported

## [2.2.3] - 2023-04-04

### Changed in 2.2.3

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.5.0`
- In `requirements.txt`, updated:
  - psycopg2-binary==2.9.6

## [2.2.2] - 2022-10-11

### Changed in 2.2.2

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.3.1`

## [2.2.1] - 2022-09-29

### Changed in 2.2.1

- In `Dockerfile`, updated FROM instruction to `senzing/senzingapi-tools:3.3.0`

## [2.2.0] - 2022-08-25

### Changed in 2.2.0

- In `Dockerfile`, bump from `senzing/senzing-base:1.6.8` to `senzing/senzingapi-runtime:3.2.0`

## [2.1.1] - 2022-08-11

### Added to 2.1.1

- Fix incorrect G2IniParams import

## [2.1.0] - 2022-08-04

### Added to 2.1.0

- Improve workload stats dumping for each engine process
- Workload stats now dumped every 2 mins instead of x records
- Support for SENZING_ENGINE_CONFIGURATION_JSON
- Improve handling of CTRL-C for Postgres governor
- Fix uncaught exception on startup checks
- Add prologue warning G2Loader is a PoC tool
- Improved help
- Add basic Senzing repository information to startup output

## [2.0.3] - 2022-07-20

### Added to 2.0.3

- Change to default max threads per process.
- Add ability to get config_json from env variable.

## [2.0.2] - 2022-06-08

### Added to 2.0.2

- Alter the G2IniParams import, after it was removed from the SDK.

## [2.0.1] - 2022-05-25

### Added to 2.0.1

- Migrated Dockerfile from [docker-g2loader](https://github.com/senzing-garage/docker-g2loader) to this repository

## [2.0.0] - 2022-05-04

### Added to 2.0.0

- Support SenzingAPI 3.0.0

## [1.19.0] - 2021-05-17

### Added to 1.19.0

- Shipped with SenzingAPI 2.6.0

## [1.18.1] - 2021-05-06

### Added to 1.18.1

- Shipped with SenzingAPI 2.5.1

## [1.18.0] - 2021-04-15

### Added to 1.18.0

- Shipped with SenzingAPI 2.5.0

## [1.17.0] - 2021-02-24

### Added to 1.17.0

- Shipped with SenzingAPI 2.4.0

## [1.16.0] - 2020-12-15

### Added to 1.16.0

- Shipped with SenzingAPI 2.3.0

## [1.15.2] - 2020-10-29

### Added to 1.15.2

- Shipped with SenzingAPI 2.2.4

## [1.15.1] - 2020-10-23

### Added to 1.15.1

- Shipped with SenzingAPI 2.2.2

## [1.15.0] - 2020-09-30

### Added to 1.15.0

- Shipped with SenzingAPI 2.2.1

## [1.14.0] - 2020-09-03

### Added to 1.14.0

- Shipped with SenzingAPI 2.1.0

## [1.13.0] - 2020-07-16

### Added to 1.13.0

- Shipped with SenzingAPI 2.0.0

## [1.12.2] - 2020-06-17

### Added to 1.12.2

- Shipped with SenzingAPI 1.15.4

## [1.12.1] - 2020-04-28

### Added to 1.12.1

- Shipped with SenzingAPI 1.15.1

## [1.12.0] - 2020-04-20

### Added to 1.12.0

- Shipped with SenzingAPI 1.15.0

## [1.11.1] - 2019-11-06

### Added to 1.11.1

- Shipped with SenzingAPI 1.12.2

## [1.11.0] - 2019-10-16

### Added to 1.11.0

- Shipped with SenzingAPI 1.12.0

## [1.10.0] - 2019-09-03

### Added to 1.10.0

- Shipped with SenzingAPI 1.11.0

## [1.9.1] - 2019-11-06

### Added to 1.9.1

- Shipped with SenzingAPI 1.10.5

## [1.9.0] - 2019-07-09

### Added to 1.9.0

- Shipped with SenzingAPI 1.10.0

## [1.8.0] - 2019-06-04

### Added to 1.8.0

- Shipped with SenzingAPI 1.9.0

## [1.7.0] - 2019-05-08

### Added to 1.7.0

- Shipped with SenzingAPI 1.8.0

## [1.6.0] - 2019-04-05

### Added to 1.6.0

- Shipped with SenzingAPI 1.7.0

## [1.5.0] - 2019-03-02

### Added to 1.5.0

- Shipped with SenzingAPI 1.6.1

## [1.4.0] - 2019-01-31

### Added to 1.4.0

- Shipped with SenzingAPI 1.5.0

## [1.3.1] - 2018-12-20

### Added to 1.3.1

- Shipped with SenzingAPI 1.4.1

## [1.3.0] - 2018-12-07

### Added to 1.3.0

- Shipped with SenzingAPI 1.4.0

## [1.2.1] - 2018-10-09

### Added to 1.2.1

- Shipped with SenzingAPI 1.3.1

## [1.2.0] - 2018-10-02

### Added to 1.2.0

- Shipped with SenzingAPI 1.3.0

## [1.1.0] - 2018-09-30

### Added to 1.1.0

- Shipped with SenzingAPI 1.2.0

## [1.0.0] - 2018-09-18

### Added to 1.0.0

- Shipped with SenzingAPI 1.1.0
