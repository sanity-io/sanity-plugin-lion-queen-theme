# Lion Queen Studio Theme

A Lion Queen theme that overrides the default look of the [Sanity](https://sanity.io) Studio. Created as part of the [How to Brand your Studio](https://www.sanity.io/guides/how-to-brand-your-studio) tutorial.

![Screenshot of the Lion Queen theme](https://github.com/sanity-io/sanity-plugin-lion-queen-theme/raw/master/.github/lion-queen-theme.png)

## Installation

At the root of your Sanity project, run this command in the terminal.

```
sanity install lion-queen-theme
```

## Example Studio

To see this theme in action, take a look at the example Studio created with `sanity init` and the e-commerce template:

```bash
$ cd example
$ npm install # or yarn install
$ sanity start
```

## CSS Variables

This theme only uses a handful of the available variables that lets you give the Studio a custom look. Find the CSS variables this theme overrides in [variables.css](./src/variables.css). 

```css
/* Brand colors */
--brand-primary
--brand-primary--inverted
--brand-secondary
--brand-secondary--inverted

/* Typography */
--font-family-sans-serif
--font-size-base
--text-color

/* Main Navigation */
--main-navigation-color
--main-navigation-color--inverted
```

See the documentation for more information about [styling the Studio](https://www.sanity.io/docs/styling), or explore the [full list of variables](https://github.com/sanity-io/sanity/tree/master/packages/%40sanity/base/src/styles/variables) on GitHub.
