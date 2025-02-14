# React + Vite
## Component
### Class components
class ClassComponent extends React.Component{
  render(){
    return <h2>Class component</h2>
  }
}

but not recommend
### Functional Component
const Component = () => {
  return <></>
}
export default Component
## Props
Are the way too pass data from one component to another.
Props as arguments you pass to a function.
## States & Hooks
State:
- hold information about the components that can change over time
- when state changes, react automatically re-renders the component to reflect the new data on the screen in this sample.
Hook:
- useState: for managing state
- useEffect: for handling side effects like data fetching, clean up
- useContext: for sharing data across components
- useCallback: for optimizing callback functions
useReducer, useMemo, useTransition, useRef,...

## Introduce Movie app
- a single page application
- search feature







