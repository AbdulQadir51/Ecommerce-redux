# Ecommerce-redux

The state management of my website should be managed by Redux instead of React's Context API as I am a senior engineer working on an e-commerce platform.

When I review an e-commerce platform that uses Redux to manage global state, I find that the app uses a Redux store instead of the Context API, and when I examine how the React front end accesses the store, I find a Redux provider. Reviewing how the app determines changes to its global state, I find that it passes reducers to a Redux store instead of using the Context API. When I examine how the app extracts state data from the store, I find that it uses Redux instead of the Context API.
