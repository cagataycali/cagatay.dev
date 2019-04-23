---
description: >-
  JavaScript dilinde yorum satırları nasıl kullanılır bu bölümde onu
  öğreneceğiz.
---

# Yorum Satırları 🐥

## Tek Satırlık Yorumlar

Tek satırlık yorumlar için `//` operatörünü kullanıyoruz.

```javascript
// Fibonacci serisini hesaplayan metod.
function fibonacci(num){
  var a = 1, b = 0, temp;

  while (num >= 0) {
    // Swap işlemi yapalım.
    temp = a;
    a = a + b;
    b = temp;
    num--;
  }

  return b;
}
```

{% hint style="info" %}
 Eğer kod blogunun arasında yorum yazılacaksa, kısa ve öz olmasına dikkat etmeliyiz. Her kod satırına yorum yazmak kodu boğar ve okunabilirliğini düşürür. Yorum satırları algoritmaları açıklarken kullanılırsa daha efektif olacaktır.
{% endhint %}

### Ufak bir örnek;

{% hint style="danger" %}
**YANLIŞ!**
{% endhint %}

```javascript
// Yaş değerini tutmak için bir değişken.
var age = 18
```

{% hint style="success" %}
**DOĞRU!**
{% endhint %}

```javascript
// Fibonacci serisini hesaplayan kendini çağıran metod.
function fibonacci(num) {
  // Eğer num 1'den küçükse 1 dön.
  if (num <= 1) return 1;
  // Bir önceki sayı ile bir sonraki sayının toplamını hesapla.
  return fibonacci(num - 1) + fibonacci(num - 2);
}
```

## Çok Satırlı Yorumlar

JavaScript'de çok satırlı yorum yazılacağı zaman `/*` operatörü ile başlar ve `*/` operatörü ile biter. Yukarıdaki kod blogunu tekrar bu şekilde güncelleyelim;

```javascript
/* 
  Fibonacci serisini hesaplayan kendini çağıran metod.
  Kendini çağıran bir şekilde hazırlanmıştır (recursion)
  Kod hafızadan ödün vererek performans kazanmak amaçlıdır.
*/
function fibonacci(num, memo) {
  memo = memo || {};

  if (memo[num]) return memo[num];
  if (num <= 1) return 1;

  return memo[num] = fibonacci(num - 1, memo) + fibonacci(num - 2, memo);
}
```



