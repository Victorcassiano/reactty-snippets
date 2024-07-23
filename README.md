# Reactty Snippets

The essential collection of React Snippets and commands.

## Features

These snippets were selected carefully from my own day-to-day React Native use. Not
everything in React is included here. This is a hand selected set of snippets
that work the way that you would expect.

## Snippets

| Snippet         | Renders                                              |
| --------------- | ---------------------------------------------------- |
| `imrn`          | Import React end React Native                        |
| `imrs`          | Import React, { useState }                           |
| `imrse`         | Import React, { useState, useEffect }                |
| `rcp`           | Create page for React                                |
| `cprn`          | Create page for React Native                         |
| `cpr-ex`        | Create page for React with Export Default            |
| `cprn-ex`       | Create page for React Native with Export Default     |
| `cwi`           | Function Component with Interface end Export Default |
| `fc`            | Function Syntax Component                            |
| `fc-async`      | Async Function Syntax Component                      |
| `uef`           | useEffect Hook                                       |
| `usf`           | useState Hook                                        |
| `arrowfc`       | Create Arrow function                                |
| `arrowfc-async` | Create async arrow function                          |
| `parrow-ex`     | Create Page with arrow function                      |

## Full Expansions

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

### rcp - Create page

```typescript
import React from "react";

const Page: React.FC = () => {
  return <div></div>;
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
