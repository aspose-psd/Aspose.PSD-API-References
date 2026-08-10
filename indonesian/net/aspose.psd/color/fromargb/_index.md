---
title: "Color.FromArgb"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Color. Membuat struktur Color dari nilai ARGB 32‑bit"
type: docs
weight: 1430
url: /id/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

Membuat struktur [`Color`](../) dari nilai ARGB 32‑bit.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| argb | Int32 | Nilai yang menentukan nilai ARGB 32‑bit. |

### Nilai Kembalian

Struktur [`Color`](../) yang dibuat oleh metode ini.

### Lihat Juga

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Membuat struktur [`Color`](../) dari empat nilai komponen ARGB (alpha, merah, hijau, dan biru). Meskipun metode ini memungkinkan nilai 32‑bit diberikan untuk setiap komponen, nilai setiap komponen dibatasi hingga 8 bit.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alpha | Int32 | Komponen alpha. Nilai yang valid antara 0 hingga 255. |
| merah | Int32 | Komponen merah. Nilai yang valid antara 0 hingga 255. |
| hijau | Int32 | Komponen hijau. Nilai yang valid antara 0 hingga 255. |
| biru | Int32 | Komponen biru. Nilai yang valid antara 0 hingga 255. |

### Nilai Kembalian

[`Color`](../) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *red*, *green*, atau *blue* kurang dari 0 atau lebih besar dari 255. |

### Lihat Juga

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Membuat struktur [`Color`](../) dari struktur [`Color`](../) yang ditentukan, tetapi dengan nilai alfa baru yang ditentukan. Meskipun metode ini memungkinkan nilai 32-bit diteruskan untuk nilai alfa, nilai tersebut dibatasi hingga 8 bit.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alpha | Int32 | Nilai alfa untuk [`Color`](../) baru. Nilai yang valid adalah 0 hingga 255. |
| baseColor | Color | `[`Color`](../)` yang akan digunakan untuk membuat [`Color`](../) baru. |

### Nilai Kembalian

[`Color`](../) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* kurang dari 0 atau lebih besar dari 255. |

### Lihat Juga

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Membuat struktur [`Color`](../) dari nilai warna 8-bit yang ditentukan (merah, hijau, dan biru). Nilai alfa secara implisit 255 (sepenuhnya tidak tembus). Meskipun metode ini memungkinkan nilai 32-bit diteruskan untuk setiap komponen warna, nilai setiap komponen dibatasi hingga 8 bit.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| red | Int32 | Nilai komponen merah untuk [`Color`](../) baru. Nilai yang valid adalah 0 hingga 255. |
| green | Int32 | Nilai komponen hijau untuk [`Color`](../) baru. Nilai yang valid adalah 0 hingga 255. |
| blue | Int32 | Nilai komponen biru untuk [`Color`](../) baru. Nilai yang valid adalah 0 hingga 255. |

### Nilai Kembalian

[`Color`](../) yang dibuat oleh metode ini.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *red*, *green*, atau *blue* kurang dari 0 atau lebih besar dari 255. |

### Lihat Juga

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


