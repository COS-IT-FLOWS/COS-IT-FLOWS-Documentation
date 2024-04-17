# Release RoadMap

> **IMPORTANT**:
> This project is currently in a very early development stage. This roadmap is a roadmap template for future releases.

Regardless of the release type (major, minor, patch), the CoS-IT-FloWS system release process follows this roadmap.

1. Identification of features and fixes to be included in the release. This is coordinated through the github page.
2. Features and fixes are added to the appropriate branch (develop or hotfix) via Github pull requests.
3. The model is tested using the CoS-IT-FloWS test framework. Each of the following tests should be run and verified for any release.

    + Unit tests
    + System tests
    + Example tests
    + Science tests
    + Release tests

4. Once all tests have been run and the release is ready, a few minor changes need to be made to the source code prior to a release:

    + Update the version string for classic and image drivers (`version.h`)
    + Update the version string for the python driver (`setup.py`)
    + Update the documentation. At a minimum this means updating ReleaseNotes.md.

5. Make the release!
    + Merge the `release` branch into the `master` branch.
    + Create the tag. This is best done on the command line as `git tag -f -a COS-IT-FLOWS.0.1 -m 'release tag of COS-IT-FLOWS.0.1, bug fix update for this example`.
    + Publish the release on Github.
    + Update the CoS-IT-FloWS documentation and Readme files.
    + Update the `develop` branch with the changes from the `master` branch.
    + Reset the version strings in the `develop` branch.
