# DEMO Open Flights Reviews (Rails + React)

## Generate history

```bash
rails g model Airline name image_url slug
rails g model Review title description:text score:integer airline:belongs_to
```

## Refference

1. [Let's build a CRUD app with Ruby on Rails and React.js - Part 1](https://youtu.be/oyjzi837wME)
