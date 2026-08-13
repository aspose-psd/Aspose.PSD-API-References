---
title: "Matrix.Matrix"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Matrix yapıcı. Matrix sınıfının yeni bir örneğini birim matris olarak başlatır."
type: docs
weight: 10
url: /tr/net/aspose.psd/matrix/matrix/
---
{{< psd/tize >}}
## Matrix() {#constructor}

Matrix sınıfının yeni bir örneğini birim matris olarak başlatır.

```csharp
public Matrix()
```

### Ayrıca Bakınız

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

Yeni bir [`Matrix`](../) sınıf örneği başlatır.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| m11 | Single | m00 M11 Ölçek X |
| m12 | Single | m10 M12 Kayma Y |
| m21 | Single | m01 M21 Kayma X |
| m22 | Single | m11 M22 Ölçek Y |
| m31 | Single | m02 M31 Çevir X |
| m32 | Single | m12 M32 Çevir Y |

### Ayrıca Bakınız

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

Belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme sahip olacak şekilde [`Matrix`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | RectangleF | Dönüştürülecek dikdörtgeni temsil eden bir [`RectangleF`](../../rectanglef/) yapısı. |
| plgpts | PointF[] | Dikdörtgenin sol üst, sağ üst ve sol alt köşelerinin dönüştürüleceği bir paralelkenarın noktalarını temsil eden üç adet [`PointF`](../../pointf/) yapısı dizisi. Paralelkenarın sağ alt köşesi ilk üç köşe tarafından ima edilir. |

### Ayrıca Bakınız

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

Belirtilen dikdörtgen ve nokta dizisi tarafından tanımlanan geometrik dönüşüme sahip olacak şekilde [`Matrix`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rect | Rectangle | Dönüştürülecek dikdörtgeni temsil eden bir [`Rectangle`](../../rectangle/) yapısı. |
| plgpts | Point[] | Dikdörtgenin sol üst, sağ üst ve sol alt köşelerinin dönüştürüleceği bir paralelkenarın noktalarını temsil eden üç adet [`Point`](../../point/) yapısı dizisi. Paralelkenarın sağ alt köşesi ilk üç köşe tarafından ima edilir. |

### Ayrıca Bakınız

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

[`Matrix`](../) sınıfının bir kopyasını oluşturur.

```csharp
public Matrix(Matrix origin)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| origin | Matrix | Uyum sağlamak için temel bir matris |

### Ayrıca Bakınız

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


