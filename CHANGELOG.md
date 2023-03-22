# Semantic Release Automated Changelog

## [4.2.2](https://github.com/AlaskaAirlines/auro-avatar/compare/v4.2.1...v4.2.2) (2023-03-22)


### Performance Improvements

* **ie:** remove additional legacy resources ([14402d7](https://github.com/AlaskaAirlines/auro-avatar/commit/14402d7f62bb4520b339fb76be4ab5f9b32db61f))

## [4.2.1](https://github.com/AlaskaAirlines/auro-avatar/compare/v4.2.0...v4.2.1) (2022-12-01)


### Bug Fixes

* **fallback:** check for 403 http status code for fallback image [#28](https://github.com/AlaskaAirlines/auro-avatar/issues/28) ([81e724e](https://github.com/AlaskaAirlines/auro-avatar/commit/81e724eaa2a59f56f18d571e9425ba2ce85f8456))
* **properties:** enable reflect on 'type' attribute [#26](https://github.com/AlaskaAirlines/auro-avatar/issues/26) ([03435d2](https://github.com/AlaskaAirlines/auro-avatar/commit/03435d2684385d331f62e24694a5fccfc02f5946))

# [4.2.0](https://github.com/AlaskaAirlines/auro-avatar/compare/v4.1.0...v4.2.0) (2022-01-21)


### Features

* **fallback:** new fallback image for invalid airport codes ([b18f99c](https://github.com/AlaskaAirlines/auro-avatar/commit/b18f99caa927a7dc878b751b3d7254c22990fcd2))
* **httpstatus:** support exposing http status of airport code image URL ([f24e285](https://github.com/AlaskaAirlines/auro-avatar/commit/f24e2859852bf05191fdda6678d26d7fc272cba6))


### Reverts

* Revert "feat(httpstatus): support exposing http status of airport code image URL" ([44da0a1](https://github.com/AlaskaAirlines/auro-avatar/commit/44da0a194b022112aeeabd1056fdef409e2409e9))

# [4.1.0](https://github.com/AlaskaAirlines/auro-avatar/compare/v4.0.0...v4.1.0) (2021-12-28)


### Features

* **reflected attrs:** tail is a reflected attribute [#19](https://github.com/AlaskaAirlines/auro-avatar/issues/19) ([f26add3](https://github.com/AlaskaAirlines/auro-avatar/commit/f26add3f83e89cbfda1f4779d35645cab806431c))

# [4.0.0](https://github.com/AlaskaAirlines/auro-avatar/compare/v3.0.0...v4.0.0) (2021-09-17)


### chore

* **deps:** update majro, minor and patch updates ([b1c13fa](https://github.com/AlaskaAirlines/auro-avatar/commit/b1c13fa81d07305068050c76e1e5fd1246aae86f))


### BREAKING CHANGES

* **deps:** Official new relesae was never delivered,
triggering new build

# [3.0.0](https://github.com/AlaskaAirlines/auro-avatar/compare/v2.1.0...v3.0.0) (2021-07-13)


### Code Refactoring

* **migrate:** address post-migration issues ([831ea0e](https://github.com/AlaskaAirlines/auro-avatar/commit/831ea0e9166f664b074b9c38bbaa6b0483ee66f0))


### Features

* **lg:** update to have more robust API [#6](https://github.com/AlaskaAirlines/auro-avatar/issues/6) ([c1e18f8](https://github.com/AlaskaAirlines/auro-avatar/commit/c1e18f8187fd0f15301bf497661d57096f74dfae))


### BREAKING CHANGES

* **migrate:** This and the previous commits
are considered breaking changes due to the
reassignment of the new @aurodesignsystem
npm namespace.

# [2.1.0](https://github.com/AlaskaAirlines/auro-avatar/compare/v2.0.0...v2.1.0) (2021-02-11)


### Features

* add support for avatar tail feature ([9a28150](https://github.com/AlaskaAirlines/auro-avatar/commit/9a2815089d7b7fc5dfccf16e5c1eb876dd143f2b))

# [2.0.0](https://github.com/AlaskaAirlines/auro-avatar/compare/v1.0.2...v2.0.0) (2020-12-23)


### Features

* add support for rollup bundles ([948c0fe](https://github.com/AlaskaAirlines/auro-avatar/commit/948c0fefb65f54790faf2a1911f431146067eed2))
* updates resource path ([5ce8fdb](https://github.com/AlaskaAirlines/auro-avatar/commit/5ce8fdbe75c937c55a23f65533e9804790db6c79))


### BREAKING CHANGES

* This is an update to the underlying URL
path of image resources. Updating to this version will
change the images being used witin the element
* This is a change in the use of bundled resources,
removed depenbdency on polyfill file and created ES5 and ES6 resources

## [1.0.2](https://github.com/AlaskaAirlines/auro-avatar/compare/v1.0.1...v1.0.2) (2020-10-31)


### Bug Fixes

* update auro-icon dependency ([7c76877](https://github.com/AlaskaAirlines/auro-avatar/commit/7c768771a55f698a18322d77cf9f227c744fde8c))

## [1.0.1](https://github.com/AlaskaAirlines/auro-avatar/compare/v1.0.0...v1.0.1) (2020-10-30)


### Bug Fixes

* update packages; move to GHA ([dfc1083](https://github.com/AlaskaAirlines/auro-avatar/commit/dfc108369ec5a35d469f70336ea3e67dd74f9550))

# 1.0.0 (2020-09-29)


### Features

* build new auro-avatar component ([177c3bd](https://github.com/AlaskaAirlines/auro-avatar/commit/177c3bdc1942ff3f949bf378ce616be141d89b73))