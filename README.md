# Flow project template

Simple template to save some time

## Dev tools

* Flow
* Babel
  * presets:
    * env (target: node 8.10)
    * flow
  * plugin:
    * rest spread
  * nodemon

## Scripts

### start

```
node src/index.js
```

### startDev

```
nodemon src/index.js
```

### prebuild

```
rm -rf dst
```

### build

```
babel -d dst src/
```
