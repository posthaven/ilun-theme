# The Ilun Posthaven Theme

A simple dark theme for Posthaven.com blogs.

## Screenshot

![Screenshot](/assets/screenshot.png?raw=true)

## Theme Building Resources

* [Posthaven theme documentation](http://theme-docs.posthaven.com/)
* See the [posthaven_theme](https://github.com/posthaven/posthaven_theme) gem for theme file upload via the API.

## Building Assets

### Install Gems

Install [bundler](http://bundler.io) and run:
```
bundle install
```

### Building SCSS

Build `assets/blog.css`:
```
rake compile
```

Watch `src/blog.scss` and build on update:
```
rake watch
```
