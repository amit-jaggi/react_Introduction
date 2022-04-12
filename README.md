> ## **React Introduction**
>
> ---
>
> React is an open source front-end JavaScript library which is used for developing dynamic web pages especially for single page applications. It follows a component-based architecture which helps in building reusable UI components. It was created by Jordan Walke, a software engineer working for Facebook. Due to its high demand, it also has a large community support.

> ## **React Features**
>
> ---
>
> It main features are:
>
> 1. It has an easy learning curve because  it requires only the knowledge of JavaScript.
> 2. Uses reusable UI components to develop the view of website.
> 3. Support JSX which helps us to write HTML codes into JavaScript
> 4. Uses Virtual DOM instead of Real DOM which makes the application more faster
> 5. Follows a uni-directional data flow or data binding throughout the application

> ## **SPA Model**
>
> ---
>
> Basically SPA stands for single page application. If a user clicks on any button from the navigation bar of a website and that website navigates to a different web page i. e. only update the page without reloading the browser's page, then that application is known as single page application.

> ## **Virtual DOM**
>
> ---
>
> Virtual DOM is a light-weight JavaScript object having all the similar properties as that of the real DOM object, but does not have the ability to directly update the changes occured. When a complete React application is mounted on the screen with the help of Real DOM, along with that a new Virtual DOM is created. Now when a user makes any changes by clicking of a button, by which a state is updated. The change of state will not directly effect on Real DOM, whereas it will get effect on the Virtual DOM. So, now the updated Virtual DOM will get compared with the previous Real DOM and check for the new changes and this complete procedure is known as Diffing Algorithm. When the new changes is been reflected on the Real DOM, then this procedure is known as Recoinciliation.

> ## **Library v/s Framework**
>
> ---
>
> Library is a set of reuasble functions where the code calls to the different libraries. On the other hand, Framework is piece of code that dedicates the architecture of the project where the Framework calls the code.
>
> Popular libraries are React & jQuery and popular frameworks are angular JS & Vue JS.

> ## **JSX**
>
> ---
>
> JSX stands for JavaScript XML which is simply a syntax extension of JavaScript. It is a type of file used by React which allows developers to directly write HTML like template syntax in React and makes it really easy to understand. Basically it helps to avoid writing the React.createElement() function which is the feature of ECMA Script 5 where as JSX is the feature of ECMA Script 6.

> ## **Babel**
>
> ---
>
> Babel is an inbuild transpiler that converts the ECMA Script 6 code to an ECMA Script 5 code because the browser cannot read JSX which is not a regular JavaScript object. So Babel helps to convert the JSX file to a regular JavaScript object and then pass it to the browser.

>## Difference between class-component & functional-component
>
> ---
> 
> CLASS COMPONENT:
> 1. Class component can be used when you are doing data operations and server calls.
> 2. It contains lifecycle methods.
> 3. Constructor structure is required since these are class components.
> 4. And it contains state variables.

> FUNCTIONAL COMPONENT:
> 1. Functional components can be used mostly when we need to create dumb or stateless components.
> 2. Thses components doen not have lifecycle methods, they have hooks like useEffect.
> 3. Complete constructor structure is not required in these components, so they are easy to handle.
> 4. Do not have state variables, they have hooks like useState, useParams, etc.


>## Difference between named-export and default export
>
> ---
>
> Export without a default tag are named-exports, it use the name of the function or class as their identifier. When we want to import a named component, we can use the same name it was exported with. Names must be imported inside curly brackets. Named exports allow multiple exports in a single file.
>
> Whereas, Default exports are created by including a default tag in the export. Usually, we see default exports happen at the bottom of a file, but it's possible to define them when your component is declared. When importing a default export, we don't use curly brackets. When we import a default export, we can give it whatever name we want. A modules can only have one default export.


