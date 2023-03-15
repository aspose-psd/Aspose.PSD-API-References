---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD for .NET API Referansı
description: Cache mülk. Yeniden tahsisin kesin olup olmayacağını belirten bir değer alır veya ayarlar. Yeniden tahsis kesin değilse performans daha yüksek olmalıdır.
type: docs
weight: 50
url: /tr/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

Yeniden tahsisin kesin olup olmayacağını belirten bir değer alır veya ayarlar. Yeniden tahsis kesin değilse performans daha yüksek olmalıdır.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Mülk değeri

`doğru` yeniden tahsis kesin ise; aksi takdirde,`YANLIŞ` .

### Notlar

Kesin yeniden tahsis, yalnızca belirtilen üst sınıra kadar ek belleğin yeniden tahsisini gerçekleştirecektir. Yeniden tahsis sırasında bellek içi için üst sınır aşılırken, önbelleğe alınan veriler mümkünse diske kopyalanacaktır. Yeniden tahsis sırasında disk belleği için üst sınır geçildiğinde, uygun istisna atılır. Mümkünse ek kopyalama yapılmayacağından bu seçenek kapatılırsa performans daha yüksek olmalıdır, ancak bu, bellek veya disk için belirtilen üst limitlerin de aşılmasına neden olabilir.

### Ayrıca bakınız

* class [Cache](../)
* ad alanı [Aspose.PSD](../../cache/)
* toplantı [Aspose.PSD](../../../)


