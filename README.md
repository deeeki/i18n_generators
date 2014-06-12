# I18n generators

This is a fork working with Microsoft API credentials.

## Original

https://github.com/amatsuda/i18n_generators

Copyright (c) 2008 Akira Matsuda, released under the MIT license

## Usage

* 1. Get credentials. See [BingTranslator gem's flow](https://github.com/CodeBlock/bing_translator-gem#getting-a-client-id-and-secret)
* 2. Bundle it

```ruby
gem 'i18n_generators', github: 'deeeki/i18n_generators', branch: 'bing_translator', group: 'development'
```

* 3. Generate with credentials

```sh
MICROSOFT_CLIENT_ID=YOUR_CLIENT_ID \
MICROSOFT_CLIENT_SECRET=YOUR_CLIENT_SECRET \
rails g i18n_translation ja # de-AT, pt-BR, etc.
```
