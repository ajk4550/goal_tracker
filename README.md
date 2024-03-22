# Hotwire Hands-On Training

1. Clone the code into apps folder:
2. Bundle install
bundle config set --local path vendor/bundle

3. Create symlink
   ln -snf ~/apps/goal_tracker/public ~/depot/mainline/weblive/bizappsroot/goal_tracker

4. Add app to the list of apps in httpd.conf.erb
5. Test config and restart apache
6. Run migrations (SQLite)
7. Test app loads:
   https://apps-business-main-ajk292.dev.web.sha.cornell.edu/goal_tracker/

# Tasks:

1. Allow goal titles to be edited inline using turbo
2. Allow deleting of goals via turbo streams
3. Allow goals to be added from the index page by making a form appear when you click the "New Goal" button.
