mg
==============

A minimal theme for [Pelican](http://blog.getpelican.com/) that uses uikit.
The theme is suited for a single author blog without tag pages nor
blogroll. Feeds are provided via ATOM.


Screenshots
--------------

Browser screenshot

![mg home page screenshot](https://raw.githubusercontent.com/lucachr/pelican-mg/master/home-page-screenshot.png)

Smartphone screenshot

![mg home page smartphone top screenshot](https://github.com/lucachr/pelican-mg/blob/master/home-page-smartphone-top.png)

Features
--------------

* [Open Graph](http://ogp.me) support.
* [Twitter Summary Card](https://dev.twitter.com/cards/types/summary) support.
* [Schema.org](http://schema.org) support.
* Responsive design.
* SCSS style sheets.
* Analytics with Google Analytics, PIWIK and StatCounter.
* Share buttons built with share urls.
* Custom footer notice.

Settings
--------------

The following settings are required for a correct behaviour of this theme.

```python
    TAG_SAVE_AS = ''
    AUTHOR_SAVE_AS = ''
    DIRECT_TEMPLATES = ('index', 'categories', 'archives')
```

###Optional settings

**ALT_NAME**
An alternative name for your site. It appears in the header bar.

**DESCRIPTION**
A brief description of your site, for social networks and search engines.

**FOOTER**
A custom footer notice.

**META_IMAGE**
The absolute URL of a custom image for the `og:image` meta property, Twitter
summary card, and `image` meta property of Schema.org. This image is used in
every page of the blog. Articles and pages can override the default
**META_IMAGE** by setting the "image" metadata in the relative file.

**META_IMAGE_TYPE**
The MIME type for **META_IMAGE**, this is needed for `og:image:type`.

**SC_PROJECT**
The StatCounter project number.

**SC_SECURITY**
The StatCounter security code for the project.

**SHARE**
Enable share buttons, boolean.

**SOCIAL**
A list of tuples (icon, URL). The icons are from [Font Awesome]
(http://fortawesome.github.io/Font-Awesome/). The suffix "-square" is removed
in the footer icons of the small screen layout.
e.g.
```python
    SOCIAL = (('twitter', 'https://twitter.com/twitteruser'),
              ('github', 'https://github.com/githubuser'),
              ('envelope', 'mailto:user@gmail.com'),)
```

License
---------

mg is released under [the MIT License](http://opensource.org/licenses/MIT).
