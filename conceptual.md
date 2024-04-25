### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?

	- The React Router gives us straightforward Client-Side Routing.

- What is a single page application?

	- This is a site that uses client-side routing to map between the URL bar and page the user sees via the browser rather than the server.

- What are some differences between client side and server side routing?

	- Client side uses one page while server-side navigation causes the browser to request a page and replace the entire DOM. The server decides what HTML to return based on the URL requested.

- What are two ways of handling redirects with React Router? When would you use each?

	- the useNavigate hook is useful for "you're done here, go here instead, if you go back that's fine" while the Navigate component is useful for "you shouldn't have gotten here go here instead, do not go back"

- What are two different ways to handle page-not-found user experiences using React Router? 

	- A redirect or not found error (404)
	
- How do you grab URL parameters from within a component using React Router?

	- the useParams hook stores info on URL parameters and they can be accessed in the object that it returns in a name: value format.

- What is context in React? When would you use it?

	- Context is a way to distribute universal data across the application that is accessible across all components. It's less repetitive and used for global themes and shared data.

- Describe some differences between class-based components and function
  components in React.
  
  - Class-based components must include a render() method to return UI elements. Functions can now use hooks like useState, useEffect, etc.

- What are some of the problems that hooks were designed to solve?

	- Repetitive code, reducing clutter, a separated hook can be written separately, tested in isolation, and used in any other components.