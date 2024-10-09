# Secure the Vault

## psuedocode steps

- in index.html, link the script file to the page via the HTML code below

```html
  <script src="index.js"></script>
```
- in the index.js page, first alert the user they're receiving this message because they've been choosen to open an important vault

```javascript
alert(`You have received this message because you have been chosen to open an important vault.`)
```

- next, set constant declaration for each of the the 3 combination numbers, including the mathematic 

const num = 40
const num1 = 2*5
const num2 = 80/2
const num3 = 40-1

alert(`Here is the secret combination: ` + num/4 + " - " + num + " - " + num-1 )