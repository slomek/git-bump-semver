# git-bump-semver

A tiny script that helps generating new tag semver-based tags based on the latest one defined in the repository.

## Usage

```
./git-bump-semver
Bump version v0.1.100 -> v0.1.101? [Y/n] # Y
Tag created

./git-bump-semver
Bump version v0.1.100 -> v0.1.101? [Y/n] # n
Aborted
```

### git alias

It's recommended to add `git-bump-semver` to git aliases:

```
git config --global alias.bump !git-bump-semver
```

In order for this to work, you need to make sure `git-bump-server` is in your `$PATH`:

```
$ git bump
Bump version v0.1.100 -> v0.1.101? [Y/n] # Y
Tag created
```
