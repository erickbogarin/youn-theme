# Youn - Jekyll Theme

![Youn Screenshot](/screenshot.png)

A simple and minimalist template for [Jekyll](https://jekyllrb.com/) designed for developers who wants start blogging

## Demo
[Author Personal Blog](http://blog.erickbogarin.com.br)

## Features
- Resposive Design (Mobile-First)
- Stylus (Jeet, Rupture, Kouto Swiss)
- ITCSS + RSCSS
- Gulp
- Live Search
- Offcanvas Menu
- SVG icons
- Tags page
- Color Customization
- Info Customization

## How to use this theme
### Environment Requirements
- Npm
- Gulp
- Jekyll

### Usage
1. You must have Jekyll already installed - [Install Jekyll](https://jekyllrb.com/docs/installation/)
2. Then within your **project folder** copy the following commands:

  ```bash
  $ git clone https://github.com/erickbogarin/youn-theme.git
  $ npm install
  $ npm run build
  ```
3. Edit the `_config.yml` file including the following code snippets:

  ```
    # include these files for jekyll works properly
    exclude:
      - Gemfile
      - Gemfile.lock
      - package.json
      - src
      - node_modules
  ```
4. Run the project `jekyll serve`

### Writing posts

When creating a new post include at least the following info like the example below:

```
introduction: "Lorem ipsum dolor sit amet"
description: "Cras convallis, mauris in mattis pharetra."
image: "/assets/img/icons/html.svg"
tags:
- web
- programming
```

There you describe important informations for your readers, for example the icon related to the post and the tags.

## Customizing

### Changing the author name

Open the `src/styl/settings/_settings.variables.styl` file and change the code snippet below:

```
//== Site Title
$site-title = 'Awesome Dev'
$site-title-small = '</> AD'
```

### Adding a new icon
- `assets/img/icons`
- Inline svg: `_includes/svg-icons.html`

## Questions

Feel free to open any issue.

## License

This theme is free and open source, distributed under the The MIT License. So feel free to use this Jekyll theme on your site without linking back to me or using a disclaimer.
