2014-08-07 Release 0.3.0

Features:
- Make both `on_pe_supported_platforms` and `on_pe_unsupported_platforms` take
  'all' as the default for targets as this is easier for CI to set than nil.

2014-08-07 Release 0.2.1

Bugfixes:
- Rename opensuse- to sles- in PE3.3.

2014-08-07 Release 0.2.0

Features:
- Add `on_pe_supported_platforms` to take an argument of target platforms
- Add `on_pe_unsupported_platforms` to perform the inverse
- Add ability to only check PE versions that match metadata requirements
