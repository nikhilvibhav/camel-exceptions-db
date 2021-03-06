# camel-exceptions-db
Extensions to camel-exceptions-core providing additional Exceptions for database-wrangling problems.

Releases are hosted over at [bintray](https://bintray.com/capgeminiuk/maven/camel-exceptions-db/view) licenced under Apache v.2.0.

![Build Status](https://travis-ci.org/andrewharmellaw/camel-exceptions-db.svg?branch=master)

It's recommended when you're handling exceptions in Apache Camel that you differentiate between recoverable and irrecoverable exceptions.  These classes take the representations of these two types of exception (from [camel-exceptions-core](https://github.com/andrewharmellaw/camel-exceptions-core)) and create database-specific subclasses.  

They are very simple, extending the relevant Recoverable or IrrecoverableException, and providing a meaningful classname.  Nothing beyond that.  

Isn't it nice when someone does a bunch of your typing for you?
