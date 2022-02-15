# DEMO Open Flights Reviews (Rails + React)

## Project Initialization

```bash
rails new demo_open_flights --webpack-react --database=postgresql
```

## Command history

```bash
rails g model Airline name image_url slug
rails g model Review title description:text score:integer airline:belongs_to
rails g serializer Airline name image_url slug
rails g serializer Review title description score airline_id
rails g controller Pages
yarn add react-router-dom@5.2.0
```

## Postman doc

[https://documenter.getpostman.com/view/8596816/UVkgwdyw](https://documenter.getpostman.com/view/8596816/UVkgwdyw)

## Refference

1. [Let's build a CRUD app with Ruby on Rails and React.js - Part 1](https://youtu.be/oyjzi837wME)
1. [Let's build a CRUD app with Ruby on Rails and React.js - Part 2](https://www.youtube.com/watch?v=F0xErjOtJAQ)
