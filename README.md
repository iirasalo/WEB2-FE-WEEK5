# Readme

## Task 1

Inside the `server` directory

1. create a file `.env` and add the following content:

```text
MONGODB_URI=mongodb+srv://tivi:SqZsopHbsRtRDO24@cluster0.1x4ks.mongodb.net/groupnr?retryWrites=true&w=majority
PORT=4000
SECRET=mysecretepassword
```

> In `MONGODB_URI`, replace `groupnr` to reflect your group e.g `group1` , `group2` etc

2. Run:

```sh
npm install
npm run dev
```

3. Test the endpoints with postman
   > More instructions in class

## Task 2

1. The code for `signup.html` is provided for you.
   Test that you can register a new user
2. Implement the necessary logic to have a working logout service.
3. Implement the necessary logic to have a working frontend.
