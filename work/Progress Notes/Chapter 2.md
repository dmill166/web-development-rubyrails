# Progress Notes

These markdown files will cover progress notes as progressing through chapter content.

## Chapter 2
### First Environment Details:
Lessons learned include:
* Creating new Rails application & a new controller
* Creating dynamic content in the controller & displaying it via a view
* Linked pages together
* Debugged problems in code / URL-side
* Illustrated a few Ruby expressions

### Commands to note (for MacOS X Terminal / RubyMine terminal): 
* `cd`: Changes directory to specified option (tab for auto-completion suggestions)
* `rails new <name here>`: Spins up a new Rails directory with the provided name including framework creation
* `ls`: Lists all folder & files in current directory
* `bin/rails about`: Generates list of environment configuration details (Ruby version, Rails version, etc)
* `rails server`: Starts up the current directory's web application
* `rails generate controller <controller_name> **<action_name(s)>`: Creates a Rails controller under the provided name & views for each action listed.
  * Controller found in < directory_name>/app/controllers/< here>
  * Views found in < directory_name>/app/views/< controller name>/< .erb files for each requested action>

### Ruby Methods:
* 

### Additional notes:
* In .erb files are primarily HTML; however, between `<%= %>` signifies Ruby code. An example was found on page 27:
```HTML
<h1>Hello From Rails!</h1>
<p>
    It is now <%= Time.now %>
</p>
```
and again on page 36:
```HTML
<p>
  <br>Experimenting with Ruby expressions:<br>

  &nbsp;&nbsp;&nbsp;&nbsp;Addition: 1 + 2 = <%= 1 + 2 %><br>
  &nbsp;&nbsp;&nbsp;&nbsp;Concatenation: "cow" + "boy" = <%= "cow"+"boy" %><br>
  &nbsp;&nbsp;&nbsp;&nbsp;Time in one hour: <%= 1.hour.from_now.localtime %><br>
</p>
```