# lareactsecureapp_nt

### Set up ESLint
```
npm info "eslint-config-airbnb@latest" peerDependencies
```


.eslintrc
```
{
  "extends":"airbnb",
  "plugins":[
    "react",
    "jsx-a11y",
    "import"
  ],
  "rules":{
    "react/jsx-filename-extension":[1,{"extensions":[".js",".jsx"]}]
  }
}
```
