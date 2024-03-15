# Dark Rabbit Theme for PayloadCMS

The theme is an initial design to make the PayloadCMS UI more visually pleasing. It's not complete and may not be implemented cleanly in some areas. If anyone is interested, it can be further developed. It supports both light and dark modes, as it largely builds upon the pre-defined theme in Payload.

Tested with Payload 2

## How to use

1. Clone or download the theme, then add it to your Payload source directory, typically under a folder named themes.
2. Adjust your payload.config.ts as follows:

```ts
export default buildConfig({
  ...
  admin: {
    css: path.resolve(__dirname, 'themes/dark-rabbit/index.scss'),
    ...
  }
  ...
});
```

3. Modify the project color variable `--dr-project-color` in the `_theme-vars.scss` file as required.

## Preview

### Light Mode

![3](preview/3.png?raw=true "3")
![1](preview/1.png?raw=true "1")

### Dark Mode

![4](preview/4.png?raw=true "4")
![2](preview/2.png?raw=true "2")
