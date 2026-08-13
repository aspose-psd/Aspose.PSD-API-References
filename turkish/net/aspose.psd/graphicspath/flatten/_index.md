---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD for .NET API Referansı"
description: "GraphicsPath yöntemi. Bu yoldaki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür"
type: docs
weight: 90
url: /tr/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

Bu yoldaki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür.

```csharp
public void Flatten()
```

### Ayrıca Bakınız

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Belirtilen dönüşümü uygular ve ardından bu [`GraphicsPath`](../) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür.

```csharp
public void Flatten(Matrix matrix)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | Matrix | Bu [`GraphicsPath`](../) düzleştirilmeden önce dönüştürmek için bir [`Matrix`](../../matrix/) |

### Ayrıca Bakınız

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Bu [`GraphicsPath`](../) içindeki her eğriyi birbirine bağlı çizgi segmentlerinden oluşan bir diziye dönüştürür.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix | Matrix | Bu [`GraphicsPath`](../) düzleştirilmeden önce dönüştürmek için bir [`Matrix`](../../matrix/) |
| düzlük | Single | Eğri ile düzleştirilmiş yaklaşımı arasındaki izin verilen maksimum hatayı belirtir. Varsayılan değer 0.25'tir. Düzlük değerini azaltmak, yaklaşımda kullanılan çizgi segmenti sayısını artırır. |

### Ayrıca Bakınız

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


