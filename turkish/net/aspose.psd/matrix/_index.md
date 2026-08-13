---
title: "Sınıf Matrix"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.Matrix sınıfı. GDI Matrix yerine geçer"
type: docs
weight: 5610
url: /tr/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

GDI+ Matrisini değiştirir.

```csharp
public class Matrix
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Matrix](matrix/#constructor)() | Matrix sınıfının yeni bir örneğini birim matris olarak başlatır. |
| [Matrix](matrix/#constructor_1)(Matrix) | `Matrix` sınıfının bir kopyasını oluşturur. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre `Matrix` sınıfının yeni bir örneğini başlatır. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Belirtilen dikdörtgen ve nokta dizisiyle tanımlanan geometrik dönüşüme göre `Matrix` sınıfının yeni bir örneğini başlatır. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | `Matrix` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Bu `Matrix`'in öğelerini temsil eden kayan nokta değerlerinden oluşan bir dizi alır. |
| [M11](../../aspose.psd/matrix/m11/) { get; } | İlk satırın ilk sütunundaki matris öğesini alır. X ekseni boyunca ölçeği temsil eder. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | İlk satırın ikinci sütunundaki matris öğesini alır. Y ekseni boyunca kaymayı temsil eder. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | İkinci satırın ilk sütunundaki matris öğesini alır. X ekseni boyunca kaymayı temsil eder. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | İkinci satırın ikinci sütunundaki matris öğesini alır. Y ekseni boyunca ölçeği temsil eder. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Üçüncü satırın ilk sütunundaki matris öğesini alır. X ekseni boyunca çeviriyi temsil eder. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Üçüncü satırın ilk sütunundaki matris öğesini alır. Y ekseni boyunca çeviriyi temsil eder. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Belirtilen Nesnenin bu örnek ile eşit olup olmadığını belirler. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Matris öğelerinin bir kopyasını alır. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Bu örnek için bir hash kodu döndürür. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Bu Matrix'i, matrix parametresinde belirtilen matrisle (varsayılan) Prepend sırasını kullanarak çarpar. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Bu Matrix'i, matrix parametresinde belirtilen matrisle ve order parametresinde belirtilen sırada çarpar. |
| [Reset](../../aspose.psd/matrix/reset/)() | Bu Matrix'i kimlik matrisinin elemanlarına sahip olacak şekilde sıfırlar. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde döndürmeyi, orijinin (sıfır x ve y koordinatları) etrafında, varsayılan (Prepend) sırada uygular. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Bu Matrix için, açı parametresinde belirtilen miktarda saat yönünde döndürmeyi, orijinin (sıfır x ve y koordinatları) etrafında, belirtilen sırada uygular. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Bu Matrix'e, belirtilen nokta etrafında saat yönünde döndürmeyi, varsayılan (Prepend) sırada uygular. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Bu Matrix'e, belirtilen nokta etrafında saat yönünde döndürmeyi, belirtilen sırada uygular. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Bu Matrix'e, belirtilen ölçek vektörünü (scaleX ve scaleY) (varsayılan) Prepend sırasını kullanarak uygular. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Belirtilen ölçek vektörünü (scaleX ve scaleY) bu `Matrix`'e belirtilen sırayı kullanarak uygular. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Bu örneği temsil eden bir String döndürür. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Bu `Matrix` tarafından temsil edilen geometrik dönüşümü belirtilen nokta dizisine uygular. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Belirtilen çeviri vektörünü bu `Matrix`'e (varsayılan) Prepend sırasını kullanarak uygular. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Belirtilen çeviri vektörünü bu Matrix'e belirtilen sırada uygular. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | İki matrisin eşit olup olmadığını belirler. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak, normalde sağ el koordinat sistemini sol el sistemine değiştiren bir eksen etrafında ayna görüntüsü çevirmesi yaptığını gösterir. Sağ el koordinat sistemi, pozitif X ekseninin pozitif Y ekseninin üzerine gelmek için saat yönünün tersine döndüğü, başparmağınıza baktığınızda sağ elinizin parmaklarının kıvrıldığı yönle benzer bir sistemdir. Sol el koordinat sistemi ise pozitif X ekseninin pozitif Y ekseninin üzerine gelmek için saat yönünde döndüğü, sol elinizin parmaklarının kıvrıldığı yönle benzer bir sistemdir. Uygun bir ayarlama dönüşümü verildiğinde tüm çevirme açıları aynı olduğundan, orijinal çevirme veya yansıtma dönüşümünün açısını belirlemenin matematiksel bir yolu yoktur. NOT: TypeFlip, GENERAL_TRANSFORM kamuya açık hale geldikten sonra eklendi ve bayrak bitleri dış kodda ikili uyumsuzluk yaratmadan yeniden numaralandırılamadı. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün, diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak, keyfi bir açıyla döndürme yaptığını gösterir. Bir döndürme, vektörün orijinal yönünden bağımsız olarak vektörlerin açılarını aynı miktarda değiştirir ve vektörün uzunluğunu değiştirmez. Bu bayrak biti, şununla karşılıklı olarak dışlayıcıdır: |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Genel bir ölçek, dik vektörler arasındaki açıyı değiştirmeden, x ve y yönlerinde vektör uzunluklarını farklı miktarlarda çarpar. Bu bayrak biti, TypeUniformScale bayrağıyla karşılıklı olarak dışlayıcıdır. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Bu sabit, bu nesne tarafından tanımlanan dönüşümün girdi koordinatlarının keyfi bir dönüşümünü yaptığını gösterir. Eğer bu dönüşüm yukarıdaki sabitlerden herhangi biriyle sınıflandırılabiliyorsa, tür ya TypeIdentity sabiti ya da bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri için uygun bayrak bitlerinin bir kombinasyonu olacaktır. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Kimlik dönüşümü, çıktı koordinatlarının her zaman giriş koordinatlarıyla aynı olduğu bir dönüşümdür. Bu dönüşüm kimlik dönüşümü dışında bir şey ise, tür ya GENERAL_TRANSFORM sabiti ya da bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri için uygun bayrak bitlerinin bir kombinasyonu olacaktır. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Bu sabit, döndürme bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Bu sabit, ölçek bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Bu bayrak biti, bu nesne tarafından tanımlanan dönüşümün diğer bayrak bitleriyle belirtilen dönüşümlere ek olarak, 90 derecenin bir katı kadar bir çeyrek döndürme yaptığını gösterir. Bir döndürme, vektörün yönünden bağımsız olarak açıları aynı miktarda değiştirir ve vektörün uzunluğunu değiştirmez. Bu bayrak biti, TypeGeneralRotation bayrağıyla karşılıklı olarak birbirini dışlar. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Bir çeviri, koordinatları x ve y yönlerinde sabit bir miktar hareket ettirir ve vektörlerin uzunluğunu ya da açısını değiştirmez. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Tekdüzen bir ölçeklendirme, vektörlerin uzunluğunu x ve y yönlerinde aynı miktarda çarpar ve vektörler arasındaki açıyı değiştirmez. Bu bayrak biti, TypeGeneralScale bayrağıyla karşılıklı olarak birbirini dışlar. |

## Açıklamalar

Çoğu algoritma Sun'un AffineTransform.java dosyasından alınmıştır. Java'nın dahili olarak kullanılan matris elemanları adları. Java adlarından .net adlarına ve açıklamalara harita: m00 M11 Ölçek X m10 M12 Kayma Y m01 M21 Kayma X m11 M22 Ölçek Y m02 M31 Çevirme X m12 M32 Çevirme Y

### Ayrıca Bakınız

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


