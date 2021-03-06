# svelte-pathfinder changelog

# 2.2.1

* Move build output to a dedicated dist folder

# 2.2.0

* Use single export instead of multiple.
* Fix `prefs` export which was missed in PR.

# 2.1.2

* Fix boolean values convertation.

# 2.1.1

* Minor fix of new query array param formating.

# 2.1.0

* Improve query string parsing
* Support different formats of query string array processing, eg. `?foo[]=1&foo[]=2` (default) and NEW alternative way `?foo=1,2`.
* Support arrays in `path` eg. param`/:variants` in example `/foo|bar|baz` will be parsed as array `$path.variants === ['foo', 'bar', 'baz']`.

# 2.0.0

* Re-write to Typescript (first edition).
* Add `svelte` to devDeps to get typings.
* Improve query string parsing, better support for nesting objects.
* Now configurable from user-land!
* Jest setup (tests coming soon).

# 1.1.0

* Fix URL() base.
* Fix deps.
* Code formatting via Prettier.

## 1.0.0

* First release
