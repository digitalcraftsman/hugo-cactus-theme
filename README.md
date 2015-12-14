# Cactus Theme

Cactus is a minimalistic theme for bloggers based on the default theme of the same-named [Cactus static site generator](//github.com/koenbok/Cactus) written in Python and [Nick Balestra](//github.com/nickbalestra/kactus)'s Jekyll port. Noteworthy features of this Hugo theme are the integration of a comment-system powered by Disqus, a customizable about page, support for RSS feeds, syntax highlighting for source code and sharing options for blog posts.


![Screenshot](https://github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/images/screenshot.png)

## Contents

- [Installation](#installation)
- [The config file](#the-config-file)
- [About page](#about-page)
- [Disqus](#disqus)
- [Nearly finished](#nearly-finished)
- [Contributing](#contributing)
- [License](#license)
- [Annotations](#annotations)


## Installation

Inside the folder of your Hugo site run:

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/digitalcraftsman/hugo-cactus-theme.git

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

### The config file

Take a look inside the [`exampleSite`](//github.com/digitalcraftsman/hugo-cactus-theme/tree/dev/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml).

To use it, copy the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml) in the root folder of your Hugo site. Feel free to change strings as you like to customize your website.

## About page

Use the about page to introduce yourself to your visitors. You can customize the content as you like in the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml). Furthermore, you should replace the [avatar placeholder](//github.com/digitalcraftsman/hugo-cactus-theme/blob/master/static/images/avatar.png) with a great image of yourself.

## Disqus

This theme features a comment system powered by Disqus too. Just add your Disqus-shortname to the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml) and let readers respond to your blog posts.

## Social link icons

You can add a social link panel in the footer by adding entries to the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml). The icons uses fonts from the [mono social icons](https://github.com/drinchev/monosocialiconsfont) project. There are 3 styles of icon - circle, rounded, or default(empty).

## Nearly finished

In order to see your site in action, run Hugo's built-in local server. 

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](//github.com/digitalcraftsman/hugo-cactus-theme/issues) to let me know. Or make directly a [pull request](//github.com/digitalcraftsman/hugo-cactus-theme/pulls).


## License

This theme is released under the MIT license. For more information read the [License](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/LICENSE.md).


## Annotations

Thanks to [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project.

