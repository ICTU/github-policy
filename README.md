# ICTU GitHub policy

How ICTU uses GitHub.

ICTU projects, departments, and employees using GitHub should follow the guidelines below to the best of their ability. The guidelines are applicable to both repositories and forks.

## Mandatory guidelines

### For people

- Users have GitHub 2FA authentication turned on.
- Repository owners ensure that Dependabot and Code scanning alerts are monitored and addressed.
- Repository owners report new users and users leaving to [Frank Niessink](@fniessink).
- Repository owners archive their repositories if they become inactive (meaning no activity for over one year, or no activity for two years if the repository is a fork of another repository).

### For repositories

- Repositories have a repository owner. The repository owner is a human being who works for ICTU.
- Repositories have a `README.md` file describing the project. The `README.md` mentions the repository owner and contact information for the repository owner.
- Repositories have a `LICENSE` file.
- Repositories have a `CODE_OF_CONDUCT.md` file accompanied with a `CONTRIBUTING.md` file in the root of the repository explaining how people are invited to contribute. See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) and [CONTRIBUTING.md](CONTRIBUTING.md) for examples.
- Repositories have a `SECURITY.md` file in the root of the repository explaining the security status and point of contact for the repository. See [SECURITY.md](SECURITY.md) for an example.
- Repositories have [Dependabot alerts](https://docs.github.com/en/code-security/dependabot/dependabot-alerts/about-dependabot-alerts) turned on.
- Repositories have [Code scanning alerts](https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning) turned on.
- Repositories have [Secret scanning alerts](https://docs.github.com/en/code-security/secret-scanning) turned on.
- Repositories have [Private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability) turned on.

## Optional guidelines

### For repositories

- Repositories have a `publiccode.yml` file in the root of the repository, a [metadata description standard](https://github.com/publiccodeyml/publiccode.yml) for public software in order to make the software easily discoverable. See [publiccode.yml](publiccode.yml) for an example.
- Repositories have a `CHANGELOG.md` file describing relevant changes to the repository contents. The changelog format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/). See [CHANGELOG.md](CHANGELOG.md) for an example.
- Repositories use [Semantic Versioning](https://semver.org/spec/v2.0.0.html) to version the repository contents.

## Get in touch

Point of contact for this repository is [Frank Niessink](@fniessink).
