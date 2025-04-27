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
| Ubuntu       | 25.04   | LTS          | apt/ubuntu/plucky   |
| Ubuntu       | 24.10   |              | apt/ubuntu/oracular |
| Ubuntu       | 24.04   | LTS          | apt/ubuntu/noble    |
| Ubuntu       | 22.04   | LTS          | apt/ubuntu/jammy    |
| Ubuntu       | 20.04   | LTS          | apt/ubuntu/focal    |
| Ubuntu       | 18.04   | LTS          | apt/ubuntu/bionic   |
| Ubuntu       | 16.04   | LTS          | apt/ubuntu/xenial   |
| Ubuntu       | 14.04   | LTS          | apt/ubuntu/trusty   |

## Status

[![Debian](https://github.com/apt-repositories/generator/actions/workflows/debian.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/debian.yml) [![Ubuntu](https://github.com/apt-repositories/generator/actions/workflows/ubuntu.yml/badge.svg)](https://github.com/apt-repositories/generator/actions/workflows/ubuntu.yml)

## Further reading

- https://wiki.debian.org/SourcesList
- https://wiki.debian.org/DebianRepository/Format
- https://wiki.ubuntu.com/Releases
- https://help.ubuntu.com/community/Repositories
