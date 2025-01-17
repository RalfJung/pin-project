# Unreleased

# 0.3.4 - 2019-07-21

* Improved error messages.

# 0.3.3 - 2019-07-15 (yanked)

* Improved error messages.

# 0.3.2 - 2019-03-30

* Avoided suffixes on tuple index.

# 0.3.1 - 2019-03-02

* Improved documentation.

* Updated minimum `syn` version to 0.15.22.

# 0.3.0 - 2019-02-20

* Removed `unsafe_fields` attribute.

* Removed `unsafe_variants` attribute.

# 0.2.2 - 2019-02-20

* Fixed a bug that generates incorrect code for the some structures with trait bounds on type generics.

# 0.2.1 - 2019-02-20

* Fixed a bug that generates incorrect code for the structures with where clause and associated type fields.

# 0.2.0 - 2019-02-11

* Made `unsafe_fields` optional.

* Improved documentation.

# 0.1.8 - 2019-02-02

* Added the feature to create projected enums to `unsafe_project`.

* Added `project` attribute to support pattern matching.

# 0.1.7 - 2019-01-19

* Fixed documentation.

# 0.1.6 - 2019-01-19

* `unsafe_fields` can now opt-out.

* Added `unsafe_variants` attribute. This attribute is available if pin-project is built with the "unsafe_variants" feature.

# 0.1.5 - 2019-01-17

* Added support for tuple struct to `unsafe_project`.

# 0.1.4 - 2019-01-12

* Added options for automatically implementing `Unpin` to both `unsafe_project` and `unsafe_fields`.

# 0.1.3 - 2019-01-11

* Fixed dependencies.

* Added `unsafe_fields` attribute.

# 0.1.2 - 2019-01-09

* Improved documentation.

# 0.1.1 - 2019-01-08

* Renamed from `unsafe_pin_project` to `unsafe_project`.

# 0.1.0 - 2019-01-08

Initial release
