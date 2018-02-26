I wanna import body-parser

then I use it in the router

let app = express\(\);

app.use\(body-parser.json\(\)\);

Then error

I have to use it in the beginning of the app.js

where is the starting point of this whole app.

So there is only one express?

I can not use nestedly calling it??

request.body  needs body-parser

/:userId

route parameter

can be found at req.params.userId



For Mongoose:

model.find\(\) return another what?

if I wanna send the result back

the result is inside find

it's in the callback fun of it

```
    usersModel.find({}, function (err, users){
        if (err) {
            response.status(500).json(err);
        }
        console.log(users);
        response.status(200).json(users);
    });
```

like this, the second parameter of callback fun "users" is the result.



what dose it return?

maybe nothing?

I need to check out the document of Mongoose later





