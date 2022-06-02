## Cloned and Deployed on this repository

### what does this app contains ?

- Security middlewares.
- Authentication with cookies & salt encryption.
- User roles management.
- Database connection.
- API MOCK handle.
- Console runners:
  - to inject users data.
  - backup DB into a Docker container.
  - run queries.
- User images served by AWS S3 bucket.
- Testing Units. (TDD)

### Automatic Continuous Integration CI

https://github.com/ortiztena/heroku-automatic-deploy/runs/6624854056?check_suite_focus=true

## Heroku app URL and login

https://automatic-dpl.herokuapp.com/

1. Login with admin role credentials:
   - username: admin@email.com
   - password: test
2. Login with user role credentials:
   - username: user@email.com
   - password: test

Env variables:

```
API MOCK: False
MONGODB_URI: personal mongodb account.
AWS_BUCKET: personal aws account.
```

#### TO DO:

- Implement a Scene that allow you to save a hotel review(role credentianls) and see the result.
- implement a Scene that shows the hotel collection.
