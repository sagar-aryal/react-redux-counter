# REDUX TERMINOLOGIES

## REDUX
It is a state management tool with a single store.

## ACTIONS
Actions are a plain JavaScript object that contains information.They are the only source of information for the store.There are two actions within a action, action type and action creator.Action type lists all the action creators together and action creater are the function that creates action type. Action creater have two field properties, type and payload.Type field is a unique identifier that tells what kind of action to perform and all payload is the one that contains all information or data that are required.


## REDUCERS
It is a pure function that takes the previous state and action to returns the newly updated state.It decides our updated state based on the action received.

## STORE
It is an object which holds all the state of the application together.
       
 ---

### dispatch
It is used to send actions to update the data

### Middleware
Redux itself is synchronous, so middleware comes here to perfome the async operations. Its required to handle all the extra jobs before actions get dispatch to reducers.
For example: logging crash reports, send API requests etc

