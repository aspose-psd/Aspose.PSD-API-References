---
title: Font.Font
second_title: Aspose.PSD für .NET-API-Referenz
description: Font constructeur. Initialisiert eine neueFont die die angegebene vorhandene verwendetFont UndFontStyle Aufzählung.
type: docs
weight: 10
url: /de/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Initialisiert eine neue[`Font`](../) die die angegebene vorhandene verwendet[`Font`](../) Und[`FontStyle`](../../fontstyle/) Aufzählung.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prototype | Font | Die bestehende[`Font`](../) aus der das Neue entsteht[`Font`](../). |
| newStyle | FontStyle | Der[`FontStyle`](../../fontstyle/) auf das Neue anwenden[`Font`](../) . Mehrere Werte der[`FontStyle`](../../fontstyle/) Enumeration kann mit dem OR-Operator kombiniert werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *prototype* ist Null. |

### Siehe auch

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namensraum [Aspose.PSD](../../font/)
* Montage [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Initialisiert eine neue[`Font`](../) unter Verwendung einer bestimmten Größe. Der Zeichensatz ist eingestellt aufDefault , die Grafikeinheit anPoint , den Schriftstil zuRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../) Name. |
| emSize | Single | Die Em-Größe der neuen Schriftart in Punkt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* class [Font](../)
* namensraum [Aspose.PSD](../../font/)
* Montage [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Initialisiert eine neue[`Font`](../) unter Verwendung einer bestimmten Größe und eines bestimmten Stils. Der Zeichensatz ist eingestellt aufDefault , die Grafikeinheit anPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../) Name. |
| emSize | Single | Die Em-Größe der neuen Schriftart in Punkt. |
| style | FontStyle | Der[`FontStyle`](../../fontstyle/) der neuen Schriftart. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namensraum [Aspose.PSD](../../font/)
* Montage [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Initialisiert eine neue[`Font`](../) unter Verwendung einer bestimmten Größe und Einheit. Der Zeichensatz ist eingestellt aufDefault der Stil ist eingestellt aufRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../) Name. |
| emSize | Single | Die em-Größe der neuen Schriftart in den von der angegebenen Einheiten*unit* Parameter. |
| unit | GraphicsUnit | Der[`GraphicsUnit`](../../graphicsunit/) der neuen Schriftart. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namensraum [Aspose.PSD](../../font/)
* Montage [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Initialisiert eine neue[`Font`](../) Verwenden einer bestimmten Größe, eines Stils, einer Einheit und eines Zeichensatzes.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../) Name. |
| emSize | Single | Die em-Größe der neuen Schriftart in den von der angegebenen Einheiten*unit* Parameter. |
| style | FontStyle | Der[`FontStyle`](../../fontstyle/) der neuen Schriftart. |
| unit | GraphicsUnit | Der[`GraphicsUnit`](../../graphicsunit/) der neuen Schriftart. |
| characterSet | CharacterSet | Ein für diese Schriftart zu verwendender Zeichensatz. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namensraum [Aspose.PSD](../../font/)
* Montage [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Initialisiert eine neue[`Font`](../) unter Verwendung einer bestimmten Größe, eines Stils und einer Einheit.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenfolgendarstellung der[`Font`](../) Name. |
| emSize | Single | Die em-Größe der neuen Schriftart in den von der angegebenen Einheiten*unit* Parameter. |
| style | FontStyle | Der[`FontStyle`](../../fontstyle/) der neuen Schriftart. |
| unit | GraphicsUnit | Der[`GraphicsUnit`](../../graphicsunit/) der neuen Schriftart. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* kleiner oder gleich 0 ist, zu unendlich ausgewertet wird oder keine gültige Zahl ist. |
| ArgumentNullException | *fontName* ist Null. |

### Siehe auch

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namensraum [Aspose.PSD](../../font/)
* Montage [Aspose.PSD](../../../)


