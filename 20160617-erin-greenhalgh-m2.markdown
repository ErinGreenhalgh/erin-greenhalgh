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

TBD

## Work

The projects below are my evaluated projects.

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
"EI've really appreciated that Erin makes sure she understands a problem before she moves on. However, I believe Erin (and probably all of us) could work on improving the problem solving process so that it's a series of productive steps in the right direction and there's less circling a bug. Overall, I think Erin has been a wonderful team member and has contributed helpful code and ideas to the project."

**Ilana Corson:**
"Erin is a secret beast.  Erin could speak her mind a bit more when it comes to her way to do things, she knows what’s up! She is able to come up with logical solutions to problems that come up in the group.""

## Little Shop

* [GitHub URL]()
* [Original Assignment](https://github.com/turingschool/curriculum/blob/master/source/projects/little_shop.markdown)

Purpose:

####Notes from eval with ?:

TBD

####Project Scores:

TBD

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
