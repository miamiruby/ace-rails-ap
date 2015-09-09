# ace-rails-ap

[![Join the chat at https://gitter.im/miamiruby/ace-rails-ap](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/miamiruby/ace-rails-ap?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

The [Ajax.org Cloud9 Editor (Ace)](/ajaxorg/ace) for the Rails 3.1 asset 
pipeline.

## Usage

`Gemfile`:

```ruby
gem 'ace-rails-ap'
```

`application.js`:

```javascript
//= require ace
```

To include a theme or mode, just put:

```javascript
//= require theme-[sometheme].js
//= require mode-[somemode].js
```

After `//= require ace` in your `application.js` manifest.

Then just use Ace like normal.

