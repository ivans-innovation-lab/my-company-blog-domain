# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased][]

[Unreleased]: https://github.com/ivans-innovation-lab/my-company-blog-domain/compare/1.1.1...HEAD

## [1.1.1][] - 2017-12-21

[1.1.1]: https://github.com/ivans-innovation-lab/my-company-blog-domain/compare/1.1.0...1.1.1

### Changed

-   Added validation to the Publish blog post command `PublishBlogPostCommand.java`. Date must be in the future.

## [1.1.0][] - 2017-12-10

[1.1.0]: https://github.com/ivans-innovation-lab/my-company-blog-domain/compare/1.0.0...1.1.0

### Added

-   New command `UnPublishBlogPostCommand.java`

### Changed

-   Version upgraded to [1.1.0]
-   Vesrion of ' my-company-common' dependency upgraded to [1.1.0]
-   Command handler and event source handler for `UnPublishBlogPostCommand.java` added to aggregate root

## [1.0.0][] - 2017-10-15

Initial / First Release

[1.0.0]: https://github.com/ivans-innovation-lab/my-company-blog-domain/tree/1.0.0

### Added

-   Blog post aggregate, commands and handlers are added
