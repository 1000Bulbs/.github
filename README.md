# 1000Bulbs GitHub Actions

A collection of github actions workflows to be used in 1000Bulbs repos.

## Workflows

- [chef-lint-unit](.github/workflows/chef-lint-unit.yml)

## Releases

- Update [CHANGELOG](CHANGELOG.md)

```
changelog-maker --markdown --start-ref=[starting commit] 1000Bulbs .github
```

- Commit git release

```
git add -A && git commit -m "Release v1.0.0"
```

- Push git release

```
git push origin master
```

- Tag git release

```
git tag -a v1.0.0 -m "Release v1.0.0" && git push --tags
```

- Click on [Releases](https://github.com/1000Bulbs/.github/releases)

- Click on [Draft a new release](https://github.com/sous-chefs/.github/releases/new) button

- Fill out form and click on `Publish release`
