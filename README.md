# Meteor Feature Requests

This repository is used to track [Meteor](https://github.com/meteor/meteor) feature requests only (requests for new Meteor functionality). Click [here](https://github.com/meteor/meteor-feature-requests/issues/new) to open a new feature request.

**Note:** Meteor bugs are tracked in the [Meteor repo issue tracker](https://github.com/meteor/meteor/issues).

## Guidelines

Meteor is a big project with many sub-projects. There aren't as many core developers (we're hiring!) as there are sub-projects, so we're not able to work on every single sub-project every month. We use our roadmap to communicate the high-level features we're currently prioritizing.

Every additional feature adds a maintenance cost in addition to its value. This cost starts with the work of writing the feature or reviewing a community pull request. In addition to the core code change, attention needs to be paid to documentation, tests, maintainability, how the feature interacts with existing and speculative Meteor features, cross-browser/platform support, user experience/API considerations, etc. Once the feature is shipped, it then becomes the community's responsibility to fix future bugs related to the feature. In case the original author disappears, it's important that the feature has good tests and is widely used in order to be maintainable by other contributors.

For these reasons, we strongly encourage features to be implemented as Atmosphere or npm packages rather than changes to core. Try to re-work your feature request as a minimal set of hooks to core that enable the feature to be implemented as a package.

Feature requests should be well specified and unambiguous to have the greatest chance of being worked on by a contributor.

Finally, you can show your support for (or against!) features by using GitHub reactions or by adding meaningful details which help the feature definition become more clear. Please do not comment with "+1" since it creates a lot of noise (e-mails, notifications, etc.).

## Resources

- Main Meteor repo: https://github.com/meteor/meteor
- Contribution guidelines: https://github.com/meteor/meteor/blob/devel/CONTRIBUTING.md
- Feature request triaging guidelines: https://github.com/meteor/meteor/blob/devel/ISSUE_TRIAGE.md#feature-requests
- Feature request (PR) development guide: https://github.com/meteor/meteor/blob/devel/DEVELOPMENT.md
