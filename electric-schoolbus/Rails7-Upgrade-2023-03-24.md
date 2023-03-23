## Rails 6 ➡️ 7 Upgrade Guide Page Review

<!--toc:start-->
- [Resources:](#resources)
- [Things changing - TODOs](#things-changing-todos)
  - [Update to Spring >3.0](#update-to-spring-30)
  - [Sprockets:](#sprockets)
  - [Zeitwerk - Autoloading](#zeitwerk-autoloading)
  - [Remove config.autoloader](#remove-configautoloader)
  - [Audit usage of ActiveSupport::Dependencies](#audit-usage-of-activesupportdependencies)
  - [Autoloading during initialization](#autoloading-during-initialization)
  - [autoload_once_paths](#autoloadoncepaths)
  - [ActionDispatch content_type](#actiondispatch-contenttype)
  - [Change to Key generator digest class to use SHA256](#change-to-key-generator-digest-class-to-use-sha256)
  - [ActiveSupport::Cache](#activesupportcache)
  - [Rails version is not included in the schema dump](#rails-version-is-not-included-in-the-schema-dump)
<!--toc:end-->

#### Presented by James Kiesel
###### (Notes by Adam Henley)

## Resources
[Upgrading from Rails 6.1 to Rails 7.0](https://guides.rubyonrails.org/upgrading_ruby_on_rails.html#upgrading-from-rails-6-1-to-rails-7-0)


[Classic to Zeitwerk HOWTO](https://guides.rubyonrails.org/v7.0/classic_to_zeitwerk_howto.html) (Linked from main upgrade guide)

## Things changing - TODOs

### Update to Spring >3.0
 - Mostly at >4 in most places
 - Some places have 2.1 though?
 - Predicted to only be required/present when running in development environment

### Sprockets:
  - Asset pipeline stuff
  - Now an optional dependency
  - To be deprecated
  - Audit usage

### Zeitwerk - Autoloading
  - We will look into this ~~at a later date~~ now
  - Used in `rewards` app
  - [Don't be scared](https://guides.rubyonrails.org/v7.0/classic_to_zeitwerk_howto.html#i-am-scared)
    - Will blow up big and early if it's an issue
  - check to check if it's working
  - [Acronym inflection](https://guides.rubyonrails.org/v7.0/classic_to_zeitwerk_howto.html#acronyms) changes e.g. Gst => GST
  - Look at any acronyms
  - Concerns
    - Since we're on the side of no Concerns, we're going to stay that way ⛔
  - `lib` folder used a lot

### Remove config.autoloader
  - Think everything is done. Question mark?

### Audit usage of ActiveSupport::Dependencies

### Autoloading during initialization
  - deprecating
  - audit usage in intialisers
  - loud warnings : VERY OBVIOUS

### autoload_once_paths
  1. Not sure if/why this would be anywhere
  2. audit still

### ActionDispatch content_type
  - Mostly used in our codebase in the context of setting content_type
    - (not as much - if ever - to access a request's content type)
  - But maybe used in specs?

### Change to Key generator digest class to use SHA256
  - Here be dragons 🐉
  - How does identity do encryption/cookies?
  - Audit this
  - Maybe test process:
    - Deploy to UAT while logged in and try refreshing the page

### ActiveSupport::Cache
  - Audit where we use this
  - Not widely used (we think/allege)

### Rails version is not included in the schema dump
  - Using structure.sql most of the time
  - Probably don't care about this?



