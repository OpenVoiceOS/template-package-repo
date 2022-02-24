# replace_package_name

- search and replace the string `replace_package_name` everywhere in this repo
- create dev and master branches
- make dev default branch
- set PYPI_TOKEN in action secrets
- disable wiki/projects/merge commits under repo settings
- edit license_tests.py settings to your liking
- on PR to dev -> alpha version published and github prerelease created
- merge dev -> master when ready for release
- manually trigger one of the workflows for major/minor/build release in the actions tab
- never touch a version file, make a github release or publish to pypi manually again!
