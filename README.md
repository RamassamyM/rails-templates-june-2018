# Rails Templates

Quickly generate a rails app with the default [Wagon](https://www.lewagon.com) configuration
using [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).


## Minimal

Get a minimal rails 5.1+ app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/RamassamyM/rails-templates-june-2018/master/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME \
  --skip-test-unit
```

## Devise

Same as minimal **plus** a Devise install with a generated `User` model.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/RamassamyM/rails-templates-june-2018/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME \
  --skip-test-unit
```

## Devise with ldap

Same as Devise **plus** a LDAP config

```bash
rails new --database postgresql --webpack -m https://raw.githubusercontent.com/RamassamyM/rails-templates-june-2018/master/devise-ldap.rb CHANGE_THIS_TO_YOUR_RAILS_APP_NAME --skip-test-unit
```
