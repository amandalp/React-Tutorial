# React-Tutorial

Context:
- With Javascript Application frameworks, design philosophy is the key differentiating factor. 
- Though JS frameworks, such as EmberJS, AngularJS, Backbone, Knockout, etc. have their differences (in their abstractions, thinking models, and terminology), they all do one thing -- abstract out the DOM in such a way that you don't deal directly with HTML Elements.

The Basics of ReactJS:
Where does it come from?
- The folks at Facebook
What popular apps use React?
- Instagram
How is it different?
- Components!
- The component is the primary building block of React.
- The component generates an "intermediate DOM." The strategy is to create an intermediate DOM before creating the final HTML DOM. The intermediate-DOM is just a JavaScript object graph and is not rendered directly.
- You compose the UI of your application by assembling a tree of Components. The "render" method of each component creates the intermediate DOM. The Intermediate DOM is eventually converted into real HTML DOM.
- Components have a 3-step lifecycle: Mounted, Update, Unmounted.

The following tutorial describes how to create a comments box that you can then drop into antoher app, e.g., blog, social media app, etc. Here you see two interesting things: comments appear in the list before they're saved on the server so it feels fast, and there are live updates so that other users' comments are popped into the comment view in real time.
