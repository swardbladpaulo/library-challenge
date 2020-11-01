## Library Challenge
### Week 1 Ruby challenge

### User Stories

As a Library
In order to allow visitors to rent books
I want the visitors to view a list of available books in the library

As a Visitor
In order to lend a book
I want to see the title and the author of the book

As a Library 
I want the return date to be a month ahead of the checkout date
So that the lender knows when to return it

## The Code

The code lets a user search for a book via author or title. The user can also see if a book is available. 

## Dependencies

Rspec https://rubygems.org/gems/rspec/
YAML (https://yaml.org/)
source 'https://rubygems.org'

## Setup

* Fork the repo from https://github.com/FlisAnn/library-challenge
* In your terminal go to the library-challange folder
* Type IRB and the following:
 ```
 require 'yaml'
 load './lib/library.rb'
 load './lib/user.rb'
 ```

## Instructions

Creating a collection
 ```
collection = YAML.load_file('./lib/data.yml')

```

## Acknowledgements

Course material from Craft Academy
Demos from our coaches


## Update and Improvments

We want to create the functionality of changing the value of available so that we can check out a book. 

## Licence

* The MIT License (MIT).



Instructions
-------
Read this entire README carefully and follow all instructions.

* Challenge time: this weekend, until Monday 9am
* Feel free to use Google, Stack Overflow, your notes, previously written code, books, etc. but work on your own
* If you refer to or have in whole or partially used the solution of another coach or student, please put a link to that in your README
* If you have a partial solution, **still check in a partial solution to GitHub and create a Pull Request**
* You must submit a Pull Request to this repository with your code by 9.30am Monday morning - before the stand-up


### Tasks
----

* Fork the challenge repo: https://github.com/CraftAcademy/library-challenge
* Run the command `bundle install` in the project directory to ensure you have all the gems
* Write your specs and implementation
* Be smart about using Git: commit and push often. Use feature branches.
* Create a Pull Request as soon as possible
* Read the comments from Hound and fix any issues that the service points out.

### Tips
----

##### Some hints:
  * A Person needs to have a list of books that he currently has in his possession. That list needs to include the return date.
  * The return date can be calculated using the `Date` object. Out of the box, there are methods you can use to add days to the current date.
  * Make use of `doubles` when writing your specs
  * Follow the [naming conventions/standards](https://craftacademy.gitbooks.io/coding-as-a-craft/content/extras/naming_standards.html) for methods and variables

### What we are looking for
----
##### I'm hoping to see that:
* You can take a problem set and write a well tested implementation on your own.
* You understand how to define Ruby Classes and work with objects.
* You understand how classes can interact with each other.
* You know how to make use of arrays, hashes, and associated methods to create dynamic lists.
* You know how to write specs and use them as a blueprint in your development.
* I can track your work by following you commit history - so please commit as soon you are done with a feature or when you have made a test pass.

##### In your Pull Request, I'm hoping to see:
* That you are testing the right thing in the right spec file.
* That all tests passing - green is good!
* High test coverage (above 95% is accepted)
* The code is easy to follow: every class has a clear responsibility, methods are short, code is nicely formatted, etc.
* The `README.md` includes information on how to use your solution with command examples in `irb`. (Feel free to remove this text)


**Happy coding!**
