#React in Depth

* Overview
* Adding Properties
* First Component
* Events
* Mapping Data
* State and Nesting Components
* Adding State Data Through a Form
* Deleting State Data
* Updating State Data
* Persisting State Data to Firebase

## States & props

* Components hold properties (props) that can be passed in as attributes
* Components can maintain internal "state" data
* When a state is changed, the component is re-rendered and markup will be updated. This makes React very dynamic

## Lifecycle Methods

Methods fired when component is rendered or updated

* render - Renders a component. The only required method.
* getInitialState - You can set default values for state
* getDefaultProps - Set defaults for properties
* componentWillMount - Invoked once on client & server before render
* componentDidMount - After first render

## React Addons

* Collection of moduls that aid in developing React.js applications
* Animation Addons
* 2 Way Data Binding addons - React Link
* Testing Addons
