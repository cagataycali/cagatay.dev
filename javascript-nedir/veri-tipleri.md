---
description: JavaScript dilinde bulunan veri tiplerini ve kullanımlarını göreceğiz.
---

# Veri Tipleri 🥚

Her programlama dilinde olduğu gibi JavaScript dilinde de yerleşik veri tipleri vardır, ancak bunlar bir dilden diğerine göre farklılık gösterebilir. 

![Hadi bu veri tiplerini beraber &#xF6;&#x11F;renelim.](../.gitbook/assets/201510_1957_aecci_sm.jpg)

JavaScript dilinde  Primitive \( ilkel \) ve Object - Referance \( Nesne - Referans \) 2 ana veri türüdür.

### Primitive \( İlkel \) Veri Tipleri 

JavaScript' te, ilkel veri türü nesne değildir ve kendine ait hiçbir method' u yoktur.  

#### Numbers \( Sayılar \)

```text
let n = 175
n = 17.535
```

Sayı tipi integer ve float point sayılarını temsil eder.

{% tabs %}
{% tab title="Çarpma" %}
```text
var a = 17;
var b = 5;

var total = a * b;

console.log(total);
console.log(typeof total);
```
{% endtab %}

{% tab title="Bölme" %}
```text
var a = 255;
var b = 14;

var total = a / b;

console.log(total);
console.log(typeof total);
```
{% endtab %}

{% tab title="Toplama" %}
```text
var a = -28;
var b = 84;

var total = a + b;

console.log(total);
console.log(typeof total);
```
{% endtab %}

{% tab title="Çıkarma" %}
```text
var a = 175;
var b = 53;

var total = a - b;

console.log(total);
console.log(typeof total);
```
{% endtab %}
{% endtabs %}

Değişkenlere tanımlanan sayısal verileri doğrudan kullanarak matematiksel işlemleri `*`  , `/`  , `+`  , `-`  yapabiliriz.



{% embed url="https://codepen.io/busradanisman/pen/axMGXR" %}







JavaScript değişkenleri birçok veri türünü tutabilir:

* Number \( Sayı \)
* String \( Katar - Karakter Dizesi \)
* Undefined \( Tanımsız \)
* Null \( Değer Yok \)
* Boolean \( Mantıksal Veri Tipleri \)
* Symbol \( ECMAScript 6 \) ve daha fazlası...









