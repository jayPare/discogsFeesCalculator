# CountryCodes

A simple Javascript UMD tool for ISO country codes.

##

## Usage

```html
<script
  crossorigin
  src="https://raw.githubusercontent.com/jayPare/CountryCodes/main/countryCodes.js"
></script>
```

### Country name to 2-digits code:

```js
code = countryCodes.countryToCode("Canada"); // code == "CA"
```

### Country name to 3-digits code:

```js
code = countryCodes.countryToCode3("Canada"); // code == "CAN"
```

### 2-digits code to 3-digits code:

```js
code = countryCodes.codeToCode3("CA"); // code == "CAN"
```

### 3-digits code to 2-digits code:

```js
code = countryCodes.codeToCode3("CAN"); // code == "CA"
```

### 2-digits code to country name:

```js
code = countryCodes.codeToCountry("CA"); // code == "Canada"
```

### 3-digits code to country name:

```js
code = countryCodes.code3ToCountry("CAN"); // code == "Canada"
```

## Notes

- Missing countries coming soon.

## License

[MIT](LICENSE.txt) © [JayPare](https://github.com/jayPare)
