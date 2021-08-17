# Comments Engine API
This is the first backend project for Koject!

You are a freelancer working remotely from your home! In the morning a client contacted you for a gig: He is the owner of a blog, where he shares his experiences traveling around the world, his blog is amazing and has thousands of visitors each month, the readers are happy following him in his adventures. But there is a problem, the blog does not have a comment section, and as consequence, he can't connect with his followers effectively.

His blog is actually built with React.js for the Frontend, and he is using a custom legacy Backend for the blogs, which is very hard to maintain. He already hired a Frontend Engineer that will help to implement the comments system in the Frontend, but he needs a Backend Engineer to implement the feature in the Backend, that is the reason you are here!

The problem is that you can't modify the current Backend, you don't have the knowledge for that, but as we are in 2021, you decide to implement a microservice dedicated just to this task, it will store and serve the comments of the blog! This microservice will run along the legacy backend, but will never interact with it, so this is an isolated microservice!

Now, you are in a privileged position, because you are about to start a greenfield project, where you will take all the decisions regarding languages, libraries, technologies, and architectural patterns!

## Requirements
1. The client requires that each post in his blog gets backed by a comments section, so you need a way to filter comments by blog post
2. He wants that as a minimum the comment box gets a level of depth/nesting, that is comments that have replies. (But this can be higher if you want to assume the task)
3. He wants to allow anonymous users that can comment anytime, but also want to give the option to the users to submit a nickname along with the comments.

## Extras
1. Support for arbitrary levels of nesting in the comments, just like Reddit!
