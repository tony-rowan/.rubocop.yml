# .rubocop.yml
My personal preferred [`rubocop`](https://github.com/rubocop-hq/rubocop) configuration.

## Usage
This configuration can be used by copying the `.rubocop.yml` file to you project's
directory; or, if there is a eed to make further modifications, by inheriting from 
this configuration file. In `.rubocop.yml`:

```yml
inherit_from:
  - https://raw.githubusercontent.com/tony-rowan/.rubocop.yml/main/.rubocop.yml
```

### Rails Projects
For Rails projects using [`rubocop-rails`](https://github.com/rubocop-hq/rubocop-rails)
there is a more specific configuration.

```yml
inherit_from:
  - https://raw.githubusercontent.com/tony-rowan/.rubocop.yml/main/.rubocop.rails.yml
```
