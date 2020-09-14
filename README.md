# useCounter Hook

Use example:

```
    const {counter, increment, decrement, reset} = useCounter(10);
```

useCounter() // Receives defult value of 10

# useFETCH

Use example:

```
const url = 'API endpoint';
const { data: null, loading: true, error: null } = useFetch(url);

```

# useForm

Use example:

```
const initialForm = {
    name: "",
    age: 0,
    email: "",
}

const [formValues, handleInputChange, reset] = useForm( initialForm );

```
