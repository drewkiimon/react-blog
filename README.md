# React Blog

Interested in learning [Redux](https://www.udemy.com/react-redux/)?

#### A SPA using React, Redux, and lots of cool stuff

This Blog was created in conjunction with Stephen Grider's Udemy class that goes
over the core of using React as a front facing interface for users to interact with,
while we use Redux to handle with Application state (not component state).

### What are some of the dependencies you used?

* **Axios**: Used for doing our AJAX requests without jQuery, and passing it onto payloads
* **react-router-dom**: Used for making our application into a single page application (aka spa); we used the BrowserRouter, Switch, and Route components to navigate to other paths
* **redux-form**: It is used to bind our form to Redux to allow us to use our action creator to send data to our API
* **redux-promise**: This magical little dependency allows our middleware to halt an AJAX call until we get a response back, that we can then pass off to reducers and then our React components
* **lodash ( \_ )**: We used lodash to map out our state, or for one of its other useful functionalities

### How does this application work?

We are using a blogging API given to us by Stephen Grider that allows us to send GET, POST, and DELETE requests with our super secret key to get or delete posts. It was the last leg off his Udemy class, and incorporated everything we have learned up to now.

### Do you recommend this class?

**Yes**, I really do. I am more of a visual learner, so reading about React wasn't very effective for myself when it came to learning the material. His examples are broad enough to span many different projects, but also relative and interesting enough to make me want to continue and add upon what we've created together in the class. The ability to teach about reducers, action creators, component vs application state, and so many other fundamentals of both React and Redux makes me want to continue this learning grind.
