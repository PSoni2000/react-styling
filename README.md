# React Styling

React Styling is using a simple 'Course Goal' app to learn different Styling in React.

## Notes

1. Inline Styles have the highest Priority
   `style = {{color: red}}`
2. tagged template literals -
   ```
   const FormControl = styled.div`
   margin: 0.5rem 0;
   `;
   ```
3. CSS Modules -
   - css file should be named as 'Button.module.css'
   - css file should be included as 'import styles from "./Button.module.css";' in jxs file.
   - in css modules all css are component scoped.
