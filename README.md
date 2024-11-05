## Express basic Server with typescript 

Hello developers ,hope you all are well.Basically in development sector most irritating thing is setup a server then code . that's I have created a basic server which contains some validations handlers .Errors are the most common things in development . So backend developers need to structure this errors so that client / frontend site can understand easily what's going on . that's why I have created this type of folder structure which will make your development journey smooth . so follow the steps to setup this basic Express server .

### Features used

- Global handlers
  - Cast error handlers (mongoose)
  - validation error handlers (mongoose)
  - zod validation error handlers (zod)

-  Global Interface 
    - generic error interface
    - jwt payload interface

- utils 
    - catchAsync (which resolve try catch promise functions in express)
    - global error (which returns same structured errors to client site )
    - validation middleware (which solves to validate zod schema in body)
  
    ```
    const validate = z.object({
        body : z.object({
            // your code here
        })
    }) 
    ```

### step 1 

```

git clone https://github.com/Shatab99/basic-express-server-ts.git

```

### step 2

```

cd basic-express-server-ts

```

### step 3

```

rmdir /s /q .git

```

### step 4

```

npm i 

```

<div>
<br>
<br>
</div>

<div align="center">
<img src="./assets/Screenshot 2024-11-05 093115.png" alt="Alt text" width="350" height="250">
</div>




