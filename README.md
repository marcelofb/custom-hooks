# Custom Hooks

Custom Hooks for use in React

## useFetch

Usage:

```javascript
    const url = 'Url';
    const { data: null, loading: true, error: null } = useFetch(url);
```

## useForm

Usage:

```javascript
    const initialForm = {
        age: 0,
        email: '',
        name: ''
    };
    
    const [ formValues, handleInputChange, reset ] = useForm( initialForm );
```