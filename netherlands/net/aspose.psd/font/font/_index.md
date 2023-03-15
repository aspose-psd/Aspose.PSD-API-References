---
title: Font.Font
second_title: Aspose.PSD voor .NET API-referentie
description: Font constructeur. Initialiseert een nieuwFont dat gebruik maakt van de gespecificeerde bestaandeFont EnFontStyle opsomming.
type: docs
weight: 10
url: /nl/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Initialiseert een nieuw[`Font`](../) dat gebruik maakt van de gespecificeerde bestaande[`Font`](../) En[`FontStyle`](../../fontstyle/) opsomming.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| prototype | Font | Het bestaan[`Font`](../) waaruit het nieuwe ontstaat[`Font`](../). |
| newStyle | FontStyle | De[`FontStyle`](../../fontstyle/) toe te passen op het nieuwe[`Font`](../) . Meerdere waarden van de[`FontStyle`](../../fontstyle/) opsomming kan worden gecombineerd met de OR-operator. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | *prototype* is niets. |

### Zie ook

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* naamruimte [Aspose.PSD](../../font/)
* montage [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Initialiseert een nieuw[`Font`](../) een opgegeven maat gebruiken. De tekenset is ingesteld opDefault , de grafische eenheid naarPoint , de lettertypestijl aanRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | String | Een tekenreeksrepresentatie van de[`Font`](../) naam. |
| emSize | Single | De em-grootte, in punten, van het nieuwe lettertype. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* is kleiner dan of gelijk aan 0, resulteert in oneindig of is geen geldig getal. |
| ArgumentNullException | *fontName* is niets. |

### Zie ook

* class [Font](../)
* naamruimte [Aspose.PSD](../../font/)
* montage [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Initialiseert een nieuw[`Font`](../) met behulp van een opgegeven grootte en stijl. De tekenset is ingesteld opDefault , de grafische eenheid naarPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | String | Een tekenreeksrepresentatie van de[`Font`](../) naam. |
| emSize | Single | De em-grootte, in punten, van het nieuwe lettertype. |
| style | FontStyle | De[`FontStyle`](../../fontstyle/) van het nieuwe lettertype. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* is kleiner dan of gelijk aan 0, resulteert in oneindig of is geen geldig getal. |
| ArgumentNullException | *fontName* is niets. |

### Zie ook

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* naamruimte [Aspose.PSD](../../font/)
* montage [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Initialiseert een nieuw[`Font`](../) met behulp van een gespecificeerde maat en eenheid. De tekenset is ingesteld opDefault is de stijl ingesteld opRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | String | Een tekenreeksrepresentatie van de[`Font`](../) naam. |
| emSize | Single | De em-grootte van het nieuwe lettertype in de eenheden gespecificeerd door de*unit* parameter. |
| unit | GraphicsUnit | De[`GraphicsUnit`](../../graphicsunit/) van het nieuwe lettertype. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* is kleiner dan of gelijk aan 0, resulteert in oneindig of is geen geldig getal. |
| ArgumentNullException | *fontName* is niets. |

### Zie ook

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* naamruimte [Aspose.PSD](../../font/)
* montage [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Initialiseert een nieuw[`Font`](../) met behulp van een gespecificeerde grootte, stijl, eenheid en tekenset.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | String | Een tekenreeksrepresentatie van de[`Font`](../) naam. |
| emSize | Single | De em-grootte van het nieuwe lettertype in de eenheden gespecificeerd door de*unit* parameter. |
| style | FontStyle | De[`FontStyle`](../../fontstyle/) van het nieuwe lettertype. |
| unit | GraphicsUnit | De[`GraphicsUnit`](../../graphicsunit/) van het nieuwe lettertype. |
| characterSet | CharacterSet | Een tekenset die voor dit lettertype moet worden gebruikt. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* is kleiner dan of gelijk aan 0, resulteert in oneindig of is geen geldig getal. |
| ArgumentNullException | *fontName* is niets. |

### Zie ook

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* naamruimte [Aspose.PSD](../../font/)
* montage [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Initialiseert een nieuw[`Font`](../) met een opgegeven grootte, stijl en eenheid.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | String | Een tekenreeksrepresentatie van de[`Font`](../) naam. |
| emSize | Single | De em-grootte van het nieuwe lettertype in de eenheden gespecificeerd door de*unit* parameter. |
| style | FontStyle | De[`FontStyle`](../../fontstyle/) van het nieuwe lettertype. |
| unit | GraphicsUnit | De[`GraphicsUnit`](../../graphicsunit/) van het nieuwe lettertype. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* is kleiner dan of gelijk aan 0, resulteert in oneindig of is geen geldig getal. |
| ArgumentNullException | *fontName* is niets. |

### Zie ook

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* naamruimte [Aspose.PSD](../../font/)
* montage [Aspose.PSD](../../../)


