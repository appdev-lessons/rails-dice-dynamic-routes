# Rails: Dice Roll with dynamic path segments

In this project, you will rebuild the Dice Roll app that you made in Sinatra; this time using Rails.

Here is your target: [dice-roll.matchthetarget.com](https://dice-roll.matchthetarget.com/)

This project includes automated tests, so click on this button to get started:

LTI{Load Rails Dice Roll assignment}(https://grades.firstdraft.com/launch)[S9ymPy6WCsn18gLbByVbZQ7k]{vfdtzJb5bLYqYwuqgeRKpc5d}(10)[Rails Dice Roll Project]

Then, fork the repository and create your Codespace. Start your live app preview with `bin/dev` once the Codespace is setup.

You can use the code from Rails RPS and Sinatra Dice Dynamic to match the target. You should keep the [RCAV Flowchart lesson handy](https://learn.firstdraft.com/lessons/120-rcav-flowchart); it's a good reference for building Rails routes:

1. View [the target app](https://dice-roll.matchthetarget.com/) and decide on a resource path to start building.
2. In your Rails app, start with the `config/routes.rb` file to define the **route**.
3. Assign the route a **controller** in the `app/controllers/` directory and add the controller file.
4. Add an **action** in the controller file to handle the Ruby logic that should be executed, possibly pulling user input (from forms) or path input (from dynamic path segments) from the `params` Hash.
5. At the end of the action, render a **view** template in the `app/views/<you_template_folder_name>/` folder (create a new folder under `app/views/` to house your templates).
6. Fill the `.html.erb` view template file with HTML and embedded Ruby tags to be sent back to the user of your app.
7. Rinse and repeat! Route, Controller, Action, View (RCAV). 

Revisit the [Dynamic Path Segments lesson](https://learn.firstdraft.com/lessons/111-sinatra-dice-dynamic-routes) if you need a refresher on this syntax:

```ruby
get("/my_cool_route/:param_one/:param_two", { :controller => "my_controller", :action => "some_action" })
```

When you think you have the target matched, run `rake grade` to get automated feedback.

---

- Approximately how long (in minutes) did this lesson take you to complete?
{: .free_text_number #time_taken title="Time taken" points="1" answer="any" }
	
---
