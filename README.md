# Reactty Snippets

The essential collection of React Snippets and commands.

## Features

Simply, simple React snippets.

These snippets were selected carefully from my own day-to-day React use. Not
everything in React is included here. This is a hand selected set of snippets
that work the way that you would expect, not just a copy of the documentation.

## Snippets

| Snippet | Renders                               |
| ------- | ------------------------------------- |
| `imr`   | Import React                          |
| `imrn`  | Import React end React-Native         |
| `imrs`  | Import React, { useState }            |
| `imrse` | Import React, { useState, useEffect } |
| `fcwi`  | Function Component with Interface     |
| `fc`    | Function Syntax Component             |
| `uef`   | useEffect Hook                        |
| `usf`   | useState Hook                         |

## Full Expansions

### imr - Import React

```typescript
import React from "react";
```

### imrn - Import React end React-Native

```typescript
import React from "react";
import {} from "react-native";
```

### imrs - Import React, { useState }

```typescript
import React, { useState } from "react";
```

### imrse - Import React, { useState, useEffect }

```typescript
import React, { useState, useEffect } from "react";
```

### fcwi - Function Component with Interface

```typescript
export interface ComponentProps {

}

const Component: React.FC<ComponentProps> = () => {
    return (  );
}

export default Component;
```

### fc - Function Syntax Component

```typescript
function nameFunction() {
    return (  );
}

export default nameFunction;
```

### uef - useEffect Hook

```typescript
useEffect(() => {}, []);
```

### `usf` - useState Hook

```typescript
const [state, setState] = useState();
```
