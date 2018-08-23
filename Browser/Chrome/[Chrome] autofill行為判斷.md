# Chrome autofill判斷
autofill

## Browser
`Chrome`

## 處理方式
針對Chrome autofill行為做判斷
```js
setTimeout(function() {
    $('input').each(function() {
        var inputAutofill = $(this).is("*:-webkit-autofill") ? true : false;
        if(inputAutofill) {
            //行為
        }
    });
}, 100)
```
