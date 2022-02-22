# update-react-component

Sometimes you need to force re-render on function based component. This is a simple custom hook to do force re-render.

Note: Custom hooks cannot be called inside callbacks.

### Usage

```js
import {useForceUpdate} from 'update-react-component';
```

```js
useForceUpdate()
```