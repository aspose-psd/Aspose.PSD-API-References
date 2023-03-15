---
title: Graphics.DrawBezier
second_title: Aspose.PSD untuk Referensi .NET API
description: Graphics metode. Menggambar spline Bézier yang ditentukan oleh empat pasang koordinat berurutan yang mewakili titik.
type: docs
weight: 170
url: /id/net/aspose.psd/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Menggambar spline Bézier yang ditentukan oleh empat pasang koordinat berurutan yang mewakili titik.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yang menentukan warna, lebar, dan gaya kurva. |
| x1 | Single | Koordinat x dari titik awal kurva. |
| y1 | Single | Koordinat y dari titik awal kurva. |
| x2 | Single | Koordinat x titik kontrol pertama kurva. |
| y2 | Single | Koordinat y dari titik kontrol pertama kurva. |
| x3 | Single | Koordinat x dari titik kontrol kedua kurva. |
| y3 | Single | Koordinat y dari titik kontrol kedua kurva. |
| x4 | Single | Koordinat x titik akhir kurva. |
| y4 | Single | Koordinat y titik akhir kurva. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* adalah nol. |

### Lihat juga

* class [Pen](../../pen/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Menggambar spline Bézier yang ditentukan oleh empat[`PointF`](../../pointf/) struktur.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) yang menentukan warna, lebar, dan gaya kurva. |
| pt1 | PointF | [`PointF`](../../pointf/) struktur yang mewakili titik awal kurva. |
| pt2 | PointF | [`PointF`](../../pointf/) struktur yang mewakili titik kontrol pertama untuk kurva. |
| pt3 | PointF | [`PointF`](../../pointf/) struktur yang mewakili titik kontrol kedua untuk kurva. |
| pt4 | PointF | [`PointF`](../../pointf/) struktur yang mewakili titik akhir dari kurva. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* adalah nol. |

### Lihat juga

* class [Pen](../../pen/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Menggambar spline Bézier yang ditentukan oleh empat[`Point`](../../point/) struktur.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen/) struktur yang menentukan warna, lebar, dan gaya kurva. |
| pt1 | Point | [`Point`](../../point/) struktur yang mewakili titik awal kurva. |
| pt2 | Point | [`Point`](../../point/) struktur yang mewakili titik kontrol pertama untuk kurva. |
| pt3 | Point | [`Point`](../../point/) struktur yang mewakili titik kontrol kedua untuk kurva. |
| pt4 | Point | [`Point`](../../point/) struktur yang mewakili titik akhir dari kurva. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *pen* adalah nol. |

### Lihat juga

* class [Pen](../../pen/)
* struct [Point](../../point/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)


