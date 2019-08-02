# Full Stack 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What is Enzyme and what are some of the methods that it provides?

Enzyme is a tool package for React that assists with testing.  It allows us to simulate user input to the application.

Enzyme is a JavaScript Testing utility for React that makes it easier to assert, manipulate, and traverse your React Components' output. 
mount and render are two methods that come from Enzyme.

#### 2. What is the difference between dynamic and a static routes?

static routes always route to the same information.  Dynamic routes allow a single route to act as a template to store information of many instances. 

React Router introduces a concept called “Dynamic Routing”, which is quite different from the “Static Routing” we are used to. ... “Dynamic Routing” means that routing takes place as your app is rendering, not in a configuration or convention outside of a running app.

#### 3. What is a JSON API?

A JSON API is an external set of data that is referenced in an application.  The data is stored in a JSON format (as a human readable object).

JavaScript Object Notation Application Programming Interface

#### 4. What is a migration and why would you use one?

a migration is an aspect of Rails and the management of databases.  A migration is the way that the model of Rails to create attributes for a set of data.

Rails Migration allows you to use Ruby to define changes to your database schema, making it possible to use a version control system to keep things synchronized with the actual code.

#### 5. Explain how to set up a route in React.

In order to set up a route in React, you must first import the React-Router-DOM into the main App.js file.  Then, under the render/return section of the main component within a <Router> tag, you must set up the route path, defining the url name and which component is being routed to.

import {
	  BrowserRouter as Router,
	  Route,
	  Link
	} from "react-router-dom";
.
.
.
<Route path="/" exact component={Home} />
<Route path="/about/" component={AboutUs} />

#### 6. When would you use a generate resource over a generate controller?

You generate a resource when you a creating a controller that will handle data.  If you want to be able to create, read, update, or delete infomration from that database, then you would generate a resource so that you can create the necessary methods more easily for the purposes of those HTTP verbs.

#### 7. Explain the difference between a controller spec and a request spec.

A controller spec is a file used to create RSpec tests in React.  Controller specs are specifically used for testing the methods within a controller.  A request spec is more of a full system RSpec test. This test ensures that both the methods within the controller are functioning as expected and also that the routes are sending and receiving information correctly.

#### 8. Describe the React component lifecycle. What are some of the lifecycle methods?

A component lifecycle is the time a component is called and rendered, until the page is rerendered or state is changed.

Initialization, Mounting, Updating, and Unmounting. 


#### 9. At this point in the program, what technologies/languages do you find yourself gravitating to?

I definitely find myself gravitating most towards Javascript, Ruby, and React.  I find Rails really interesting and powerful, but it feels a little less intuitive for me. HTML and CSS are the least exciting to me.  While I enjoy the design aspect and like taking the time to make things look good, I always seem to put this off as long as possible, and tend to get frustrated with CSS.  Especially when trying to locate things on the page.