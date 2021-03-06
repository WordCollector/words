## 0.1.1

- Added: (Added together with Dart `2.17.0` in linter version `1.22.0`)
  - Core:
    - `use_enums`
    - `use_super_parameters`
  - Flutter:
    - `use_colored_box`

## 0.1.0+1

- Removed: (These were added in linter version `1.22.0`, which isn't yet
  featured in the stable Dart SDK channel)
  - `use_enums`
  - `use_super_parameters`

## 0.1.0

- Added: (Added together with Dart `2.16.0` in linter version `1.18.0`)
  - Core:
    - `avoid_final_parameters`
    - `conditional_uri_does_not_exist`
    - `no_leading_underscores_for_library_prefixes`
    - `no_leading_underscores_for_local_identifiers`
    - `require_trailing_commas`
    - `unnecessary_late`
    - `secure_pubspec_urls`
  - Flutter:
    - `sized_box_shrink_expand`
    - `use_decorated_box`

## 0.0.2+2

- Added:
  - `use_enums`
  - `use_super_parameters`

## 0.0.2+1

- Edited package description.

## 0.0.2

- Added:
  - `eol_at_end_of_file`
  - `library_private_types_in_public_api`
  - `noop_primitive_operations`
  - `prefer_null_aware_method_calls`
  - `use_test_throws_matchers`
  - `depend_on_referenced_packages`
- Removed:
  - `constant_identifier_names` ~ Enumerator values should be in PascalCase, and
    not in camelCase. Thus, the `constant_identifier_names` rule was tedious to
    work with and disable.

## 0.0.1+2

- Enabled stricter type checks through `analyzer` options.

## 0.0.1+1

- Added EXAMPLE.md.

## 0.0.1

- Initial release.
