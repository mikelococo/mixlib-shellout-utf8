Test Kitchen - UTF-8 Drivers Fork
=================================

This is a fork of v1.6.1 of the mixlib-shellout gem. A variety of tools use mixlib-shellout and have their locale coerced to C from UTF-8 when shelling out, causing exceptions when Unicode characters are encounted.

For documentation about test-kitchen, visit https://github.com/opscode/mixlib-shellout

Usage Via Bundler
=================

In your Gemfile, replace:

```ruby
gem 'mixlib-shellout'
```

with:

```ruby
gem 'mixlib-shellout',
  github: 'mikelococo/mixlib-shellout-utf8',
  branch: 'utf8'
```

Then bundle install and run kitchen as per normal.

(Lack of) Updates
=================

This fork may or may not get timely updates, the release the fork branched off is listed at the top of this README. If mixlib-shellout switches the default locale, this repo will be deleted.
