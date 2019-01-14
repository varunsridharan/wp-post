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
## Sponsored By
[![DigitalOcean](https://vsp.ams3.cdn.digitaloceanspaces.com/cdn/DO_Logo_Horizontal_Blue-small.png)](https://s.svarun.in/Ef)  [![JetBrains](https://vsp.ams3.cdn.digitaloceanspaces.com/cdn/phpstorm-small.png?v3)](https://www.jetbrains.com)
