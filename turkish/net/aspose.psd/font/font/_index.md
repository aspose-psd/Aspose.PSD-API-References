---
title: Font.Font
second_title: Aspose.PSD for .NET API Referansı
description: Font inşaatçı. Yeni bir başlatırFont belirtilen mevcut olanı kullananFont VeFontStyle numaralandırma.
type: docs
weight: 10
url: /tr/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Yeni bir başlatır[`Font`](../) belirtilen mevcut olanı kullanan[`Font`](../) Ve[`FontStyle`](../../fontstyle/) numaralandırma.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| prototype | Font | Var olan[`Font`](../) yenisini yaratmak için[`Font`](../). |
| newStyle | FontStyle | bu[`FontStyle`](../../fontstyle/) yeni uygulamaya başvurmak[`Font`](../) . Birden çok değer[`FontStyle`](../../fontstyle/) numaralandırma OR işleci ile birleştirilebilir. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | *prototype* boş. |

### Ayrıca bakınız

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* ad alanı [Aspose.PSD](../../font/)
* toplantı [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Yeni bir başlatır[`Font`](../) belirli bir boyut kullanarak. Karakter seti şu şekilde ayarlanmıştır:Default , grafik birimiPoint , yazı tipi stiliRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | Bir dize temsili[`Font`](../) isim. |
| emSize | Single | Yeni yazı tipinin punto cinsinden em boyutu. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya eşittir, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* class [Font](../)
* ad alanı [Aspose.PSD](../../font/)
* toplantı [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Yeni bir başlatır[`Font`](../) belirli bir boyut ve stil kullanarak. Karakter seti şu şekilde ayarlanmıştır:Default , grafik birimiPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | Bir dize temsili[`Font`](../) isim. |
| emSize | Single | Yeni yazı tipinin punto cinsinden em boyutu. |
| style | FontStyle | bu[`FontStyle`](../../fontstyle/) yeni yazı tipinin. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya eşittir, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* ad alanı [Aspose.PSD](../../font/)
* toplantı [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Yeni bir başlatır[`Font`](../) belirli bir boyut ve birim kullanarak. Karakter seti şu şekilde ayarlanmıştır:Default stil şu şekilde ayarlanır:Regular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | Bir dize temsili[`Font`](../) isim. |
| emSize | Single | tarafından belirtilen birimlerde yeni yazı tipinin em boyutu*unit* parametre. |
| unit | GraphicsUnit | bu[`GraphicsUnit`](../../graphicsunit/) yeni yazı tipinin. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya eşittir, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* ad alanı [Aspose.PSD](../../font/)
* toplantı [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Yeni bir başlatır[`Font`](../) belirtilen bir boyut, stil, birim ve karakter seti kullanarak.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | Bir dize temsili[`Font`](../) isim. |
| emSize | Single | tarafından belirtilen birimlerde yeni yazı tipinin em boyutu*unit* parametre. |
| style | FontStyle | bu[`FontStyle`](../../fontstyle/) yeni yazı tipinin. |
| unit | GraphicsUnit | bu[`GraphicsUnit`](../../graphicsunit/) yeni yazı tipinin. |
| characterSet | CharacterSet | Bu yazı tipi için kullanılacak bir karakter kümesi. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya eşittir, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* ad alanı [Aspose.PSD](../../font/)
* toplantı [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Yeni bir başlatır[`Font`](../) belirtilen bir boyut, stil ve birim kullanarak.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fontName | String | Bir dize temsili[`Font`](../) isim. |
| emSize | Single | tarafından belirtilen birimlerde yeni yazı tipinin em boyutu*unit* parametre. |
| style | FontStyle | bu[`FontStyle`](../../fontstyle/) yeni yazı tipinin. |
| unit | GraphicsUnit | bu[`GraphicsUnit`](../../graphicsunit/) yeni yazı tipinin. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 0'dan küçük veya eşittir, sonsuz olarak değerlendirilir veya geçerli bir sayı değildir. |
| ArgumentNullException | *fontName* boş. |

### Ayrıca bakınız

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* ad alanı [Aspose.PSD](../../font/)
* toplantı [Aspose.PSD](../../../)


