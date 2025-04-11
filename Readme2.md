// Notes of Context API

/* useContext()= React Hook that allows u to share values
between multiple levels of components without passing props thorugh each level

// PROVIDER COMPONENT
1. import {createContext} from react
2. export const MyContext (any var name)= createContext() - a fun that creates context
3. <MyContext.Provider value={value}>
    <Child />
    </ MyContext.Provider >


// CONSUMER COMPONENT
1. import React, {useContext} from react
   import {MyContext} from "./ComponentA" - location where provider component is created
2. const value= useContext(MyContext)
