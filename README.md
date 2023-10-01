# ER_project
hospital websocket


### Edit and Add seed user
```js
* In project
- prisma/init-user.seed.ts

* Example
[
    ...,
    {
        email: 'acme@abc.com',
        password: '12345678',
        name: 'Test User'
    },
    ....
]
```


### Initail user to DB
```bash
yarn prebuild

yarn seed
```


### Run Project
```bash
* Client
    - yarn dev

* Hook server
    - yarn dev:wss

```
