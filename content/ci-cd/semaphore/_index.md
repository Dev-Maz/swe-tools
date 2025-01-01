+++
title = "Semaphore"
type = "chapter"
+++

Semaphore is a hosted continuous integration and deployment service used for testing and deploying software projects 
hosted on GitHub and BitBucket.

While open source projects can use Semaphore for free in its full capacity, free use for private projects is limited to
100 builds per month (Semaphore Classic) or $20 of service every month (Semaphore 2.0).

One of Semaphore’s features is native Docker support, which enables testing and deploying Docker-based applications.
Semaphore also offers Boosters, a feature that reduces the duration of running a test suite to that of the longest test
through automatic parallelization of builds for Ruby projects.

Semaphore supports the following programming languages: C/C++, Clojure, Elixir, Go, Java, JavaScript, PHP, Python, Ruby
and Scala. Projects written in other programming languages demand manual configuration.

Some of the supported frameworks include: test/unit, RSpec, Cucumber, Steak, Capybara Webkit, Jasmine, Karma, Minitest,
Poltergeist, PhantomJS.

Deployment integrations include AWS, Heroku, Capistrano and Cloud 66.

Semaphore 2.0 supports iOS and MacOS.

Once the project and the branch have been selected, Semaphore determines the configuration of the project, by extracting
meta information. After customizing and configuring the wanted builds, Semaphore begins testing. The results of the 
performed jobs are highlighted red (failed) or green (passed). If a test fails, the developer needs to further
configure and fix the code until the test is green.
