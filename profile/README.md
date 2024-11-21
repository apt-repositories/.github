# APT Package Metadata

Provides APT package metadata for commonly used repositories as JSON-structured data.

For binary metadata, only `amd64` architecture is supported.

## Support

| Distribution | Version | Type         | Repository          |
| ------------ | ------- | ------------ | ------------------- |
| Debian       | 14      | unstable     | apt/debian/sid      |
| Debian       | 13      | testing      | apt/debian/trixie   |
| Debian       | 12      | stable       | apt/debian/bookworm |
| Debian       | 11      | oldstable    | apt/debian/bullseye |
| Debian       | 10      | oldoldstable | apt/debian/buster   |
| Ubuntu       | 24.10   |              | apt/ubuntu/oracular |
| Ubuntu       | 24.04   | LTS          | apt/ubuntu/noble    |
| Ubuntu       | 23.04   |              | apt/ubuntu/lunar    |
| Ubuntu       | 22.04   | LTS          | apt/ubuntu/jammy    |
| Ubuntu       | 20.04   | LTS          | apt/ubuntu/focal    |
| Ubuntu       | 18.04   | LTS          | apt/ubuntu/bionic   |
| Ubuntu       | 16.04   | LTS          | apt/ubuntu/xenial   |
| Ubuntu       | 14.04   | LTS          | apt/ubuntu/trusty   |

## Status

### Debian

-   [![Debian](https://github.com/apt-repositories/generator/actions/workflows/debian.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/debian.yml)
-   [![Debian Backports](https://github.com/apt-repositories/generator/actions/workflows/debian-backports.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/debian-backports.yml)
-   [![Debian Security](https://github.com/apt-repositories/generator/actions/workflows/debian-security.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/debian-security.yml)
-   [![Debian Updates](https://github.com/apt-repositories/generator/actions/workflows/debian-updates.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/debian-updates.yml)

### Ubuntu

-   [![Ubuntu](https://github.com/apt-repositories/generator/actions/workflows/ubuntu.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/ubuntu.yml)
-   [![Ubuntu Backports](https://github.com/apt-repositories/generator/actions/workflows/ubuntu-backports.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/ubuntu-backports.yml)
-   [![Ubuntu Security](https://github.com/apt-repositories/generator/actions/workflows/ubuntu-security.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/ubuntu-security.yml)
-   [![Ubuntu Updates](https://github.com/apt-repositories/generator/actions/workflows/ubuntu-updates.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/ubuntu-updates.yml)


## Further reading

- https://wiki.debian.org/SourcesList
- https://wiki.debian.org/DebianRepository/Format
- https://wiki.ubuntu.com/Releases
- https://help.ubuntu.com/community/Repositories
