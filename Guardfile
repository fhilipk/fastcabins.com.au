# A sample Guardfile
# More info at https://github.com/guard/guard#readme

## Uncomment and set this to only include directories you want to watch
# directories %w(app lib config test spec features)

## Uncomment to clear the screen before every task
# clearing :on

## Guard internally checks for changes in the Guardfile and exits.
## If you want Guard to automatically start up again, run guard in a
## shell loop, e.g.:
##
##  $ while bundle exec guard; do echo "Restarting Guard..."; done
##
## Note: if you are using the `directories` clause above and you are not
## watching the project directory ('.'), then you will want to move
## the Guardfile to a watched dir and symlink it back, e.g.
#
#  $ mkdir config
#  $ mv Guardfile config/
#  $ ln -s config/Guardfile .
#
# and, you'll have to watch "config/Guardfile" instead of "Guardfile"

# This will concatenate the javascript files specified in :files to public/js/all.js
#
# Specifying every single file in the array like %w(a b c) to maintain the loading order is suggested - See https://github.com/makevoid/guard-concat for more info
#

guard :concat, type: "js", files: %w(), input_dir: "javascripts", output: "public/js/all"
guard :concat, type: "css", files: %w(), input_dir: "stylesheets", output: "public/css/all"
# guard :concat, type: "html", files: %w(partials/* index), input_dir: "./", output: "./"
