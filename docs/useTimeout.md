# `useTimeout`

Returns `true` after a specified number of milliseconds.

## 用法

```jsx
import { useTimeout } from 'react-use';

const Demo = () => {
  const ready = useTimeout(2000);

  return <div>Ready: {ready ? 'Yes' : 'No'}</div>;
};
```
