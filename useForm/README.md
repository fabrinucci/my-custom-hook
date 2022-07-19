# useForm

Example:
```
const initialForm = {
  name: '',
  age: 0,
  email: ''
};

const [ formState, onInputChange, onResetForm, ] = useForm( initialForm );
```