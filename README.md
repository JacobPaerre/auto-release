# auto-release

Example code for auto-release with semantic versioning
testtesttest

## How does this work?

With the code created, whenever a push is made to main in the src/-folder, the workflow is run. It will check the latest release and take the version number and either increment the patch, the minor (if commit contains #minor" or the major (if the commit contains #major) version. The title and tag will be the same (the version number with the prefix 'v' before)

