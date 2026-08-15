---
title: "Font Sınıfı"
type: docs
weight: 1340
url: /tr/python-net/aspose.psd/font/
---

**Summary:** Defines a particular format for text, including font face, size, and style attributes. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Font

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [Font(font_name, em_size)](#Font_font_name_em_size_1) | Belirtilen bir boyut kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) olarak, grafik birimi [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) olarak, yazı tipi stili ise [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) olarak ayarlanır. |
| [Font(font_name, em_size, style)](#Font_font_name_em_size_style_2) | Belirtilen bir boyut ve stil kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) olarak, grafik birimi ise [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) olarak ayarlanır. |
| [Font(font_name, em_size, style, unit)](#Font_font_name_em_size_style_unit_3) | Belirtilen bir boyut, stil ve birim kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. |
| [Font(font_name, em_size, style, unit, character_set)](#Font_font_name_em_size_style_unit_character_set_4) | Belirtilen bir boyut, stil, birim ve karakter kümesi kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. |
| [Font(font_name, em_size, unit)](#Font_font_name_em_size_unit_5) | Belirtilen bir boyut ve birim kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) olarak ayarlanır, stil ise [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) olarak ayarlanır. |
| [Font(prototype, new_style)](#Font_prototype_new_style_6) | Belirtilen mevcut bir [Font](/psd/python-net/aspose.psd/font/) ve [FontStyle](/psd/python-net/aspose.psd/fontstyle/) dizisini kullanan yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| bold | bool | r | Bu [Font](/psd/python-net/aspose.psd/font/) kalın mı olduğunu gösteren bir değer alır. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | r | Bu [Font](/psd/python-net/aspose.psd/font/) tarafından kullanılan karakter kümesini belirten bir bayt değeri alır. |
| italic | bool | r | Bu [Font](/psd/python-net/aspose.psd/font/) eğik mi olduğunu gösteren bir değer alır. |
| name | string | r | Bu [Font](/psd/python-net/aspose.psd/font/) yüz adını alır. |
| size | float | r | Bu [Font](/psd/python-net/aspose.psd/font/) em-boyutunu, [Font.unit](/psd/python-net/aspose.psd/font/) özelliği tarafından belirtilen birimlerde ölçülmüş olarak alır. |
| strikeout | bool | r | Bu [Font](/psd/python-net/aspose.psd/font/) üzerinden yatay bir çizgi belirtiyor mu olduğunu gösteren bir değer alır. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | r | Bu [Font](/psd/python-net/aspose.psd/font/) için stil bilgilerini alır. |
| underline | bool | r | Bu [Font](/psd/python-net/aspose.psd/font/) altı çizili mi olduğunu gösteren bir değer alır. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | r | Bu [Font](/psd/python-net/aspose.psd/font/) için ölçü birimini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Bu [Font](/psd/python-net/aspose.psd/font/) tam bir derin kopyasını oluşturur. |


### Constructor: Font(font_name, em_size) {#Font_font_name_em_size_1}


```
 Font(font_name, em_size) 
```

Belirtilen bir boyut kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) olarak, grafik birimi [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) olarak, yazı tipi stili ise [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) olarak ayarlanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) adının dize temsili. |
| em_size | float | Yeni fontun puan cinsinden em-boyutu. |

### Constructor: Font(font_name, em_size, style) {#Font_font_name_em_size_style_2}


```
 Font(font_name, em_size, style) 
```

Belirtilen bir boyut ve stil kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) olarak, grafik birimi ise [GraphicsUnit.POINT](/psd/python-net/aspose.psd/graphicsunit/) olarak ayarlanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) adının dize temsili. |
| em_size | float | Yeni fontun puan cinsinden em-boyutu. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Yeni fontun [FontStyle](/psd/python-net/aspose.psd/fontstyle/) değeri. |

### Constructor: Font(font_name, em_size, style, unit) {#Font_font_name_em_size_style_unit_3}


```
 Font(font_name, em_size, style, unit) 
```

Belirtilen bir boyut, stil ve birim kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) adının dize temsili. |
| em_size | float | Yeni fontun <paramref name="unit" /> parametresi tarafından belirtilen birimlerdeki em-boyutu. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Yeni fontun [FontStyle](/psd/python-net/aspose.psd/fontstyle/) değeri. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Yeni fontun [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) değeri. |

### Constructor: Font(font_name, em_size, style, unit, character_set) {#Font_font_name_em_size_style_unit_character_set_4}


```
 Font(font_name, em_size, style, unit, character_set) 
```

Belirtilen bir boyut, stil, birim ve karakter kümesi kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) adının dize temsili. |
| em_size | float | Yeni fontun <paramref name="unit" /> parametresi tarafından belirtilen birimlerdeki em-boyutu. |
| style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Yeni fontun [FontStyle](/psd/python-net/aspose.psd/fontstyle/) değeri. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Yeni fontun [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) değeri. |
| character_set | [CharacterSet](/psd/python-net/aspose.psd/characterset) | Bu font için kullanılacak bir karakter kümesi. |

### Constructor: Font(font_name, em_size, unit) {#Font_font_name_em_size_unit_5}


```
 Font(font_name, em_size, unit) 
```

Belirtilen bir boyut ve birim kullanarak yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır. Karakter kümesi [CharacterSet.DEFAULT](/psd/python-net/aspose.psd/characterset/) olarak ayarlanır, stil ise [FontStyle.REGULAR](/psd/python-net/aspose.psd/fontstyle/) olarak ayarlanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | [Font](/psd/python-net/aspose.psd/font/) adının dize temsili. |
| em_size | float | Yeni fontun <paramref name="unit" /> parametresi tarafından belirtilen birimlerdeki em-boyutu. |
| unit | [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit) | Yeni fontun [GraphicsUnit](/psd/python-net/aspose.psd/graphicsunit/) değeri. |

### Constructor: Font(prototype, new_style) {#Font_prototype_new_style_6}


```
 Font(prototype, new_style) 
```

Belirtilen mevcut bir [Font](/psd/python-net/aspose.psd/font/) ve [FontStyle](/psd/python-net/aspose.psd/fontstyle/) dizisini kullanan yeni bir [Font](/psd/python-net/aspose.psd/font/) başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| prototype | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Yeni [Font](/psd/python-net/aspose.psd/font/) oluşturulacak mevcut [Font](/psd/python-net/aspose.psd/font/). |
| new_style | [FontStyle](/psd/python-net/aspose.psd/fontstyle) | Yeni [Font](/psd/python-net/aspose.psd/font/) uygulanacak [FontStyle](/psd/python-net/aspose.psd/fontstyle/). [FontStyle](/psd/python-net/aspose.psd/fontstyle/) dizisinin birden çok değeri OR operatörüyle birleştirilebilir. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Bu [Font](/psd/python-net/aspose.psd/font/) tam bir derin kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Bu yöntemin oluşturduğu [Font](/psd/python-net/aspose.psd/font/). |


