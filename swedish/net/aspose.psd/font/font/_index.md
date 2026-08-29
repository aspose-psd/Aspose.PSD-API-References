---
title: "Font.Font"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Font-konstruktor. Initierar ett nytt Font som använder det angivna befintliga Font och FontStyle‑enumerationen"
type: docs
weight: 10
url: /sv/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

Initierar ett nytt [`Font`](../) som använder det angivna befintliga [`Font`](../) och [`FontStyle`](../../fontstyle/)‑enumerationen.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prototype | Font | Det befintliga [`Font`](../) som den nya [`Font`](../) ska skapas från. |
| newStyle | FontStyle | Den [`FontStyle`](../../fontstyle/) som ska tillämpas på det nya [`Font`](../). Flera värden i [`FontStyle`](../../fontstyle/)‑enumerationen kan kombineras med OR‑operatorn. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | *prototype* är null. |

### Se även

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Initierar ett nytt [`Font`](../) med en angiven storlek. Teckenuppsättningen sätts till Default, grafik‑enheten till Point, teckensnittsstilen till Regular.

```csharp
public Font(string fontName, float emSize)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av namnet på [`Font`](../). |
| emSize | Single | Em-storleken, i punkter, för det nya teckensnittet. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, utvärderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är null. |

### Se även

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Initierar ett nytt [`Font`](../) med en angiven storlek och stil. Teckenuppsättningen sätts till Default, grafik‑enheten till Point.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av namnet på [`Font`](../). |
| emSize | Single | Em-storleken, i punkter, för det nya teckensnittet. |
| style | FontStyle | Den [`FontStyle`](../../fontstyle/) för det nya teckensnittet. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, utvärderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är null. |

### Se även

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Initierar ett nytt [`Font`](../) med en angiven storlek och enhet. Teckenuppsättningen sätts till Default, stilen sätts till Regular.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av namnet på [`Font`](../). |
| emSize | Single | Em-storleken för det nya teckensnittet i de enheter som anges av parametern *unit*. |
| unit | GraphicsUnit | Den [`GraphicsUnit`](../../graphicsunit/) för det nya teckensnittet. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, utvärderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är null. |

### Se även

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Initierar ett nytt [`Font`](../) med en angiven storlek, stil, enhet och teckenuppsättning.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av namnet på [`Font`](../). |
| emSize | Single | Em-storleken för det nya teckensnittet i de enheter som anges av parametern *unit*. |
| style | FontStyle | Den [`FontStyle`](../../fontstyle/) för det nya teckensnittet. |
| unit | GraphicsUnit | Den [`GraphicsUnit`](../../graphicsunit/) för det nya teckensnittet. |
| characterSet | CharacterSet | En teckenuppsättning att använda för detta teckensnitt. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, utvärderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är null. |

### Se även

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Initierar ett nytt [`Font`](../) med en angiven storlek, stil och enhet.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | String | En strängrepresentation av namnet på [`Font`](../). |
| emSize | Single | Em-storleken för det nya teckensnittet i de enheter som anges av parametern *unit*. |
| style | FontStyle | Den [`FontStyle`](../../fontstyle/) för det nya teckensnittet. |
| unit | GraphicsUnit | Den [`GraphicsUnit`](../../graphicsunit/) för det nya teckensnittet. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* är mindre än eller lika med 0, utvärderas till oändlighet eller är inte ett giltigt tal. |
| ArgumentNullException | *fontName* är null. |

### Se även

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


