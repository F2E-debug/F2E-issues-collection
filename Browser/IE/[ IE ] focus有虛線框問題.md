# IE focus有虛線框問題
input:focus會有虛線框

## Browser
`IE`

## 處理方式
針對focus行為的outline下!important
```css
*:focus { outline: 0 !important; }
```