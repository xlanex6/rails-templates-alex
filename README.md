# Rails Templates

Quickly generate a rails app with the default [Wagon](http://www.lewagon.org) configuration
using [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).

###Quick custom
		Move SCSS —> SASS
		Add browser sync on Development ENV.
		

Big thanks to [ Le Wagon](http://www.lewagon.org).

## Devise

Same as minimal **plus** a Devise install with a generated `User` model.


```bash
rails new \
  -T --database postgresql \
  -m https://raw.githubusercontent.com/xlanex6/rails-templates-alex/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```


