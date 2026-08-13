---
title: "Font.Font"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Font yapıcı. Belirtilen mevcut Font ve FontStyle enum'ını kullanan yeni bir Font başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

Belirtilen mevcut [`Font`](../) ve [`FontStyle`](../../fontstyle/) enum'ını kullanan yeni bir [`Font`](../) başlatır.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prototype | Font | Yeni [`Font`](../) oluşturulacak mevcut [`Font`](../). |
| newStyle | FontStyle | Yeni [`Font`](../) üzerine uygulanacak [`FontStyle`](../../fontstyle/). [`FontStyle`](../../fontstyle/) enum'ının birden fazla değeri OR operatörüyle birleştirilebilir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *prototype* null. |

### Ayrıca Bakınız

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Belirtilen bir boyut kullanarak yeni bir [`Font`](../) başlatır. Karakter kümesi Default, grafik birimi Point ve font stili Regular olarak ayarlanır.

```csharp
public Font(string fontName, float emSize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | [`Font`](../) adının dize temsili. |
| emSize | Single | Yeni yazı tipinin nokta cinsinden em-boyutu. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'a eşit ya da daha küçük, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* null değerindedir. |

### Ayrıca Bakınız

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Belirtilen boyut ve stil kullanılarak yeni bir [`Font`](../) başlatır. Karakter kümesi Default, grafik birimi Point olarak ayarlanır.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | [`Font`](../) adının dize temsili. |
| emSize | Single | Yeni yazı tipinin nokta cinsinden em-boyutu. |
| style | FontStyle | Yeni yazı tipinin [`FontStyle`](../../fontstyle/) değeri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'a eşit ya da daha küçük, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* null değerindedir. |

### Ayrıca Bakınız

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Belirtilen boyut ve birim kullanılarak yeni bir [`Font`](../) başlatır. Karakter kümesi Default, stil Regular olarak ayarlanır.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | [`Font`](../) adının dize temsili. |
| emSize | Single | Yeni yazı tipinin *unit* parametresiyle belirtilen birimlerdeki em-boyutu. |
| unit | GraphicsUnit | Yeni yazı tipinin [`GraphicsUnit`](../../graphicsunit/) değeri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'a eşit ya da daha küçük, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* null değerindedir. |

### Ayrıca Bakınız

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Belirtilen boyut, stil, birim ve karakter kümesi kullanılarak yeni bir [`Font`](../) başlatır.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | [`Font`](../) adının dize temsili. |
| emSize | Single | Yeni yazı tipinin *unit* parametresiyle belirtilen birimlerdeki em-boyutu. |
| style | FontStyle | Yeni yazı tipinin [`FontStyle`](../../fontstyle/) değeri. |
| unit | GraphicsUnit | Yeni yazı tipinin [`GraphicsUnit`](../../graphicsunit/) değeri. |
| characterSet | CharacterSet | Bu yazı tipi için kullanılacak bir karakter kümesi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'a eşit ya da daha küçük, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* null değerindedir. |

### Ayrıca Bakınız

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Belirtilen boyut, stil ve birim kullanılarak yeni bir [`Font`](../) başlatır.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | String | [`Font`](../) adının dize temsili. |
| emSize | Single | Yeni yazı tipinin *unit* parametresiyle belirtilen birimlerdeki em-boyutu. |
| style | FontStyle | Yeni yazı tipinin [`FontStyle`](../../fontstyle/) değeri. |
| unit | GraphicsUnit | Yeni yazı tipinin [`GraphicsUnit`](../../graphicsunit/) değeri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'a eşit ya da daha küçük, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* null değerindedir. |

### Ayrıca Bakınız

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


