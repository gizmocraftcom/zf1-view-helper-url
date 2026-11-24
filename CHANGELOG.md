# Changelog

## 2.0.0

Fork of `diablomedia/zendframework1-view-helper-url`, published as `gizmocraft/zendframework1-view-helper-url`.

### Breaking changes

- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-view-helper-url` to `gizmocraft/zendframework1-view-helper-url`. It now requires `gizmocraft/zendframework1-controller` and `gizmocraft/zendframework1-view` (each `^2.0.0`).

### Other changes

- No library code changes were needed and no public signatures changed.
- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 attributes.
- CI runs PHP 8.5 and 8.6.
