# Changelog

All notable changes to this project are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1]

### Added

- Startup message with a note on AI non-determinism, a prompting tip, and a link to raise issues or open pull requests.

### Improved

- **Custom scan checks** — generated checks now produce complete audit issues (valid base URL, severity/confidence, background/remediation), add request/response markers evidencing findings, begin with a config comment naming the assumed check type, and are tailored to the scan check type you select.
- **Reliability** — generated code now guards null header values and absent responses, reducing runtime errors.
- **API accuracy** — sharper guidance on body typing, `utilities()` helpers, and header accessors, so generated code compiles and behaves as intended more often.

## [1.0.0]

- Initial release.