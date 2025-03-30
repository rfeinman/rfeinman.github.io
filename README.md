# Personal website

Site designed using the [minimal-mistakes-jekyll theme](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/).

## Build & deploy website

To build and serve the website, run the following:

    bundle exec jekyll serve

## Notes

The following files are no longer needed (they are bundled with the `minimal-mistakes` theme gem):

```
├── _includes
├── _layouts
├── _sass
├── assets
|  ├── css
|  ├── fonts
|  └── js
```

The following files _are_ needed:

```
├── _data
|  ├── navigation.yml
|  ├── ui-text.yml
```
