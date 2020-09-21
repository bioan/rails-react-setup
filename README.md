# rails-react-setup


rails new . --force --no-deps --database=postgresql -T --webpack=react --skip-coffee --skip-turbolinks

*optionally: --skip-bundle - don't run be install*

`rails g scaffold_controller Model --skip-template-engine`

To create a controller with most methods already functional. edit/new actions are included, so would need to be manually excluded . *


`/config/application.rb` set the following:
```
config.generators.assets = false
config.generators.helper = false
config.generators.javascript = false
```
