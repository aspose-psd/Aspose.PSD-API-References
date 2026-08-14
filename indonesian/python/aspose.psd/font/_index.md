---
title: "Font Kelas"
type: docs
weight: 1340
url: /id/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Menginisialisasi [Font](/psd/python-net/aspose.psd/font/) baru dengan ukuran yang ditentukan. Set karakter diatur ke [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), unit grafis ke [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), dan gaya font ke [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Menginisialisasi [Font](/psd/python-net/aspose.psd/font/) baru dengan ukuran dan gaya yang ditentukan. Set karakter diatur ke [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), dan unit grafis ke [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/). |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Menginisialisasi [Font](/psd/python-net/aspose.psd/font/) baru dengan ukuran, gaya, dan unit yang ditentukan. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Menginisialisasi [Font](/psd/python-net/aspose.psd/font/) baru dengan ukuran, gaya, unit, dan set karakter yang ditentukan. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Menginisialisasi sebuah [Font](/psd/python-net/aspose.psd/font/) baru menggunakan ukuran dan satuan yang ditentukan. Set karakter diatur ke [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), gaya diatur ke [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/). |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Menginisialisasi sebuah [Font](/psd/python-net/aspose.psd/font/) baru yang menggunakan [Font](/psd/python-net/aspose.psd/font/) yang ada dan enumerasi [FontStyle](/psd/python-net/aspose.psd/fontstyle/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bold | bool | r | Mendapatkan nilai yang menunjukkan apakah [Font](/psd/python-net/aspose.psd/font/) ini tebal. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Mendapatkan nilai byte yang menentukan set karakter yang digunakan oleh [Font](/psd/python-net/aspose.psd/font/). |
| italic | bool | r | Mendapatkan nilai yang menunjukkan apakah [Font](/psd/python-net/aspose.psd/font/) ini miring. |
| name | string | r | Mendapatkan nama wajah dari [Font](/psd/python-net/aspose.psd/font/). |
| size | float | r | Mendapatkan ukuran em dari [Font](/psd/python-net/aspose.psd/font/) yang diukur dalam satuan yang ditentukan oleh properti [Font.unit](/psd/python-net/aspose.psd/font/). |
| strikeout | bool | r | Mendapatkan nilai yang menunjukkan apakah [Font](/psd/python-net/aspose.psd/font/) ini memiliki garis horizontal melalui huruf. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Mendapatkan informasi gaya untuk [Font](/psd/python-net/aspose.psd/font/). |
| underline | bool | r | Mendapatkan nilai yang menunjukkan apakah [Font](/psd/python-net/aspose.psd/font/) ini bergaris bawah. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Mendapatkan satuan ukuran untuk [Font](/psd/python-net/aspose.psd/font/). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Membuat salinan dalam yang tepat dari [Font](/psd/python-net/aspose.psd/font/). |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Menginisialisasi [Font](/psd/python-net/aspose.psd/font/) baru dengan ukuran yang ditentukan. Set karakter diatur ke [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), unit grafis ke [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/), dan gaya font ke [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_name | string | Representasi string dari nama [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Ukuran em, dalam poin, dari font baru. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Menginisialisasi [Font](/psd/python-net/aspose.psd/font/) baru dengan ukuran dan gaya yang ditentukan. Set karakter diatur ke [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), dan unit grafis ke [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_name | string | Representasi string dari nama [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Ukuran em, dalam poin, dari font baru. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) dari font baru. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Menginisialisasi [Font](/psd/python-net/aspose.psd/font/) baru dengan ukuran, gaya, dan unit yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_name | string | Representasi string dari nama [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) dari font baru. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) dari font baru. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Menginisialisasi [Font](/psd/python-net/aspose.psd/font/) baru dengan ukuran, gaya, unit, dan set karakter yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_name | string | Representasi string dari nama [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter <paramref name="unit" />. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) dari font baru. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) dari font baru. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Set karakter yang akan digunakan untuk font ini. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Menginisialisasi sebuah [Font](/psd/python-net/aspose.psd/font/) baru menggunakan ukuran dan satuan yang ditentukan. Set karakter diatur ke [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/), gaya diatur ke [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| font_name | string | Representasi string dari nama [Font](/psd/python-net/aspose.psd/font/). |
| em_size | float | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter <paramref name="unit" />. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) dari font baru. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Menginisialisasi sebuah [Font](/psd/python-net/aspose.psd/font/) baru yang menggunakan [Font](/psd/python-net/aspose.psd/font/) yang ada dan enumerasi [FontStyle](/psd/python-net/aspose.psd/fontstyle/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) yang ada yang akan dijadikan dasar untuk membuat [Font](/psd/python-net/aspose.psd/font/) baru. |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | [FontStyle](/psd/python-net/aspose.psd/fontstyle/) yang akan diterapkan pada [Font](/psd/python-net/aspose.psd/font/) baru. Beberapa nilai dari enumerasi [FontStyle](/psd/python-net/aspose.psd/fontstyle/) dapat digabungkan dengan operator OR. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Membuat salinan dalam yang tepat dari [Font](/psd/python-net/aspose.psd/font/).

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | [Font](/psd/python-net/aspose.psd/font/) yang dibuat oleh metode ini. |


