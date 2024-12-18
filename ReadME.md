### 1. How do you create a React App from the terminal command line?

```sh
npm create vite@latest ./
```

### 2. If you clone a React App that has already been created, what command is needed to start developing with its dependencies?

```sh
npm install
```

### 3. How do you start the in-browser development server for a React App?

```sh
npm run dev
```

### 4. What folder in a React App should component files be created in?

```sh
components folder in the root directory
```

### 5. What is the syntax for a function based component?

```sh
const ComponentName = () =>
{
    return(
        <div></div>
    )
}

export default ComponentName
```

### 6. What direction are props passed in a React Component?

```sh
Downward, in the hierarchy
```

### 7. How is a React Component brought in to be accessed in another file?

```sh
By importing it
```

### 8. How do we gain access to props in a child component?

```sh
We pass it as an argument in the child component and use props.WhateverThePropertyNameIs to access the props values.
```