# Styleguide
Repo contains shared SASS variables and Bootstrap 4 base vars.

# Usage
Import in package.json inlcuding commit hash, so it will not download automatically the latest version:
```
"styleguide": "https://github.com/Vnumedia/styleguide#94ce9d1a30c84009b9bfe88c4e2bb946e3e0a89d"
```

### Imports

`nvb` = Nationalevacaturebank
`int` = Intermediair
```
@import "./node_modules/styleguide/mixins";
@import "./node_modules/styleguide/(nvb|int)/variables";
@import "./node_modules/styleguide/(nvb|int)/bootstrap-variables";
@import "./node_modules/styleguide/(nvb|int)/components/type";
```
If you don't use Bootstrap 4, do not import `bootstrap-variables`
If you don't want default headers styling, do not import `type`
