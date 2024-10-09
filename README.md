# Secure the Vault

## psuedocode steps

- in index.html, link the script file to the page via the HTML code below

```html
  <script src="index.js"></script>
```
- in the index.js page, set a constant for the first alert message

```javascript
const firstMsg = `You have received this message because you have been chosen to open an important vault.`
```

- display the alert message
```javascript
alert(firstMsg)
```
- define the elements of the second alert message

```javascript
const secondMsg = "Here is the secret combination:"
```

- set the variables for each of the the equations that equal the correct number combination

```javascript
const num1 = 2*5
const num2 = 80/2
const num3 = 40-1
```
 
- combine the variables to build the intended message output
```javascript
const fullMsg = `${secondMsg} ${num1} - ${num2} - ${num3}`
```

- execute the second alert
```javascript
alert(fullMsg)
```