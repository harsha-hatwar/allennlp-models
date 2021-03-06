# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Changed

- Nothing yet

### Fixed

- Replaced `deepcopy` of `Instance`s with new `Instance.duplicate()` method.
- A bug where pretrained sentence taggers would fail to be initialized because some of the models
  were not imported.

### Added

- Nothing yet

## [v1.0.0rc5](https://github.com/allenai/allennlp-models/releases/tag/v1.0.0rc5) - 2020-05-14

### Changed

- Moved the models into categories based on their format

### Fixed

- Made `transformer_qa` predictor accept JSON input with the keys "question" and "passage" to be consistent with the `reading-comprehension` predictor.

### Added

- `conllu` dependency (previously part of `allennlp`'s dependencies)

## [v1.0.0rc4](https://github.com/allenai/allennlp-models/releases/tag/v1.0.0rc4) - 2020-05-14

We first introduced this `CHANGELOG` after release `v1.0.0rc4`, so please refer to the GitHub release
notes for this and earlier releases.
