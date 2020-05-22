# Pure Function

## About

We will learn how to test this pure function.

```js
function isPasswordAllowed(password) {
  return (
    password.length > 16 &&
    // non-alphanumeric
    /\W/.test(password) &&
    // digit
    /\d/.test(password) &&
    // capital letter
    /[A-Z]/.test(password) &&
    // lowercase letter
    /[a-z]/.test(password)
  )
}
```

## Getting Started

- Go to `src/utils/__test__/auth.exercise.js`

```
npm run test:exercise:watch
```

if you want to play with the answer:

```
npm run test:answer:watch
```
