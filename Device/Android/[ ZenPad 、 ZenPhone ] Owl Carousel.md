# Owl Carousel 殘影問題
在特定 ZenXXX 機型在 [Owl Carousel](http://owlgraphic.com/owlcarousel) (2.1.4) 會出現滑動後疊加殘影問題

## Device
`ZenPad 7` 、 `Zenfone Selife` ，其他 ZenXXX 機型部份出現

## Browser
`Chrome`

## 處理方式
開啟 CSS3D 加速
```css
.owl-carousel-item{
  transform: translateZ(0);
}
```
