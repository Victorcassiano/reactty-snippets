# Reactty Snippets

The essential collection of React Snippets and commands.

## Features

These snippets were selected carefully from my own day-to-day React Native use. Not
everything in React is included here. This is a hand selected set of snippets
that work the way that you would expect.

## Snippets

| Snippet    | Renders                                              |
| ---------- | ---------------------------------------------------- |
| `imr`      | Import React                                         |
| `imrn`     | Import React end React Native                        |
| `imrs`     | Import React, { useState }                           |
| `imrse`    | Import React, { useState, useEffect }                |
| `rcp`      | Create page for React                                |
| `cprn`     | Create page for React Native                         |
| `cpr-ex`   | Create page for React with Export Default            |
| `cprn-ex`  | Create page for React Native with Export Default     |
| `cwi`      | Function Component with Interface end Export Default |
| `sheet`    | Create StyleSheet                                    |
| `fc`       | Function Syntax Component                            |
| `fc-async` | Async Function Syntax Component                      |
| `uef`      | useEffect Hook                                       |
| `usf`      | useState Hook                                        |

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

### rcp - Create page

```typescript
import React from "react";

const Page: React.FC = () => {
  return(
    <div>
    </div>
  );
};

export default Page;
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

### usf - useState Hook

```typescript
const [state, setState] = useState();
```
