#Rails War

## Introduction

## Devise

Devise will be the one tracking the user.

```console
gem 'devise', '~> 4.9', '>= 4.9.3'
```

```console
config.action_mailer.default_url_options = { host: 'localhost', port: 3000 }
```
Modify the above ***host: 'actual_host'*** for the hosting website.

## Structure the Devise Views.

### new_user_session (sign_in):GET



