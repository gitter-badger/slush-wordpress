# slush wordpress

[![Join the chat at https://gitter.im/amitmtrn/slush-wordpress](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/amitmtrn/slush-wordpress?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[![NPM version](https://img.shields.io/npm/v/slush-wordpress-theme.svg)](https://www.npmjs.com/package/slush-wordpress-theme)
[![Download stats](https://img.shields.io/npm/dm/slush-wordpress-theme.svg)](https://www.npmjs.com/package/slush-wordpress-theme)

[![NPM stats](https://nodei.co/npm/slush-wordpress-theme.svg?downloadRank=true&downloads=true)](https://www.npmjs.org/package/slush-wordpress-theme)

## installation

```
npm install -g slush
```

```
npm install -g slush-wordpress-theme
```

## Wordpress theme scaffolding

### create the theme
```
slush wordpress-theme
```

### create custom page template

```
slush wordpress-theme:custom-page custom-page-name
```

### create custom post type

```
slush wordpress-theme:post-type
// add the code to the functions.php make sure you don't close the php tag.
```

### enqueue script

```
slush wordpress-theme:enqueue-script some-script
// add the code to the functions.php make sure you don't close the php tag.
```
