# Q0: Why is this error being thrown?

Because there is not a model for Pokemon yet.


# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

Because HomeController we have an index method that looks for random pokemon in all pokemon with a trainer value of nil


# Question 2a: What does the following line in the help text do? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

It makes a Button element in HTML that maps to a patch route in routes.rb which routes to the capture_path. capture_path(id: @pokemon) specifies the path that the button routes to and the pokemon id

# Question 3: What would you name your own Pokemon?

yadelasaur

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

flash[:error] allows for error to show

# Give us feedback on the project and decal below!

I thought this project was super fun. This class is fantastic and I really like how I'm becoming more and more better at Rails development

# Extra credit: Link your Heroku deployed app
