---
title: Class Matrix
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.Matrix sınıf. GDI Matrisinin yerini alır.
type: docs
weight: 5090
url: /tr/net/aspose.psd/matrix/
---
## Matrix class

GDI+ Matrisinin yerini alır.

```csharp
public class Matrix
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [Matrix](matrix/#constructor)() | Matrix sınıfının yeni bir örneğini kimlik matrisi olarak başlatır. |
| [Matrix](matrix/#constructor_1)(Matrix) | Şunun bir kopyasını oluşturur:`Matrix` sınıf. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Yeni bir örneğini başlatır.`Matrix` belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme sınıf. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Yeni bir örneğini başlatır.`Matrix` belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme sınıf. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Yeni bir örneğini başlatır.`Matrix` sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Bunun öğelerini temsil eden bir kayan noktalı değerler dizisi alır.`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | İlk satırın ilk sütunundaki matris öğesini alır. X ekseni boyunca ölçeği temsil eder. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Birinci satır ikinci sütundaki matris öğesini alır. Y ekseni boyunca kaymayı temsil eder. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | İkinci satır birinci sütundaki matris elemanını alır. X ekseni boyunca kaymayı temsil eder. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | İkinci satır ikinci sütundaki matris elemanını alır. Y ekseni boyunca ölçeği temsil eder. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Üçüncü satır birinci sütundaki matris elemanını alır. X ekseni boyunca ötelemeyi temsil eder. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Üçüncü satır birinci sütundaki matris elemanını alır. Y ekseni boyunca ötelemeyi temsil eder. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Belirtilenin olup olmadığını belirler.Object bu örneğe eşittir. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Matris elemanlarının kopyasını alır. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Bu örnek için bir karma kod döndürür. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Bu Matrisi (varsayılan) Başa Ekle sırasını kullanarak matrix parametresinde belirtilen matrisle çarpar. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Bu Matrisi, matrix parametresinde belirtilen matrisle ve order parametresinde belirtilen sırayla çarpar. |
| [Reset](../../aspose.psd/matrix/reset/)() | Bu Matrisi, birim matrisin öğelerine sahip olacak şekilde sıfırlar. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Bu Matris için başlangıç noktası (sıfır x ve y koordinatları) etrafında, varsayılan (Başa eklenen) sırada, açı parametresinde belirtilen miktarda saat yönünde döndürme uygular. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Belirtilen sırada bu Matris için başlangıç noktası (sıfır x ve y koordinatları) etrafında açı parametresinde belirtilen miktarda saat yönünde döndürme uygular. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Bu Matrise, varsayılan (Başa Ekleme) sırayla, belirtilen nokta etrafında saat yönünde bir dönüş uygular. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Belirtilen sırada bu Matrise belirtilen nokta etrafında saat yönünde dönüş uygular. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Belirtilen ölçek vektörünü (scaleX ve scaleY) (varsayılan) Başa Ekle sırasını kullanarak bu Matrise uygular. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Belirtilen ölçek vektörünü (scaleX ve scaleY) buna uygular`Matrix` belirtilen order. kullanılarak |
| override [ToString](../../aspose.psd/matrix/tostring/)() | a döndürürString bu örneği temsil eder. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Bununla temsil edilen geometrik dönüşümü uygular`Matrix` belirli bir nokta dizisine. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Belirtilen çeviri vektörünü buna uygular`Matrix` (varsayılan) Başa Ekle sırası kullanılarak. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Belirtilen sırayla bu Matrise belirtilen öteleme vektörünü uygular. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | İki matrisin eşit olup olmadığını belirler. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Bu bayrak biti, bu object tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüştürmelere ek olarak, normalde sağ elli koordinat sistemini bir sol elli sistemine değiştiren bir eksen etrafında bir ayna görüntüsü çevirmesi gerçekleştirdiğini belirtir. Sağ elli bir koordinat sistemi pozitif X ekseninin pozitif Y ekseninin üzerine bindirmek için saat yönünün tersine döndüğü yerdir sağ elinizdeki parmakların başparmağınıza baktığınızda kıvrıldığı yöne benzer . pozitif Y eksenini sol elinizdeki parmakların kıvrıldığı yöne benzer kaplamak için saat yönünde çevirin. orijinal döndürme veya yansıtma dönüşümünün açısını belirlemenin matematiksel bir yolu yoktur, çünkü döndürmenin tüm açıları uygun bir ayarlama dönüşü verildiğinde aynıdır. NOT: GENERAL_TRANSFORM'dan sonra TypeFlip eklendi public dolaşımındaydı ve işaret bitleri, outer code. 'de ikili uyumsuzluk getirmeden artık rahatça yeniden numaralandırılamıyordu. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Bu bayrak biti, bu object tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlerine ek olarak isteğe bağlı bir açıyla döndürme gerçekleştirdiğini gösterir. Bir döndürme, vektörlerin açılarını, vektörün orijinal yönünden bağımsız olarak aynı miktarda değiştirir ve vektörün uzunluğunu değiştirmeden . Bu bayrak biti, the ile birbirini dışlar |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Genel bir ölçek, dikey vektörler arasındaki açıyı değiştirmeden, vektörlerin uzunluğunu x ve y yönlerinde farklı miktarlarıyla çarpar. Bu bayrak biti, TypeUniformScale bayrağıyla birbirini dışlar. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Bu sabit, bu object tarafından tanımlanan dönüşümün giriş koordinatlarında keyfi bir dönüşüm gerçekleştirdiğini gösterir. Bu dönüşüm yukarıdaki sabitlerden herhangi biri tarafından sınıflandırılabilirse, tür ya sabit TypeIdentity ya da uygun işaretin a kombinasyonu olacaktır. bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri için bit. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Bir kimlik dönüşümü, çıkış koordinatlarının her zaman giriş koordinatlarıyla aynı olduğu bir dönüşümdür. Bu dönüşüm, kimlik dönüşümünden başka bir şeyse, türü ya sabit GENERAL_TRANSFORM ya da a için uygun işaret bitlerinin kombinasyonu olacaktır. bu dönüşümün gerçekleştirdiği çeşitli koordinat dönüşümleri. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Bu sabit, döndürme bayrağı bitlerinden herhangi biri için bir bit maskesidir. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Bu sabit, ölçek bayrak bitlerinden herhangi biri için bir bit maskesidir. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Bu bayrak biti, bu object tarafından tanımlanan dönüşümün, diğer bayrak bitleri tarafından belirtilen dönüşümlere ek olarak, 90 derecenin katları olan bir çeyrek daire dönüşü gerçekleştirdiğini gösterir. Bir döndürme, vektörlerin açılarını, orijinal yöne bakılmaksızın aynı miktarda değiştirir ve vektörün uzunluğunu değiştirmeden olmadan. Bu bayrak biti, TypeGeneralRotation bayrağıyla birbirini dışlar. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Çeviri, vektörlerin uzunluğunu veya açısını değiştirmeden koordinatları x ve y'de sabit bir miktarda hareket ettirir. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Düzgün bir ölçek, vektörlerin uzunluğunu, x ve y yönlerinde aynı miktarda ile, arasındaki açıyı değiştirmeden çarpar vektörler. Bu bayrak biti, TypeGeneralScale bayrağıyla birbirini dışlar. |

### Notlar

Algoritmaların çoğu Sun'ın AffineTransform.java'sından alınmıştır. Dahili olarak kullanılan matris öğeleri için Java'nın adları. Java adlarının .net'e haritası, açıklamaya: m00 M11 Ölçek X m10 M12 Kesme Y m01 M21 Kesme X m11 M22 Ölçekli Y_x020 Çevir X m12 M32 Çevir Y

### Ayrıca bakınız

* ad alanı [Aspose.PSD](../../aspose.psd/)
* toplantı [Aspose.PSD](../../)


