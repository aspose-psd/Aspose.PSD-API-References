---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Cache özelliği. Yeniden tahsislemenin tam olup olmadığını gösteren bir değeri alır veya ayarlar. Yeniden tahsisleme tam değilse performans daha yüksek olmalıdır"
type: docs
weight: 50
url: /tr/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

Yeniden tahsislemenin tam olup olmadığını belirten bir değeri alır veya ayarlar. Yeniden tahsisleme tam değilse performans daha yüksek olmalıdır.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` eğer yeniden tahsisleme tam ise; aksi takdirde, `false`.

## Açıklamalar

Tam yeniden tahsisleme, ek belleğin yeniden tahsislemesini yalnızca belirtilen üst sınıra kadar gerçekleştirir. Yeniden tahsisleme sırasında bellek içi için üst sınır verildiğinde, önbelleğe alınan veri mümkünse diske kopyalanır. Yeniden tahsisleme sırasında disk belleği için üst sınır verildiğinde uygun istisna fırlatılır. Bu seçenek kapatıldığında, mümkün olduğunda ek kopyalama yapılmayacağı için performans daha yüksek olmalıdır; ancak bu, bellek veya disk için belirtilen üst sınırların aşılmasına da yol açabilir.

### Ayrıca Bakınız

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


