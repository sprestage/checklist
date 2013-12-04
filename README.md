Checklist
=======

Start with a simple task list application where users can create tasks, mark them as complete, or
remove them.  Each of these actions requires the page to be fully reloaded.  The goal is to add
AJAX so that this can be done without a page reload.

Setup
=======

Run these commands to try it out.

```
bundle
rake db:setup
rails s
```

Requires Ruby 1.9.2 or later to run.

Credits
=======

This starts with the RailsCast #136 sample application and walks me through jQuery and Ajax changes to improve
the application.  I really like having this app around as I find it personally useful as well as a good exercise.


Critical Failures
=======
Tests currently fail
