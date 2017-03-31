# General purpose Webpack boilerplate

This Webpack can be used with Wordpress, Hugo or whatever comes into you mind. The following features are included:

- Asset cache busting
- [SASS](http://sass-lang.com/) support
- [Autoprefixing](https://github.com/postcss/autoprefixer)
- Es2016 transpiling with [Babel](https://babeljs.io/)
- Linting with [ESLint](http://eslint.org/)
- [Prettier](https://github.com/prettier/prettier) for consistent formatting
- Automatic browser reloading in dev mode

## Usage

```Bash
# clone project
git clone https://github.com/lgraubner/webpack-boilerplate-general.git
cd webpack-boilerplate-general

# initialize new git workspace
rm -rf .git
git init

# install dependencies
yarn install

# start dev server
yarn run dev
```

To build a production bundle execute `yarn run build`. This will create the files and an `assets.json`. Read the filenames from here as those may change for cache busting.
