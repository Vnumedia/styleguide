# Styleguide
Repo contains shared SASS variables and Bootstrap 4 base vars.

# Usage
Import in package.json inlcuding commit hash, so it will not download automatically the latest version:
```
"styleguide": "https://github.com/Vnumedia/styleguide#94ce9d1a30c84009b9bfe88c4e2bb946e3e0a89d"
```

Import variables:
*Nationalevacaturebank:*
```
"./node_modules/styleguide/nvb/variables"
"./node_modules/styleguide/nvb/bootstrap-variables"
```
*Intermediair:*
```
"./node_modules/styleguide/int/variables"
"./node_modules/styleguide/int/bootstrap-variables"
```
If you don't use Bootstrap 4, do not import bootstrap variables.
