---
description: >-
  Değişkenler veri saklamak içindir. Bu bölümde JavaScript dilindeki değişken
  kullanımlarını göreceğiz.
---

# Değişkenler 🐣

```javascript
var age = 18
var name = "Büşra"
var gpa = 3.4
var skills = ["Diving", "Wind Surf"]
var person = {
  name: "Büşra",
  age: 18
}
var country = null
var city = undefined
var married = true
```

JavaScript type safe\* bir dil değildir, değişkenler istenilen tipte yazılıp direkt kullanılabilir. Yukarıdaki örnekte 

`age` değişkeni `integer` bir değer taşırken, 

`name` değişkeni bir `string` , 

`gpa` değişkeni bir `float`, 

`skills` değişkeni ise bir `array` taşıyor,

`person` değişkeni bir `object`, 

`country` değişkeni bir `null` yani boş değerdir,

`city` değişkeni bir `undefined` yani değişken tanımlanmış ama herhangi bir değer atanmamıştır,

`married` değişkeni bir `boolean` türünde değişkendir.

## Yeni Değişken Tanımlamaları

JavaScript'de `var` eski bir değişken tanımlama stilidir, EcmaScript6 ile hayatımıza `let` ve `const` kavramları girdi. Aşağıdaki makaleden detaylı bilgiye ulaşabilirsiniz, ileri bölümlerde EcmaScript için ayrı bir bölüm olacak.

{% embed url="https://cagatay.me/ecmascript6-nedir-nas%C4%B1l-kullan%C4%B1l%C4%B1r-neden-kullanmal%C4%B1y%C4%B1z-3-a1d092b7d261" %}

{% embed url="https://medium.com/@busramemis/js-var-const-ve-let-ce26bc9818f7" %}



