# DevOps Engineer Coding Assignment

## About the application
Build an application for scheduling the bug engineer for the week.

The bug engineer will be the primary contact during that week for bug reports.

### Application requirements
- Create a schedule based on the names provided in `engineers.yml`
- The bug engineer will be responsible for a week
- An engineer will be able to switch schedules with another engineer
- The app will have a web interface that you can see who is the bug engineer for the week and who are the bug engineers scheduled for the current month
  + **Recommendation:** Having a calendar like UI would be a good way for navigation
  + It should be able to navigate to the past or the future to check who will be on schedule
- Please take into considerations of holidays (U.S. National holidays will be enough) and don't have the engineers on those days

####  Note:
Requirements are designed to be vague, and while it's good to ask questions to clarify on requirements, for this coding challenge, we want to see how you are going to design the system so we will not be accepting questions regarding detailed requirement specifications. However, You are welcome to state in your documentations why you designed the system the way you did.

### Task specific requirements
- Please use a Ruby web framework
  + We will not disqualify you because you've never used a Ruby framework or unfamiliar with the syntax, but we do expect you to learn it if you've never used it before
  + If you're not used to Ruby, [Sinatra](http://sinatrarb.com/) could be a good point of entry since it's very basic and highly configurable, if you have some exposure to Ruby, [Ruby on Rails](http://rubyonrails.org/) might be easier for you
- Please have an architecture design of the app ready before you implement it
  + __Architecture design:__ e.g. How models (or components) will be interacting with each other
  + Have a picture of a drawing or the kind will be fine and upload it with the source code
- Please have automated tests, minimum unit tests (integration tests will be a plus)
  + [RSpec](http://rspec.info/) is one of the framework you can utilize
  + Take a look at [Capybara](https://github.com/teamcapybara/capybara) if you are willing to go all the way to end to end testing
- Please have the code publically accessible (e.g. on GitHub) and have the source code under version control
- Please provide documentation of the following
  + How to get the app running locally
  + How to run the tests
  + How to use the app

#### Optional (bonus)
Deploy the app and have it publically accessible in case the instruction for running the app locally doesn't work. [Heroku](https://www.heroku.com/) is a good way to start.

### Time limit
There will be no deadlines.

### Handing in the assignment
Please send an email to jobs@cerego.com with the title `DevOps coding assignment` with your
- Name
- Resume
- A link to your source code (and the hosted app if deployed)


Thank you for your interest and looking to see your project.
