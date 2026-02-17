# REST API & .then() in JavaScript

## REST API
A REST API is an interface that allows your application to **request data or perform actions on a server in an organized way**.

### How it works
REST APIs usually work over **HTTP**, just like any website:

- **GET**: Retrieve data (e.g., get user data)  
- **POST**: Create new data (e.g., add a new user)  
- **PUT/PATCH**: Update existing data  
- **DELETE**: Delete data  

---

## `.then()`
- `.then()` is a method for handling **Promises**.  
- When you perform something **asynchronous** (e.g., fetching data from an API), you don’t know when it will finish. A **Promise** holds the future result.  
- `.then()` specifies **what should happen when the request succeeds**.  