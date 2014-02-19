rails_engines_seed
==================

### start app
* <code>bundle</code>
* <code>rake db:migrate</code>
* <code>rails server</code>


### admin
<code> admin.localhost.com:3000/admin/login </code>


### folders
<pre>
apps
  shared
    app
      assets
      controllers
        shared
          controller
            authentication.rb
      models
        shared
          model
            read_only.rb
          user
            user_display.rb
      views
        shared
          layouts
  marketing
    app
      controllers
        marketing
          application_controller.rb
          home_controller.rb
        models
          marketing
            user.rb
    db
      migrate
  account
    app
      controllers
      models
        content
          user.rb
          post.rb
    db
      migrate
  content
    app
      assets
      controllers
      models
        admin
          post.rb
          user.rb
    db
      migrate
  admin
    app
      assets
      controllers
      models
        admin
          admin_notes.rb
          post.rb
          user.rb
      views
        layouts
    db
      migrate
config
gems
spec
</pre>
