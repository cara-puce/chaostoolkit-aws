# Changelog

## [Unreleased][]

[Unreleased]: https://github.com/chaostoolkit-incubator/chaostoolkit-aws/compare/0.4.2...HEAD

## [0.4.2][]

[0.4.2]: https://github.com/chaostoolkit-incubator/chaostoolkit-aws/compare/0.4.1...0.4.2

### Changed

-   Read package version from source file without importing as dependencies may
    not be deployed then

## [0.4.1][]

[0.4.1]: https://github.com/chaostoolkit-incubator/chaostoolkit-aws/compare/0.4.0...0.4.1

### Added

-   MANIFEST.in so that non-source code files are included in source distribution package

## [0.4.0][]

[0.4.0]: https://github.com/chaostoolkit-incubator/chaostoolkit-aws/compare/0.3.0...0.4.0

### Added

-   Add basic IAM Policy support
-   Add ECS actions to delete services, clusters and container instances

### Changed

-   Stoping EC2 instances may not take an AZ as a parameter to pick
    one or many random instances to stop within that AZ.

## [0.3.0][]

[0.3.0]: https://github.com/chaostoolkit-incubator/chaostoolkit-aws/compare/0.2.0...0.3.0

### Added

-   Support specifying a specific profile config to assume a role [#5][5]

[5]: https://github.com/chaostoolkit-incubator/chaostoolkit-aws/issues/5

## [0.2.0][]

[0.2.0]: https://github.com/chaostoolkit-incubator/chaostoolkit-aws/compare/0.1.0...0.2.0

### Added

-   Documentation on contributing to the project
-   Adding a function to sign a request when boto3 lacks support for a specific
    AWS API


## [0.1.0][]

[0.1.0]: https://github.com/chaostoolkit-incubator/chaostoolkit-aws/tree/0.1.0

### Added

-   Initial release
