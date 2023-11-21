# useForm hook

Ejemplo de uso:
```
    const initialForm = {
        name: '',
        age: 22,
        email: 'fulanitodearmas@gmail.com'
    };

    const [ formValues, handleImputChange, reset ] = useForm( initialForm );

```