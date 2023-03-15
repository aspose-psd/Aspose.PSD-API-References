---
title: Font.Font
second_title: Aspose.PSD untuk Referensi .NET API
description: Font konstruktor. Menginisialisasi yang baruFont yang menggunakan ditentukan adaFont DanFontStyle pencacahan.
type: docs
weight: 10
url: /id/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Menginisialisasi yang baru[`Font`](../) yang menggunakan ditentukan ada[`Font`](../) Dan[`FontStyle`](../../fontstyle/) pencacahan.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| prototype | Font | Yang ada[`Font`](../) dari mana untuk membuat yang baru[`Font`](../). |
| newStyle | FontStyle | Itu[`FontStyle`](../../fontstyle/) untuk melamar yang baru[`Font`](../) . Beberapa nilai dari[`FontStyle`](../../fontstyle/) pencacahan dapat dikombinasikan dengan operator OR. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *prototype* adalah nol. |

### Lihat juga

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* ruang nama [Aspose.PSD](../../font/)
* perakitan [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Menginisialisasi yang baru[`Font`](../) menggunakan ukuran tertentu. Set karakter diatur keDefault , unit grafik kePoint , gaya font keRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontName | String | Representasi string dari[`Font`](../) nama. |
| emSize | Single | Ukuran em, dalam poin, dari font baru. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, dievaluasi hingga tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* adalah nol. |

### Lihat juga

* class [Font](../)
* ruang nama [Aspose.PSD](../../font/)
* perakitan [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Menginisialisasi yang baru[`Font`](../) menggunakan ukuran dan gaya tertentu. Set karakter diatur keDefault , unit grafik kePoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontName | String | Representasi string dari[`Font`](../) nama. |
| emSize | Single | Ukuran em, dalam poin, dari font baru. |
| style | FontStyle | Itu[`FontStyle`](../../fontstyle/) dari font baru. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, dievaluasi hingga tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* adalah nol. |

### Lihat juga

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* ruang nama [Aspose.PSD](../../font/)
* perakitan [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Menginisialisasi yang baru[`Font`](../) menggunakan ukuran dan satuan tertentu. Set karakter diatur keDefault gaya diatur keRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontName | String | Representasi string dari[`Font`](../) nama. |
| emSize | Single | Ukuran font baru dalam unit yang ditentukan oleh*unit* parameter. |
| unit | GraphicsUnit | Itu[`GraphicsUnit`](../../graphicsunit/) dari font baru. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, dievaluasi hingga tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* adalah nol. |

### Lihat juga

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* ruang nama [Aspose.PSD](../../font/)
* perakitan [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Menginisialisasi yang baru[`Font`](../) menggunakan ukuran, gaya, unit, dan kumpulan karakter yang ditentukan.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontName | String | Representasi string dari[`Font`](../) nama. |
| emSize | Single | Ukuran font baru dalam unit yang ditentukan oleh*unit* parameter. |
| style | FontStyle | Itu[`FontStyle`](../../fontstyle/) dari font baru. |
| unit | GraphicsUnit | Itu[`GraphicsUnit`](../../graphicsunit/) dari font baru. |
| characterSet | CharacterSet | Kumpulan karakter yang akan digunakan untuk font ini. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, dievaluasi hingga tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* adalah nol. |

### Lihat juga

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* ruang nama [Aspose.PSD](../../font/)
* perakitan [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Menginisialisasi yang baru[`Font`](../) menggunakan ukuran, gaya, dan satuan tertentu.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fontName | String | Representasi string dari[`Font`](../) nama. |
| emSize | Single | Ukuran font baru dalam unit yang ditentukan oleh*unit* parameter. |
| style | FontStyle | Itu[`FontStyle`](../../fontstyle/) dari font baru. |
| unit | GraphicsUnit | Itu[`GraphicsUnit`](../../graphicsunit/) dari font baru. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, dievaluasi hingga tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* adalah nol. |

### Lihat juga

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* ruang nama [Aspose.PSD](../../font/)
* perakitan [Aspose.PSD](../../../)


