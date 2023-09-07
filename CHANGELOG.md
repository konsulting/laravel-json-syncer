# Changelog


<a name="1.5.0"></a>
## 1.5.0 (2023-09-07)

### Changed

- ⬆️ Upgrade dependencies. [[1a5aecf](https://github.com/mathieutu/laravel-json-syncer/commit/1a5aecf37f220c57f7e3a02747aeeb949f941198)]
- ⬆️ Upgrade to GitHub-native Dependabot ([#17](https://github.com/mathieutu/laravel-json-syncer/issues/17)) [[1509e51](https://github.com/mathieutu/laravel-json-syncer/commit/1509e51405f9ead60fa681d62a36d9e9176a6db8)]

### Miscellaneous

- 📝 Improve README. [[cc3cdd4](https://github.com/mathieutu/laravel-json-syncer/commit/cc3cdd4aa35687243f3f8ba6f117f12827ab9e70)]
- 📝 Add installation example. ([#16](https://github.com/mathieutu/laravel-json-syncer/issues/16)) [[09d8713](https://github.com/mathieutu/laravel-json-syncer/commit/09d871366c1d0891fda2c017d69f43ae61ad42f7)]


<a name="1.4.0"></a>
## 1.4.0 (2021-03-14)

### Changed

- ⬆️ Update dependencies (min PHP 7.4, Laravel 8) [[da3b967](https://github.com/mathieutu/laravel-json-syncer/commit/da3b9673b5438f4d680c280dbb778d835f145b44)]
- 👷 Replace Travis with Github actions. [[063df3a](https://github.com/mathieutu/laravel-json-syncer/commit/063df3ab2989a13725ef34c3af4a268a81b58341)]


<a name="1.3.0"></a>
## 1.3.0 (2020-03-09)

### Added

- 👷‍♂️ Update Travis config with new api. [[9108f55](https://github.com/mathieutu/laravel-json-syncer/commit/9108f5532c7ee4e14bfc2111e451e0bc1ab3bba4)]
- 📦 Implement Laravel 7 compatibility. ([#12](https://github.com/mathieutu/laravel-json-syncer/issues/12)) [[f0cc43a](https://github.com/mathieutu/laravel-json-syncer/commit/f0cc43a9a7814482b9273fa4117b1c5508b78006)]

### Fixed

- 💚 Remove forgotten import. [[46292a7](https://github.com/mathieutu/laravel-json-syncer/commit/46292a7521f6848cf1949b7403377fccb7138819)]


<a name="1.2.1"></a>
## 1.2.1 (2020-02-28)

### Fixed

- 🐛 Use native Json exception if parsing problem. [[698ec4f](https://github.com/mathieutu/laravel-json-syncer/commit/698ec4f6e3db505448d1eb5ef18d91102baec582)]


<a name="1.2.0"></a>
## 1.2.0 (2020-02-28)

### Added

- 📦 Implement Laravel 6 compatibility ([#11](https://github.com/mathieutu/laravel-json-syncer/issues/11)) [[f7eb983](https://github.com/mathieutu/laravel-json-syncer/commit/f7eb9835a735f60dc191353cbd4b282a20eea481)]

### Fixed

- 💚 🎨 Replace StyleCI by PHPCs and fix code style. [[625e7fb](https://github.com/mathieutu/laravel-json-syncer/commit/625e7fbbd9c36752eab94048740bd50a5f0dc449)]

### Miscellaneous

- ✅ Increase code coverage and quality. [[d214cda](https://github.com/mathieutu/laravel-json-syncer/commit/d214cdacd2428e888c21151ed8901cb44b25b237)]
- 📝 Change email. [[2b47b0a](https://github.com/mathieutu/laravel-json-syncer/commit/2b47b0aeb8536d3ef14ff7f1ddb16a4cce8b252c)]
- 👷 Update tests version. [[28554fe](https://github.com/mathieutu/laravel-json-syncer/commit/28554fec34262e2ec957f8c81950fb25d789f2bc)]


<a name="1.1.0"></a>
## 1.1.0 (2019-02-14)

### Added

- ✨ Add the possibility to pass null to one to many relationships. [[7452c15](https://github.com/mathieutu/laravel-json-syncer/commit/7452c15bbec7faa9fd4d1ad1ddc951fe01b77412)]
- ✨ Add isExporting and isImporting methods. [[79e5ad3](https://github.com/mathieutu/laravel-json-syncer/commit/79e5ad36c60153ad84176f31c74e7628f53d272d)]

### Changed

- 🎨 Refactor importFromJson helper method to static. [[2891596](https://github.com/mathieutu/laravel-json-syncer/commit/28915961e9fc93f175522a01c60b6553be6491a5)]

### Fixed

- 💚 Fix Php7 & StyleCI. [[e9322c7](https://github.com/mathieutu/laravel-json-syncer/commit/e9322c7913022fd8c40a88fe57f81cb62e5fec17)]

### Miscellaneous

- 📝 Add Changelog. [[765dd1b](https://github.com/mathieutu/laravel-json-syncer/commit/765dd1ba198458fe55db10d7032def068f58247d)]


<a name="1.0.0"></a>
## 1.0.0 (2017-08-07)

### Added

- ✨ Convert objects to array in Importer if they are in collection. [[b907f71](https://github.com/mathieutu/laravel-json-syncer/commit/b907f7173960e42583d0b45f5376c99b193fecfb)]
- ✨ Add exportToCollection() to the JsonExportable. [[8328a2e](https://github.com/mathieutu/laravel-json-syncer/commit/8328a2e66fcb20920e05c40e707bc42358084d52)]
- ✨ Add the Json Importer. [[73fff7d](https://github.com/mathieutu/laravel-json-syncer/commit/73fff7d19cf76a45adc4973cc5b90671398c01d3)]
- ✨ Add a service which find automatically all the Has*Relations in Model. [[d5eb19f](https://github.com/mathieutu/laravel-json-syncer/commit/d5eb19f218a213fd30c75c5a59530fdd9aa023e6)]
- ✨ Add JsonExporter. [[2c5266d](https://github.com/mathieutu/laravel-json-syncer/commit/2c5266d9fc146e6320febff0473eab33ee0b0c84)]
- 🎉 First commit. [[e27255d](https://github.com/mathieutu/laravel-json-syncer/commit/e27255d6165df2fe5b71e77f96c6fd0f7aee5590)]

### Changed

- 💚 🎨 StyleCI,  PHP 7.0, and forgotten renaming. [[8dcdf6a](https://github.com/mathieutu/laravel-json-syncer/commit/8dcdf6afc6629a065f16502a37f56d14b3ea6059)]
- ✅ 🐛 Add tests and fix bugs. [[872e536](https://github.com/mathieutu/laravel-json-syncer/commit/872e536b245d53ac3a5e644101148ee3c2b3403e)]
- 🎨 Rename package and organise imports. [[0e6ceed](https://github.com/mathieutu/laravel-json-syncer/commit/0e6ceed2a303ffb42b298c0b5a42844a8678ce6e)]
- ✅ 🐛🎨 Add tests, fix bugs, and refactor Traits. [[5976d94](https://github.com/mathieutu/laravel-json-syncer/commit/5976d94fe03baf7d3b3f1b93e33d98351a5fa00f)]
- ✅ 🐛 Add tests and fix bugs for RelationsInModelFinder [[7540199](https://github.com/mathieutu/laravel-json-syncer/commit/7540199967e27ca73e862944c7e921809d93238a)]

### Miscellaneous

- 📝 Update Readme. [[136a7a8](https://github.com/mathieutu/laravel-json-syncer/commit/136a7a82ded1eb230ca1138d6094a163549a70fc)]


