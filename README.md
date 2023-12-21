# versioning

This project was created for simulating versiong with git tags.

## Setup

Execute following commands for setup.

```
git clone https://github.com/JoeHorn/versioning.git
cd versioning
git config include.path ../.gitconfig
```

## Simulating and observation

Execute following commands for switch between versions, then watch the changes in `CHANGES.md` and `version.json`.

- Version 1
```
git pull
git checkout v1
rm -f version.json && git checkout version.json
```

- Version 2
```
git pull
git checkout v2
rm -f version.json && git checkout version.json
```
