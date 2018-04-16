# ChatRoom
Creating a chat room with Python and TKinter

- check to see what's running on port 33000
`netstat -vanp tcp | grep 33000`

- stops program from accessing port 330000
`lsof -t -i tcp:33000 | xargs kill`