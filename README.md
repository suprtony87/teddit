# Teddit

First, fork this repository and run:

```bash
cd ~/Sites/
git clone https://github.com/your-username-here/teddit.git
```

(be sure to fill in your actual GitHub username there).

Next, copy the following code into sublime text, and save it as `~/Sites/teddit/your_name_here/teddit.rb`:

```ruby
# Teddit Conditionals

# Let's add a new Teddit feature. Automatic upvotes!
# Complete the application below.
# Where you see comments (lines that begin with #) replace it with code so that the program works.

def get_input
  # Get input from the user.
end

def calculate_upvotes(story)
  # Write code so that:
    # If the story is about cats multiply the upvotes by 5
    # If the story is about bacon multiply the upvotes by 8
    # If the story is about food it gets 3 times the upvotes.

    #For example:
    # "Cats frolic despite tuna shortage" should give you 5 times the upvotes!
end

puts "Welcome to Teddit! a text based news aggregator. Get today's news tomorrow!"
puts "Please enter a News story:"
story = get_input
upvotes = calculate_upvotes(story)
puts "New story added! #{story}, Current Upvotes: #{upvotes}"
```

Follow the instructions in the comments, and when you are finished, save the file, commit the code to Git and push it to GitHub:

```bash
cd ~/Sites/teddit/your_name_here
git add teddit.rb
git commit -m "Adding teddit exercise"
git push origin master
```
