# toolpouchjs
#### A simple set of js helper methods

This is a very simple set of helper methods that I have used on a recent project. The plan is to continue adding to the set.

## Getting Starterd

```
npm install toolpouchjs
```

##### Usage example:
``` javascript
import { bind } from 'toolpouchjs';

class App {
  constructor(config) {
    bind(this, ['render', 'update']);
  }
  
  render() {
    ...
  }
  
  ...
}
```
