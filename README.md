# redux-connect-hoc


### mapStateToProps
```js
@mconnect({accountData: 'UserAccount'})
```


### mapDispatchToProps
```
const { login } = actions.UserAccount;

@mconnect(null, {login})
```
