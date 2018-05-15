It's completly based on your requirement.

## call - apply

Both `call` and `apply` execute the function with the given context `this` and parametter.

`call`- When you know the exact parametter, it's better to use `call` because we need to pass the parameter directly.

`apply`- Parametters will be passed as array, on the execution it will passeed according to the order.


## bind 
`bind` return a function reference, which context will be set as given object.

{% gist 368269810861f7ebc153614e9b939ed3 %}

