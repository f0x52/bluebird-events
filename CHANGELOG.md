# Changelog

## 3.0.1
- Update devDependencies `mocha`, `husky`, `ts-standard`

## 3.0.0

- Set minimum version of Node at `8.0.0`
- Migrate code over to `typescript`
- Update all dependencies
- Use `chai` instead of `should` for test case assertions
- Use `ts-standard` instead of `standard` now that this is a typescript project
- Added commitlint for consistent commits

## 2.1.0

- Updated all repo links due to ownership transfer
- Using js-standard for linting/formatting
- Using Travis-ci for tests
- Using coveralls for code coverage
- Now testing against multiple node versions (0.10.x, 4.x, 6.x)

## 2.0.1

- Removed the max range limiter for nodejs version
- Removed the max range limiter for bluebird version

## 2.0.0

- Updated to use bluebird 3.x and support node 5
- Removed Cancelation feature because Bluebird v3 changed it and I'm not quite sure how
  useful it even is in this project. (Note: if you need it back in, please open an issue with an
  idea of how you would like to see the api working)

## 1.0.0

- Initial release
