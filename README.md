#  🏡 GroupChat
#### GroupChat is an Express-based app that uses websockets for a live, multi-room chat system
>  👩🏻‍💻 practicing websockets and good OO design for more sophisticated applications
* using websockets, users can join chat rooms and live chat
* users can get jokes with `/joke`
* users can get list of members in the chat room with `/members`
* users can send private messages `/priv username message`
--------------------------------------------------------

## technologies:
backend is a restful api, returns JSON data
* backend: Express
    * package: ws-express
* frontend: css, html, javascript

## issues & todos:
### adding tests
* write tests

### future functionality:
* allow users to change names with `/name myNewName`

## setup:
to try out the app:
##### `node server.js`
##### navigate in your browser to `http://localhost:3000/room-name.`


