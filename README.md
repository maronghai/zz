# ZZ

**ZZ** (Chinese word for **Regex** is **正则**, the 'Pin Yin' is `Zheng4 Ze2`, **ZZ** for short, finally **z2**).

## Hello World

```
^       ; Here is start
hello   ; Here is 'hello'
|       ; Here is `or`
world   ; Here is 'world'
$       ; Here is end
```

Result:

```
^hello|world$
```

## Pro

```javascript
/(?: {3,};.*?)?\n/g
```
