# User service seed

## Description

This is a user handling service, fully written in Go

The used database engine is postgresql

The libraries used are exclusively gin-gonic and SQLX

## Auth

It uses json web tokens

## Testing

It is end to end tested, you can lauch them with a local or distant database:

source .env-test; go test ./tests
