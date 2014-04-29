# About

Once you've gone through the process of creating a new app within rails, use this cheatsheet to learn the [haml language](http://haml.info/about.html), then find and create within your views.

# Easy Conversion

http://html2haml.heroku.com/

If you've already gone through scaffolding, for instance using the bootstrap-sass gem, you can save your erb files as html.haml, then copy the html to this awesome conversion site and transfer the haml back to your views.

Basic Tips
* indentation
* html conversion
* deprecated

# Make Sure HAML Is Installed

If you are working with rails, head over to http://rubygems.org/gems/haml. You will want to include the haml gem in your Gemfile and then run bundle install again.

Once HAML is installed you will signify that you want to use HAML files by changeing your view files to have a .haml extension. For instance index.html.haml

Now you can start writing haml code within that file. Haml will then take what you write and convert it to HTML.