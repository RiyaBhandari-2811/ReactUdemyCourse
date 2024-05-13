1. Whenever you are using or reusing a component, react will basically create a new isolated instance.
2. Updating state based on old state:
   setIsEditing(prev => !prev);
   This Function will automatically be called by react and will receive the guaranteed latest state value
3. Two Way Binding: coz using onChange we are getting the value out from this input and using value attribute we are feeding a value back into this input ` <input type="text" required value={playerName} onChange={handleNameChange}/>`
4. Update object-state immutably: Objects & array (which technically are objects) are reference values in JS. You should not mutate them directly instead create a (deep) copy first!

### Lifting State Up

Lift the state up to the closest ancestor component that has access to all components that need to work with that state.
