# Erin Greenhalgh - M2 Portfolio

## Individual
### Self-Assessment Scores:
* End of mod assessment:
* Individual work and projects:
* Group work and projects:
* Community participation:
* Peer and instructor feedback:


### Areas of Emphasis

TBD

### End of Module Assessment
* Analytic/Algorithmic Thinking:  4
* Ruby Syntax & Standard Library: 3
* Rails Syntax & API:             3
* MVC & Rails Style:              3
* Testing:                        3
* Collaboration:                  3

## Evaluated Projects

### Rush Hour

* [GitHub URL](https://github.com/icorson3/rush-hour-skeleton)
* [Original Assignment](https://github.com/turingschool/curriculum/blob/master/source/projects/rush_hour.md)

Purpose: Build a web application using Sinatra and ActiveRecord that analyzes web traffic data from various registered clients.

This project was our first attempt to synthesize what we had learned so far about database design, interacting with the database via active record, and implementing the MVC model using Sinatra. It was a challenge to become more comfortable with ActiveRecord and to default to its methods and capabilities rather than trying to implement data manipulation with Ruby. It was rewarding to complete a project with some kind of interface and to implement Bootstrap and some custom CSS to make it presentable.


####Notes from eval with Andrew:
* Testing is solid, but there was too much use of hard-coded values rather than calling ActiveRecord relations, e.g., hard-coding a client ID of 1 instead of calling client.id. It was good to move some of the work of test setup to our test helper, but more of the work of creating payloads and analyzing the data should be done in the helper rather than the test. This will make the tests easier to read and help avoid having the tests be saturated with logic they don't need to know about.
* We could also benefit from more organization within our test directory.
* Missing feature test for events
* Also be careful that test names accurately reflect the contents of the test
* Get rid of nesting conditionals in the controller. Nested conditionals are a sign that we could refactor these more
* Could refactor our analyzer classes; they are currently doing both checking for correct data and then populating the database.
* Include comments and get in the habit of doing code reviews. Also do a better job of pull request messages. Ideally the message should explain everything in the files changed to a person who is not familiar with your code.

####Project Scores
* Functional expectations:                        3
* Test-driven development:                        3
* Encapsulation / breaking logic into components: 3
* Sinatra / Web and Business Logic:               3
* Basic Ruby:                                     4
* Views:                                          3
* Workflow:                                       3

####Feedback from peers:
**Lucy Fox:**
"I've really appreciated that Erin makes sure she understands a problem before she moves on. However, I believe Erin (and probably all of us) could work on improving the problem solving process so that it's a series of productive steps in the right direction and there's less circling a bug. Overall, I think Erin has been a wonderful team member and has contributed helpful code and ideas to the project."

**Ilana Corson:**
"Erin is a secret beast.  Erin could speak her mind a bit more when it comes to her way to do things, she knows what’s up! She is able to come up with logical solutions to problems that come up in the group.""

## Little Shop

* [GitHub URL]()
* [OriginalAssignment](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

Purpose: Build an ecommerce web application according to a series of user stories. Application includes a cart and checkout functionality, user authentication, and admin authorization.

This project required us to synthesize everything we learned this mod about the MVC model, ActiveRecord, Rails, and web application features. It was also an exercise in agile and git workflow.

####Notes from eval with Jhun:

TBD

####Project Scores:

TBD

## Non-Evaluated Projects
* [Robot World](https://github.com/ErinGreenhalgh/robot_world)
* [Tool Chest](https://github.com/ErinGreenhalgh/tool_chest)
* [Mix Master](https://github.com/ErinGreenhalgh/mix_master)

## Peer Evaluated Projects
* [Rails Mini Project](https://github.com/ErinGreenhalgh/gif_generator)

## Non-class Work

### Blog Post
* [Pushing Logic Down the Stack](https://medium.com/@e_green/pushing-logic-down-the-stack-an-exercise-in-refactoring-e4995fcc9733#.bnrhvkmdz)

### Posse Work
This mod I joined Armstrong Posse to work on some machine learning with Erinna and Aaron. With their help, I implemented a linear regression learning algorithm that finds the line of best fit based on a training set. I intend to keep working with the algorithm, potentially integrating it into Little Shop to implement a rating recommendation system. Though this is only a baby machine learning algorithm, and nowhere close to the best tool for implementing a rating system, I plan to use it an an exercise in integrating this tool into an existing project and to get a conceptual basis for the process of machine learning.

* [Linear Regression Learning Algorithm](https://github.com/ErinGreenhalgh/linear_regression)

## Community

### Giving Feedback

#####Feedback for others:

TBD

# Being a Community Member
##Feedback for me:

TBD

## Playing a Part

TBD

## Review

### Notes

( Leave blanks for reviewers )

### Outcome

( Leave blanks for reviewers )
