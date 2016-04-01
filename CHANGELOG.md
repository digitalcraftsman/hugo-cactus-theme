# Changelog

### 2016/04/01

#### Fontawesome as option for social icons in footer

You can now use Fontawesome as alternative to the Mono social icons. Look [here](https://github.com/digitalcraftsman/hugo-cactus-theme/tree/dev#social-link-icons) for more instructions.

[Show me the diff](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/79e5435d6be25ae882ab5ae8455f17834f109a32)

#### Hide pages

Pages can now be hidden by adding `hidden = true` to the frontmatter. The pages are still built but they will not appear in the post in on the homepage.

[Show me the diff](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/cf93e42859280b04703cd6ca96062db9a4adb65e)


### 2015/07/12

#### Social link icons

Social links with icons can be enabled replacing the copyright field in footer. Configure the style and links in `config.toml`.

### 2015/26/11

Hugo v0.15 is required in order to run the theme with the changes listed below:

#### Google Analytics

The setup of Google Analytics changed slighty due to the switch to Hugo's built-in template. In order to update the theme you need to relocate the `google_analytics` variable in the configs and rename it to `googleAnalytics`. Take a look in the example [`config.toml`](https://github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml).

[Show me the diff](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/c2cdd9a02a968738438c48d246ae3949a4e032fc)


#### Disqus

Now the theme uses the built-in template of Hugo to enable the comments section with Disqus. This change requires to relocate the `disqusShortname` variable in the configs. 

[Show me the diff](https://github.com/digitalcraftsman/hugo-cactus-theme/commit/9ebf05f5b03b3a60fc11cc47775234b7fc2616f0)
