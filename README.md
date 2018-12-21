# WP Post
Simple WP Post Class With Advanced Options.


## Installation
The preferred way to install this extension is through [Composer](http://getcomposer.org/download/).

To install **WP_Post library**, simply:

    $ composer require Varunsridharan/WP_Post

The previous command will only install the necessary files, if you prefer to **download the entire source code** you can use:

    $ composer require Varunsridharan/WP_Post --prefer-source

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
[![DigitalOcean](https://vsp.ams3.cdn.digitaloceanspaces.com/cdn/DO_Logo_Horizontal_Blue.png)](https://s.svarun.in/Ef)
