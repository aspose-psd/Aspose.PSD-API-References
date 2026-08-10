---
title: "Font.Font"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor Font. Menginisialisasi Font baru yang menggunakan Font yang ada dan enumerasi FontStyle yang ditentukan."
type: docs
weight: 10
url: /id/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

Menginisialisasi [`Font`](../) baru yang menggunakan [`Font`](../) yang ada dan enumerasi [`FontStyle`](../../fontstyle/) yang ditentukan.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prototype | Font | [`Font`](../) yang ada untuk membuat [`Font`](../) baru. |
| newStyle | FontStyle | [`FontStyle`](../../fontstyle/) yang akan diterapkan pada [`Font`](../) baru. Beberapa nilai dari enumerasi [`FontStyle`](../../fontstyle/) dapat digabungkan dengan operator OR. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *prototype* bernilai null. |

### Lihat Juga

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Menginisialisasi [`Font`](../) baru dengan ukuran yang ditentukan. Set karakter diatur ke Default, unit grafik ke Point, gaya font ke Regular.

```csharp
public Font(string fontName, float emSize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Representasi string dari nama [`Font`](../). |
| emSize | Single | Ukuran em, dalam poin, dari font baru. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, menghasilkan tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* bernilai null. |

### Lihat Juga

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Menginisialisasi [`Font`](../) baru dengan ukuran dan gaya yang ditentukan. Set karakter diatur ke Default, unit grafik ke Point.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Representasi string dari nama [`Font`](../). |
| emSize | Single | Ukuran em, dalam poin, dari font baru. |
| style | FontStyle | [`FontStyle`](../../fontstyle/) dari font baru. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, menghasilkan tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* bernilai null. |

### Lihat Juga

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Menginisialisasi [`Font`](../) baru dengan ukuran dan unit yang ditentukan. Set karakter diatur ke Default, gaya diatur ke Regular.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Representasi string dari nama [`Font`](../). |
| emSize | Single | Ukuran em dari font baru dalam unit yang ditentukan oleh parameter *unit*. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) dari font baru. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, menghasilkan tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* bernilai null. |

### Lihat Juga

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Menginisialisasi [`Font`](../) baru dengan ukuran, gaya, unit, dan set karakter yang ditentukan.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Representasi string dari nama [`Font`](../). |
| emSize | Single | Ukuran em dari font baru dalam unit yang ditentukan oleh parameter *unit*. |
| style | FontStyle | [`FontStyle`](../../fontstyle/) dari font baru. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) dari font baru. |
| characterSet | CharacterSet | Set karakter yang digunakan untuk font ini. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, menghasilkan tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* bernilai null. |

### Lihat Juga

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Menginisialisasi [`Font`](../) baru dengan ukuran, gaya, dan unit yang ditentukan.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | String | Representasi string dari nama [`Font`](../). |
| emSize | Single | Ukuran em dari font baru dalam unit yang ditentukan oleh parameter *unit*. |
| style | FontStyle | [`FontStyle`](../../fontstyle/) dari font baru. |
| unit | GraphicsUnit | [`GraphicsUnit`](../../graphicsunit/) dari font baru. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kurang dari atau sama dengan 0, menghasilkan tak terhingga atau bukan angka yang valid. |
| ArgumentNullException | *fontName* bernilai null. |

### Lihat Juga

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


