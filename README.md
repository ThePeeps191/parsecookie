# parsecookie

a simple program to find cookie values

# usage

## regular version

```html
<script src="https://raw.githubusercontent.com/ThePeeps191/parsecookie/main/parsecookie.js"></script>
```

## minified

```html
<script src="https://raw.githubusercontent.com/ThePeeps191/parsecookie/main/parsecookie.min.js"></script>
```

# fetching cookie values

```javascript

// document.cookie = "a=b;hi=there;"

console.log(getCookie("a")) // prints "b"

console.log(getCookie("hi")) // prints "there"
```

# see also

[parsequery](https://github.com/ThePeeps191/parsequery)
