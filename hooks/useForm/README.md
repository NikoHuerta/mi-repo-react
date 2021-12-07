# useForm Hook

Ejemplo de uso:
```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };
    
    const [formValues, handleInputChange, reset] = useForm(initialForm);
    const { value1, value2, ..etc } = formValues;
```
