# emoji
match and replace emoji with anything you specified by javascript

## Support emoji
support all emoji list in [this article](http://www.unicode.org/reports/tr51/index.html#emoji_data), and update aperiodically

## Usage
all you need to do is import `emoji.js` to bind a global Object `Emoji`. 
```javascript
<script src="emoji.js"></script>
<script>
    // handler is a string or function, the same with the second arg of String.prototype.replace
    // as you can see, replace and match is similar to String.prototype.replace and match
    var result = Emoji.replace(yourContent, handler);
    var match = Emoji.match(yourContent);
</script>
```
[live example](http://bigzhan.com/repository/template/366fd70c)

also support CommonJS and AMD.

## Give me some Advices
Match emoji is a samll feature, and I have no idea what you want to do. please tell me if you want more. 
thanks


