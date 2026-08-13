---
title: "Enum HatchStyle"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.HatchStyle enum. HatchBrush nesneleri için mevcut farklı desenleri belirtir."
type: docs
weight: 4840
url: /tr/net/aspose.psd/hatchstyle/
---
{{< psd/tize >}}
## HatchStyle enumeration

[`HatchBrush`](../../aspose.psd.brushes/hatchbrush/) nesneleri için mevcut farklı desenleri belirtir.

```csharp
public enum HatchStyle
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Horizontal | `0` | Yatay çizgilerden oluşan bir desen. |
| Min | `0` | Horizontal tarama stilini belirtir. |
| Vertical | `1` | Dikey çizgilerden oluşan bir desen. |
| ForwardDiagonal | `2` | Üst sol köşeden alt sağ köşeye çapraz bir çizgi desenidir. |
| BackwardDiagonal | `3` | Üst sağ köşeden alt sol köşeye çapraz bir çizgi desenidir. |
| Cross | `4` | Kesişen yatay ve dikey çizgileri belirtir. |
| LargeGrid | `4` | Cross tarama stilini belirtir. |
| Max | `4` | SolidDiamond tarama stilini belirtir. |
| DiagonalCross | `5` | Kesişen çapraz çizgilerden oluşan bir desen. |
| Percent05 | `6` | %5'lik bir tarama belirtir. Ön plan renginin arka plan rengine oranı 5:95'tir. |
| Percent10 | `7` | %10'luk bir tarama belirtir. Ön plan renginin arka plan rengine oranı 10:90'dır. |
| Percent20 | `8` | %20'lik bir tarama belirtir. Ön plan renginin arka plan rengine oranı 20:80'dir. |
| Percent25 | `9` | %25'lik bir tarama belirtir. Ön plan renginin arka plan rengine oranı 25:75'tir. |
| Percent30 | `10` | %30'luk bir tarama belirtir. Ön plan renginin arka plan rengine oranı 30:70'tir. |
| Percent40 | `11` | %40'lık bir tarama belirtir. Ön plan renginin arka plan rengine oranı 40:60'tır. |
| Percent50 | `12` | %50'lik bir tarama belirtir. Ön plan renginin arka plan rengine oranı 50:50'dir. |
| Percent60 | `13` | %60'lık bir tarama belirtir. Ön plan renginin arka plan rengine oranı 60:40'tır. |
| Percent70 | `14` | Yüzde 70'lik bir tarama belirtir. Ön plan rengi ile arka plan rengi arasındaki oran 70:30'dur. |
| Percent75 | `15` | Yüzde 75'lik bir tarama belirtir. Ön plan rengi ile arka plan rengi arasındaki oran 75:25'dur. |
| Percent80 | `16` | Yüzde 80'lik bir tarama belirtir. Ön plan rengi ile arka plan rengi arasındaki oran 80:100'dür. |
| Percent90 | `17` | Yüzde 90'lik bir tarama belirtir. Ön plan rengi ile arka plan rengi arasındaki oran 90:10'dur. |
| LightDownwardDiagonal | `18` | Sağ tarafa doğru eğimli, üst noktadan alt noktaya giden diyagonal çizgileri belirtir ve ForwardDiagonal'dan %50 daha yakın aralıklıdır, ancak antialias uygulanmaz. |
| LightUpwardDiagonal | `19` | Sol tarafa doğru eğimli, üst noktadan alt noktaya giden diyagonal çizgileri belirtir ve BackwardDiagonal'dan %50 daha yakın aralıklıdır, ancak antialias uygulanmaz. |
| DarkDownwardDiagonal | `20` | Sağ tarafa doğru eğimli, üst noktadan alt noktaya giden diyagonal çizgileri belirtir, ForwardDiagonal'dan %50 daha yakın aralıklıdır ve genişliği iki katıdır. Bu tarama deseni antialias uygulanmaz. |
| DarkUpwardDiagonal | `21` | Sol tarafa doğru eğimli, üst noktadan alt noktaya giden diyagonal çizgileri belirtir, BackwardDiagonal'dan %50 daha yakın aralıklıdır ve genişliği iki katıdır, ancak çizgiler antialias uygulanmaz. |
| WideDownwardDiagonal | `22` | Sağ tarafa doğru eğimli, üst noktadan alt noktaya giden diyagonal çizgileri belirtir, ForwardDiagonal tarama stilinin aynı aralığına sahiptir ve genişliği üç katıdır, ancak antialias uygulanmaz. |
| WideUpwardDiagonal | `23` | Sol tarafa doğru eğimli, üst noktadan alt noktaya giden diyagonal çizgileri belirtir, BackwardDiagonal tarama stilinin aynı aralığına sahiptir ve genişliği üç katıdır, ancak antialias uygulanmaz. |
| LightVertical | `24` | Dikey çizgileri belirtir ve Vertical'dan %50 daha yakın aralıklıdır. |
| LightHorizontal | `25` | Yatay çizgileri belirtir ve Horizontal'dan %50 daha yakın aralıklıdır. |
| NarrowVertical | `26` | Dikey çizgileri belirtir ve Vertical tarama stilinden %75 daha yakın aralıklıdır (veya LightVertical'dan %25 daha yakın). |
| NarrowHorizontal | `27` | Yatay çizgileri belirtir ve Horizontal tarama stilinden %75 daha yakın aralıklıdır (veya LightHorizontal'dan %25 daha yakın). |
| DarkVertical | `28` | Dikey çizgileri belirtir, Vertical'dan %50 daha yakın aralıklıdır ve genişliği iki katıdır. |
| DarkHorizontal | `29` | Yatay çizgileri belirtir, Horizontal'dan %50 daha yakın aralıklıdır ve genişliği iki katıdır. |
| DashedDownwardDiagonal | `30` | Sağ tarafa doğru eğimli, üst noktadan alt noktaya giden kesikli diyagonal çizgileri belirtir. |
| DashedUpwardDiagonal | `31` | Sol tarafa doğru eğimli, üst noktadan alt noktaya giden kesikli diyagonal çizgileri belirtir. |
| DashedHorizontal | `32` | Kesikli yatay çizgileri belirtir. |
| DashedVertical | `33` | Kesikli dikey çizgileri belirtir. |
| SmallConfetti | `34` | Konfeti görünümüne sahip bir tarama belirtir. |
| LargeConfetti | `35` | Konfeti görünümüne sahip bir tarama belirtir ve SmallConfetti'den daha büyük parçalardan oluşur. |
| ZigZag | `36` | Zikzaklardan oluşan yatay çizgileri belirtir. |
| Wave | `37` | Tilde karakterlerinden oluşan yatay çizgileri belirtir. |
| DiagonalBrick | `38` | Üst noktadan alt noktaya doğru sola eğimli, katmanlı tuğla görünümüne sahip bir tarama belirtir. |
| HorizontalBrick | `39` | Yatay katmanlı tuğla görünümüne sahip bir tarama belirler. |
| Weave | `40` | Dokuma malzeme görünümüne sahip bir tarama belirler. |
| Plaid | `41` | Kareli malzeme görünümüne sahip bir tarama belirler. |
| Divot | `42` | Çöküntü görünümüne sahip bir tarama belirler. |
| DottedGrid | `43` | Kesişen, noktalardan oluşan yatay ve dikey çizgileri belirler. |
| DottedDiamond | `44` | Kesişen, noktalardan oluşan ileri diyagonal ve geri diyagonal çizgileri belirler. |
| Shingle | `45` | Üst noktadan alt noktaya doğru sağa eğimli, diyagonal katmanlı kiremit görünümüne sahip bir tarama belirler. |
| Trellis | `46` | Kafes görünümüne sahip bir tarama belirler. |
| Sphere | `47` | Yan yana yerleştirilmiş küreler görünümüne sahip bir tarama belirler. |
| SmallGrid | `48` | Kesişen yatay ve dikey çizgileri belirler; bu çizgiler, Cross tarama stiline göre %50 daha yakındır. |
| SmallCheckerBoard | `49` | Satranç tahtası görünümüne sahip bir tarama belirler. |
| LargeCheckerBoard | `50` | Kareleri SmallCheckerBoard'dan iki kat büyük olan satranç tahtası görünümüne sahip bir tarama belirler. |
| OutlinedDiamond | `51` | Kesişen, ancak kenar yumuşatması uygulanmamış ileri ve geri diyagonal çizgileri belirler. |
| SolidDiamond | `52` | Diyagonal olarak yerleştirilmiş satranç tahtası görünümüne sahip bir tarama belirler. |

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


