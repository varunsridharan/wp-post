# WP Post
Simple WP Post Class With Advanced Options.

[![Latest Stable Version](https://poser.pugx.org/varunsridharan/wp-post/version)](https://packagist.org/packages/varunsridharan/wp-post)
[![Total Downloads](https://poser.pugx.org/varunsridharan/wp-post/downloads)](https://packagist.org/packages/varunsridharan/wp-post)
[![Latest Unstable Version](https://poser.pugx.org/varunsridharan/wp-post/v/unstable)](//packagist.org/packages/varunsridharan/wp-post)
[![License](https://poser.pugx.org/varunsridharan/wp-post/license)](https://packagist.org/packages/varunsridharan/wp-post)
[![composer.lock available](https://poser.pugx.org/varunsridharan/wp-post/composerlock)](https://packagist.org/packages/varunsridharan/wp-post)
 

## Installation
The preferred way to install this extension is through [Composer](http://getcomposer.org/download/).

To install **WP_Post library**, simply:

    $ composer require varunsridharan/wp-post

The previous command will only install the necessary files, if you prefer to **download the entire source code** you can use:

    $ composer require varunsridharan/wp-post --prefer-source

You can also **clone the complete repository** with Git:

    $ git clone https://github.com/varunsridharan/wp-post.git

Or **install it manually**:

[Download WP_Post.php](https://raw.githubusercontent.com/varunsridharan/wp-post/master/class-post.php):

    $ wget https://raw.githubusercontent.com/varunsridharan/wp-post/master/class-post.php

## Usage
```php
$post_data = new \Varunsridharan\WordPress\Post(22);
```

### Get Post Title
```php
echo $post_data->title();
```

### Get Featured Image URL
```php
if($post_data->has_featured_image()){
    echo '<img src="'.$post_data->featured_image_url('large').'"/>';
}
```

## Available Class Methods

* `has_featured_image`
* `featured_image_id`
* `featured_image_url`
* `permalink`
* `author`
* `has_content`
* `has_excerpt`
* `title`
* `slug`
* `parent`
* `type`
* `page_template`
* `excerpt`
* `content`
* `status`
* `is_status`
* `get_meta`
* `update_meta`
* `add_meta`
* `delete_meta`
* `taxonomies`
* `get_terms`
* `set_terms`
* `post`
* `id`


---

<!-- START common-footer.mustache  -->
## 📝 Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

[Checkout CHANGELOG.md](https://github.com/varunsridharan/wp-post/blob/main/CHANGELOG.md)


## 🤝 Contributing
If you would like to help, please take a look at the list of [issues](https://github.com/varunsridharan/wp-post/issues/).


## 📜  License & Conduct
- [**GNU General Public License v3.0**](https://github.com/varunsridharan/wp-post/blob/main/LICENSE) © [Varun Sridharan](website)
- [Code of Conduct](https://github.com/varunsridharan/.github/blob/main/CODE_OF_CONDUCT.md)


## 📣 Feedback
- ⭐ This repository if this project helped you! :wink:
- Create An [🔧 Issue](https://github.com/varunsridharan/wp-post/issues/) if you need help / found a bug


## 💰 Sponsor
[I][twitter] fell in love with open-source in 2013 and there has been no looking back since! You can read more about me [here][website].
If you, or your company, use any of my projects or like what I’m doing, kindly consider backing me. I'm in this for the long run.

- ☕ How about we get to know each other over coffee? Buy me a cup for just [**$9.99**][buymeacoffee]
- ☕️☕️ How about buying me just 2 cups of coffee each month? You can do that for as little as [**$9.99**][buymeacoffee]
- 🔰         We love bettering open-source projects. Support 1-hour of open-source maintenance for [**$24.99 one-time?**][paypal]
- 🚀         Love open-source tools? Me too! How about supporting one hour of open-source development for just [**$49.99 one-time ?**][paypal]

<!-- Personl Links -->
[paypal]: https://sva.onl/paypal
[buymeacoffee]: https://sva.onl/buymeacoffee
[twitter]: https://sva.onl/twitter/
[website]: https://sva.onl/website/


## Connect & Say 👋
- **Follow** me on [👨‍💻 Github][github] and stay updated on free and open-source software
- **Follow** me on [🐦 Twitter][twitter] to get updates on my latest open source projects
- **Message** me on [📠 Telegram][telegram]
- **Follow** my pet on [Instagram][sofythelabrador] for some _dog-tastic_ updates!

<!-- Personl Links -->
[sofythelabrador]: https://www.instagram.com/sofythelabrador/
[github]: https://sva.onl/github/
[twitter]: https://sva.onl/twitter/
[telegram]: https://sva.onl/telegram/


---

<p align="center">
<i>Built With ♥ By <a href="https://sva.onl/twitter"  target="_blank" rel="noopener noreferrer">Varun Sridharan</a> <a href="https://en.wikipedia.org/wiki/India">
   <img src="https://cdn.svarun.dev/flag-india.jpg" width="20px"/></a> </i> <br/><br/>
   <img src="https://cdn.svarun.dev/codeispoetry.png"/>
</p>

---


<!-- END common-footer.mustache  -->
