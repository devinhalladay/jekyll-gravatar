jekyll-gravatar
===============

## Installation
Place gravatar.rb into your site's `_plugins` directory

## Usage
Just use `{{ 'me@example.com' | gravatar }}`. It'll return the link to your Gravatar.

### Example:
```html
<figure>
  <img src="{{ 'me@example.com' | gravatar }}" alt="My beautiful face.">
</figure>
```

### Changing avatar size
Go into `gravatar.rb` and edit line 6. Change `?s=600` to `?s=[your-size-here]`. If your Gravatar is a high-res image, you can use a relatively large size. If it's a low-quality image, do whatever you want. I don't care.