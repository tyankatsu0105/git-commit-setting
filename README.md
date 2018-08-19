This settings are comfortable for you when use `git commit`.

- [commitizen](https://www.npmjs.com/package/commitizen)
- [okonet/lint-staged](https://github.com/okonet/lint-staged)(prettier,eslint,stylelint)
- [generate-changelog](https://www.npmjs.com/package/generate-changelog)

# Usage

## lint-staged, commitzen

After run `git add`

### If you are using yarn

```
yarn commit
```

### If you are using npm

```
npm run commit
```

## generate-changelog

Choose any one from among these when on master branch.

```
"release:major"

"release:minor"

"release:patch"
```

> NOTE:  
> About option `-u`
>
> Supports these service
>
> - github
> - gitlab
> - bitbucket
>
> `$npm_package_config_changelog` is watch field `config: { changelog }`
