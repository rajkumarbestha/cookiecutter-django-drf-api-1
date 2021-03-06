# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Changed
- Better django authentication support
- Updated to Django 2.0
- Documentation updated

## [0.0.2] - 2017-08-19
### Added
- Create git repo and first commit for fresh project
- Django authentication supported (only login and logout now)
- Django REST Framework intergrated
- Support virtualenv for project (bootstraped inside project dir)

### Fixed
- Modification of MIDDLAWARE settings in settings_local.py fixed
- Redirect authenticated users from login page

### Changed
- Use settings_local.py config file first if exists (not need set
  DJANGO_SETTINGS_MODULE)
- Login and logout actions redirected to index page
- Documentation minor update

## [0.0.1] - 2017-08-16
### Added
- Initial cookiecutter project
- Django LiveReload support
- Argon2 algorithm used for password hashing
