---
name: "Mutual Aid: Service Release"
about: "Release a new service or service version into the catalog"
title: "Service Release: [TODO: ServiceName] [TODO: Version]"
labels: service-release
---
<!-- This is intended for use by service mantainers only. Please use another issue type if this one doesn't apply. -->

# Service Release: `[TODO: ServiceName]` `[TODO: Version]`

<!-- NOTE: Before submitting, you should have already created a release in the service's repository based on its own process. -->

* Release Link: (TODO: Release link here)

## Notes

<!-- TODO: Any notes for us? Let us know here. -->
____

<!-- --------------------------------- -->
<!-- PLEASE DON'T EDIT BELOW THIS LINE prior to creating the issue -->
<!-- --------------------------------- -->

## Prerequisite Tasks

- [ ] A release exists in my service's repo and I've added it in the above markdown

## Tasks

<!-- Paste any associated PRs at the end of these task items -->

### If Releasing for the first time

- [ ] Add a `service:[servicename]` label in this repository.

### Tasks for Every Release
- [ ] Add/Update this repo's `ServiceCatalog.md` as applicable
- [ ] Add/Update your service templates in the `.github/ISSUE_TEMPLATE/config.yml` file here.
- [ ] Add/Update your service's templates in the `.github/ISSUE_TEMPLATE/` directory here.
- [ ] Find incomplete applications of the service in [the issues](https://github.com/AWiderDotNET/mutual-aid/issues), and note in them that a new release has occurred.
