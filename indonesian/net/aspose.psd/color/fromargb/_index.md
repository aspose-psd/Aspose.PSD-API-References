---
title: Color.FromArgb
second_title: Aspose.PSD untuk Referensi .NET API
description: Color metode. Membuat aColor struktur dari nilai ARGB 32bit.
type: docs
weight: 1430
url: /id/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

Membuat a[`Color`](../) struktur dari nilai ARGB 32-bit.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| argb | Int32 | Nilai yang menentukan nilai ARGB 32-bit. |

### Nilai Pengembalian

Itu[`Color`](../) struktur yang diciptakan metode ini.

### Lihat juga

* struct [Color](../)
* ruang nama [Aspose.PSD](../../color/)
* perakitan [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Membuat a[`Color`](../) struktur dari empat nilai komponen ARGB (alfa, merah, hijau, dan biru). Meskipun metode ini memungkinkan nilai 32-bit dilewatkan untuk setiap komponen, nilai setiap komponen dibatasi hingga 8 bit.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| alpha | Int32 | Komponen alfa. Nilai yang valid adalah 0 hingga 255. |
| red | Int32 | Komponen merah. Nilai yang valid adalah 0 hingga 255. |
| green | Int32 | Komponen hijau. Nilai yang valid adalah 0 hingga 255. |
| blue | Int32 | Komponen biru. Nilai yang valid adalah 0 hingga 255. |

### Nilai Pengembalian

Itu[`Color`](../) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , atau*blue* kurang dari 0 atau lebih besar dari 255. |

### Lihat juga

* struct [Color](../)
* ruang nama [Aspose.PSD](../../color/)
* perakitan [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Membuat a[`Color`](../) struktur dari yang ditentukan[`Color`](../) struktur, tetapi dengan nilai alpha baru yang ditentukan. Meskipun metode ini memungkinkan nilai 32-bit dilewatkan untuk nilai alfa, nilainya dibatasi hingga 8 bit.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| alpha | Int32 | Nilai alfa untuk yang baru[`Color`](../). Nilai yang valid adalah 0 hingga 255. |
| baseColor | Color | Itu[`Color`](../) dari mana untuk membuat yang baru[`Color`](../). |

### Nilai Pengembalian

Itu[`Color`](../) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* kurang dari 0 atau lebih besar dari 255. |

### Lihat juga

* struct [Color](../)
* ruang nama [Aspose.PSD](../../color/)
* perakitan [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Membuat a[`Color`](../) struktur dari nilai warna 8-bit yang ditentukan (merah, hijau, dan biru). Nilai alfa secara implisit 255 (sepenuhnya buram). Meskipun metode ini memungkinkan nilai 32-bit dilewatkan untuk setiap komponen warna, nilai setiap komponen dibatasi hingga 8 bit.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| red | Int32 | Nilai komponen merah untuk yang baru[`Color`](../). Nilai yang valid adalah 0 hingga 255. |
| green | Int32 | Nilai komponen hijau untuk yang baru[`Color`](../). Nilai yang valid adalah 0 hingga 255. |
| blue | Int32 | Nilai komponen biru untuk yang baru[`Color`](../). Nilai yang valid adalah 0 hingga 255. |

### Nilai Pengembalian

Itu[`Color`](../) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , atau*blue* kurang dari 0 atau lebih besar dari 255. |

### Lihat juga

* struct [Color](../)
* ruang nama [Aspose.PSD](../../color/)
* perakitan [Aspose.PSD](../../../)


