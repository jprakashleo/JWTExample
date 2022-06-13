# JWTExample


A JSON web token has mainly has 5 parts.
1st of all need a user to whom you are creating JWT
2nd any Key to crete JWT
3rd any Algorrithm the generate the token
4th is Claims, mean some role, some role for access
5th is life time of token
Then only we can authorize is valid for that role, not expired token, user value is passed, key is predefined in appsetting.

Here I created 2 controller First is Home controller bt default show 401, authorization error.
Then need to call /Genjwt/get {contoller/action} for generate the token value which will be valid for cuttent session.

copy this value and whiout restart app pass this value as authorization header. 
I am using here chrome ext to pass authorization and bearer token.
then home controller will run.
In deep we can check different roles, which i not coverd here
we can use different algorithms, which i not coverd here
