---
title: "Graphics.DrawLines"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Graphics. Menggambar serangkaian segmen garis yang menghubungkan array struktur Point."
type: docs
weight: 270
url: /id/net/aspose.psd/graphics/drawlines/
---
{{< psd/tize >}}
## DrawLines(Pen, Point[]) {#drawlines_1}

Menggambar serangkaian segmen garis yang menghubungkan array dari struktur [`Point`](../../point/).

```csharp
public void DrawLines(Pen pen, Point[] points)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yang menentukan warna, lebar, dan gaya segmen garis. |
| points | Point[] | Array dari struktur [`Point`](../../point/) yang mewakili titik-titik yang akan dihubungkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* bernilai null. -atau- *points* bernilai null. |
| ArgumentException | Array *points* berisi kurang dari 2 titik. |

### Lihat Juga

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawLines(Pen, PointF[]) {#drawlines}

Menggambar serangkaian segmen garis yang menghubungkan array dari struktur [`PointF`](../../pointf/).

```csharp
public void DrawLines(Pen pen, PointF[] points)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yang menentukan warna, lebar, dan gaya segmen garis. |
| points | PointF[] | Array dari struktur [`PointF`](../../pointf/) yang mewakili titik-titik yang akan dihubungkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* bernilai null. -atau- *points* bernilai null. |
| ArgumentException | Array *points* berisi kurang dari 2 titik. |

### Lihat Juga

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


