
# TODO:

GET /api/v1/categories/:id ->
GET /api/v1/categories -> all categories


# TODO 1:

## Feature 1:

Currently getAllCategories API return us an array with objects. 
Try to convert the response from array of objects to array of strings, where each string  is the name of categories

## Feature 2:

Implement Update API for category

PATCH : /api/v1/categories/:id

Req Body
```
{
    name: '',
    description: ''
}
```

Res Body
```
{
    error: '' / {},
    success: true/false,
    data: { return updated category object },
    message: '...'
}
```


# TODO 2:

## Feature 1:
Implement an error handling class for Unauthorised request


# TODO 3:
## Feature

Think about how can we add more filters to the getProducts api, like brand, category etc


# TODO 4:
## Feature

- Create an api that can change the status of an order

- Create an api to fetch order details 

- Few middlewares are pending