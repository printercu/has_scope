## Unreleased

* Add `:in` option: a shortcut for combining the `:using` option with nested hashes
* Support Rails 4.1
* Always return a relation from `apply_scopes` when a class is given, so that chaining
  and calling Enumerable-like methos (eg #each) on top of it is always possible.

## 0.6.0.rc

* Drop support for Rails 3.1 and Ruby 1.8, keep support for Rails 3.2
* Support for Rails 4.0 onward
