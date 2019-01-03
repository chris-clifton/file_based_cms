# Introduction
The goal of this project is to build a simple file-based content management system. This project uses a new format that presents each assignment in three parts: a list of requirements, a list of implementation details, and an example solution that takes the requirements and implementation details into account.

The Requirements are written as they might be if you were working on a project with a client or project designer. They are high-level, presented from a user's perspective, and will typically be devoid of any technical information.

As you move through each assignment, first read through the requirements and think about what the application needs to do in order to satisfy the requirements. Next, think about how the software will accomplish these things and what changes you need to make to it so that it can.

>Some of the assignments will contain Hints. They are there to help keep you >on track, so don't hesitate to look at them after coming up with a plan on >your own.

Once you have a plan in mind and you're fairly confident in it, you can start making the changes you identified needed to be made. Each assignment also includes an Implementation section with a list of concrete steps that need to be completed in order to fulfill the assignment's requirements. Feel free to use the Implementation section as a reference, but it is important that you come up with a plan before looking at the steps we've provided.

Finally, each assignment has a Solution, which is an example solution based on the Requirements and Implementation sections. It is OK if your solution is different than the one that is supplied as long as you can describe how they are different and if there will be any noticeable difference to a user.

Partway through the project, we'll start looking at writing tests for Sinatra applications. At that point, Solution will also contain a set of tests that are relevant to the current assignment. It's a good idea to think about what the tests should be doing and trying to write them yourself before comparing your tests to the example tests and moving on to write and verify the rest of the solution.

As you work through the project, focus on and complete each set of requirements before moving on to the next set.

>This Project is Incompatible with Heroku
>
>This project uses the filesystem to persist data, and as a result, it isn't a good fit for Heroku. Applications running on Heroku only have access to an ephemeral >filesystem. This means any files that are written by a program will be lost each time the application goes to sleep, is redeployed, or restarts (which typically >happens every 24 hours).
>
>This project will, however, run just fine within your development environment as you work through the lesson. Using the filesystem to persist data in this project >provides an opportunity to focus on the fundamentals of web development while gaining some experience with the Ruby File and IO classes.
>
>The use of files on the filesystem to persist data works fine for small projects, but in most production applications, using an external datastore such as a database >is usually a better idea. We'll work more with databases in later courses.