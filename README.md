# cookie-manager-js
Lightweight, simple and easy cookie management library in JavaScript

![Bower](https://img.shields.io/bower/l/MI)  

This is a library for providing more useful and powerful interface to manage your cookies.
- No Dependency
- Supportd AMD, Common JD and Node modules.
- Lightweight
- Supported by all browsers.


## Installation
Download the `cookie-manager.min.js` and include in your project.

```html
<script src="cookie-manager.min.js"></script>
```


## Usage
After including the `cookie-manager.min.js`, you will be able to use `CookieManager` object.

You can also load `CookieManager` object as an AMD, CommonJS or Node module.


## Functionalities

### Creating a Cookie
Creating a new Cookie

```js
  CookieManager.set(name, value, expires, domain, path, secure);
```
- `name (String)` cookie name
- `value (String)` cookie value
- `expires (Optional) (Number)` cookie expiration in days
- `domain (Optional) (String)` cookie domain
- `path (Optional) (String)` cookie path
- `secure (Optional) (Boolean)` cookie ssl support flag
### Retrieving a Cookie
Getting a cookie with given cookie name.

```js
  CookieManager.get(name);
```
- `name (String)` cookie name

### Updating a Cookie

Updating an existing Cookie

```js
  CookieManager.update(name, value, expires, domain, path, secure);
```
- `name (String)` cookie name
- `value (String)` cookie value
- `expires (Optional) (Number)` cookie expiration in days
- `domain (Optional) (String)` cookie domain
- `path (Optional) (String)` cookie path
- `secure (Optional) (Boolean)` cookie ssl support flag

### Deleting a Cookie
Deleting a cookie with given cookie name.

```js
  CookieManager.remove(name);
```
- `name (String)` cookie name


### Listing All Cookies
Returns all of the existing cookies.

```js
  CookieManager.getAll();
```

### Clearing All Cookies
Removes all of the existing cookies.

```js
  CookieManager.clear();
```

## Author and License
Created and maintained by [Shaninath](https://github.com/shaninathpawargit/cookie-manager-js) under [MIT](LICENSE.md) License
 
