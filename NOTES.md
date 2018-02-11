#Reducers and Actions notes

Redux manages state as a single javascript object.

Component state is seperate from application state.

Application state is formed by reducers which use actions to change state over time.

Actions are common javascript objects with a key of type and a key of payload.

* User Clicks
* Onclick calls an action creator
* Action sent to all reducers
* Reducers returned state based on type of action
* State injected into containers and view is rerendered