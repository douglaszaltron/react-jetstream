Packages with opinionated code formatter configurations which aim to standardize the styling and code quality throughout projects.

## Development

It uses `lerna` and `yarn workspace` to manage and publish the packages.

### Publishing

This script will look for packages that have changed since the last publish and generate a new semver for **all** packages:

`yarn run publish`

It will publish only one specific package:

`yarn run publish --scope="@react-jetstream/eslint-config"`
