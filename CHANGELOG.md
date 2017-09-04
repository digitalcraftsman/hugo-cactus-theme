# Changelog

## Release v1.1.1 - 04th September 2017


- [6f818c5](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/6f818c506139debad3188d3bb027ca6808d9577d) Ordered lists are now styled
- [9fb2a23](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/9fb2a23ab32fb61b62a77e9e8d590ab2cddb8201) adds support for subtitles in pages that can be defined with `.Description` in the front matter
-[a0db308](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/a0db30812aafc89cde5a77d3189f3a028fabe5ba) widens the content column to improve the readability of code examples
- [5108c87](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/5108c8787408d4d31a9161bb47cc506fd2d01fc6) loads FontAwesome from Bootstrap's CDN instead of using the local file.


## Release v1.1 - 26th April 2017

*In the future new additions and changes will be assigned to version numbers rather than dates.* This allows you to track changes in a better fashion. The state of this theme before this release has been assigned to v1.0.

**Some changes and additions listed below require Hugo v0.20 or higher.** Consider to update Hugo to a newer as well if necessary.

### Fixes:

[34f8cf2](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/34f8cf2)q fixes display issues of the about page that occured in Hugo v0.18 and higher due to the way how Hugo treats sites as a page of different kinds. **It's required to rename `content/about/index.md` to `content/about/_index.md`**.

### Improvements

- [931eb53](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/931eb53) improves the generation URLs and linkage of pages
- [9b358a9](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/9b358a9) uses block templates to reduce redundancy
- [dd67ac4](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/dd67ac4) adds support for linking pages in the main menu

### Deprecations

- [fa3c87d](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/fa3c87d) replaces .Now which was deprecated in Hugo v0.19
- [c618828](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/c618828) deprecates the `params.about` config option
- [1b6b863](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/1b6b863) deprecates the option to hide single pages with the `hidden = true` front matter option. Use `draft = true` instead


## 4th January 2016

### Fontawesome as option for social icons in footer

You can now use Fontawesome as alternative to the Mono social icons. Look [here](https://github.com/digitalcraftsman/hugo-cactus-theme/tree/dev#social-link-icons) for more instructions.

[Show me the diff](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/79e5435d6be25ae882ab5ae8455f17834f109a32)

### Hide pages

Pages can now be hidden by adding `hidden = true` to the frontmatter. The pages are still built but they will not appear in the post in on the homepage.

[Show me the diff](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/cf93e42859280b04703cd6ca96062db9a4adb65e)


## 7th December 2015

### Social link icons

Social links with icons can be enabled replacing the copyright field in footer. Configure the style and links in `config.toml`.

## 26th November 2015

Hugo v0.15 is required in order to run the theme with the changes listed below:

### Google Analytics

The setup of Google Analytics changed slighty due to the switch to Hugo's built-in template. In order to update the theme you need to relocate the `google_analytics` variable in the configs and rename it to `googleAnalytics`. Take a look in the example [`config.toml`](https://github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml).

[Show me the diff](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/c2cdd9a02a968738438c48d246ae3949a4e032fc)


### Disqus

Now the theme uses the built-in template of Hugo to enable the comments section with Disqus. This change requires to relocate the `disqusShortname` variable in the configs.

[Show me the diff](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/9ebf05f5b03b3a60fc11cc47775234b7fc2616f0)
