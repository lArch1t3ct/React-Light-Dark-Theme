# Light / Dark Theme

This project is part of learning the Context API offered by React.JS while I am attending the Advanced React course by Meta on Coursera.

# ThemeContext Component
1. First, the ThemeContext object was created by calling the createContext function and passing as its argument `undefined`.
2. Then, a provider component needs to be created, `ThemeProvider` which returns the `ThemeContext.Provider` component.
3. The `ThemeContext.Provider` components accepts a `value` prop, which data is going to be passed to the consuming component.
   - Thus, the data should be the state variable and the setState function.
   - In particular, a `toggleFunction` will be used which calls the `setTheme` function to change the state of the component.
4. Finally, a mean for components to subscribe to the context should be provided, `useTheme`

Having the `ThemeContext` being set up and a mean for components to subscribe to the context, the `useTheme` can be used when needed.