# ToDone: A Todo List App


## The Backend

The backend provides all the logic for handling actions on todo items. It is build with [http4s]. Most of our work will be on the backend.


## The Frontend

The frontend provides the user interface. It is built with [Slinky][slinky] and compiles into Javascript code using React. We won't do much work on the front end, though you are welcome to work on this code if you want.


## Tasks

### Task 0

Your first task is to fork the repository, creating your own copy. Why fork instead of clone? Because it allows you have put your changes in a place others can see them, while still being able to receive updates from this repository. 

Once you've made your fork, clone it to your computer.

### Task 1

Get the app running. This should be as simple as going into `sbt`, switching to the `backend` project, and issuing the <del>`run`</del> `~reStart` command. Then visit `http://localhost:3000/`. If everything works you will see the ToDone user interface. Click around and you'll that many things don't work (some because, at the time of writing, the user interface is not finished). Our task is to fix all these things to create a working app. In the process we'll learn a lot about Scala and web development.

[http4s]: https://http4s.org/
[slinky]: https://slinky.dev/
