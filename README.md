Agama
Agama is an auth-server component that offers an alternative way to build authentication flows in Janssen server. Originally, person authentication flows are defined in the server by means of jython scripts that adhere to a predefined API. With Agama, flows are coded in a DSL (domain specific language) designed for the sole purpose of writing web flows.

Some advantages of using Agama include:

Ability to express authentication flows in a clean and concise way
Flow composition is supported out-of-the-box: reuse of an existing flow in another requires no effort
Reasoning about flows behavior is easy (as consequence of points 1 and 2). This makes flow modifications and refactoring straightforward
Small cognitive load. Agama DSL is a very small language with simple, non-distracting syntax
Friendly UI templating engine. No complexities when authoring web pages - stay focused on writing HTML markup
