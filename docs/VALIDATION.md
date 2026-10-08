# Validation and release notes

The existing README reports version `0.9.0-beta.2` and lists unit, widget, repository, migration and integration tests. This public repository has documentation and brand assets; it contains no Flutter source, APK, test runner, release artifact or reproducible test results. The latest private release was not independently verified on 8 October 2026.

## Product test approach

In the private repository, validate the full customer → job → payment/expense → invoice → report journey. Exercise partial settlements, invalid inputs, database upgrades, offline behavior, PDF output and backup/restore integrity. Record the device, version, command or manual steps and actual outcome for each release.

These are validation guidance, not newly executed tests. Public CI should not install Flutter or imply that the commercial app was tested without its source.

## Evidence reviewed

The existing Jobs capture was visually inspected and the Netlify showcase loaded on 8 October 2026. Existing Dashboard and Money captures were also reviewed; their totals differ between captures and should not be interpreted as a single financial test case. No screenshots were generated or altered for this cleanup.

## Commercial boundary

Retain production source, signing keys, backups, databases and customer exports privately. Public changes should document product behavior and approved captures only. The logo and wordmark files currently have identical SHA-256 hashes; they are retained because external consumers of either filename are not known.
