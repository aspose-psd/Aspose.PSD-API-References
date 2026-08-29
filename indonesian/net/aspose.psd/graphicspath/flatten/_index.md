---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode GraphicsPath. Mengonversi setiap kurva dalam path ini menjadi urutan segmen garis yang terhubung"
type: docs
weight: 90
url: /id/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

Mengonversi setiap kurva dalam jalur ini menjadi urutan segmen garis yang terhubung.

```csharp
public void Flatten()
```

### Lihat Juga

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Menerapkan transformasi yang ditentukan dan kemudian mengonversi setiap kurva dalam [`GraphicsPath`](../) menjadi urutan segmen garis yang terhubung.

```csharp
public void Flatten(Matrix matrix)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | Matrix | Sebuah [`Matrix`](../../matrix/) yang digunakan untuk mentransformasi [`GraphicsPath`](../) ini sebelum diratakan. |

### Lihat Juga

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Mengonversi setiap kurva dalam [`GraphicsPath`](../) menjadi urutan segmen garis yang terhubung.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | Matrix | Sebuah [`Matrix`](../../matrix/) yang digunakan untuk mentransformasi [`GraphicsPath`](../) ini sebelum diratakan. |
| kelengkungan | Single | Menentukan kesalahan maksimum yang diizinkan antara kurva dan pendekatan yang diratakan. Nilai 0.25 adalah nilai default. Mengurangi nilai flatness akan meningkatkan jumlah segmen garis dalam pendekatan. |

### Lihat Juga

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


