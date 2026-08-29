---
title: "Font.Font"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Font-Konstruktor. Initialisiert einen neuen Font, der den angegebenen vorhandenen Font und die FontStyle-Aufzählung verwendet."
type: docs
weight: 10
url: /de/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

Initialisiert einen neuen [`Font`](../), der den angegebenen vorhandenen [`Font`](../) und die [`FontStyle`](../../fontstyle/)-Aufzählung verwendet.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prototype | Font | Der vorhandene [`Font`](../), aus dem der neue [`Font`](../) erstellt wird. |
| newStyle | FontStyle | Der [`FontStyle`](../../fontstyle/), der auf den neuen [`Font`](../) angewendet wird. Mehrere Werte der [`FontStyle`](../../fontstyle/)-Aufzählung können mit dem ODER-Operator kombiniert werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *prototype* ist null. |

### Siehe auch

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Initialisiert einen neuen [`Font`](../) mit einer angegebenen Größe. Der Zeichensatz wird auf Default, die Grafikeinheit auf Point und der Font-Stil auf Regular gesetzt.

```csharp
public Font(string fontName, float emSize)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenkettenrepräsentation des [`Font`](../)-Namens. |
| emSize | Single | Die Em-Größe des neuen Fonts in Punkten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* ist kleiner oder gleich 0, ergibt unendlich oder ist keine gültige Zahl. |
| ArgumentNullException | *fontName* ist null. |

### Siehe auch

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Initialisiert einen neuen [`Font`](../) mit einer angegebenen Größe und einem Stil. Der Zeichensatz wird auf Default und die Grafikeinheit auf Point gesetzt.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenkettenrepräsentation des [`Font`](../)-Namens. |
| emSize | Single | Die Em-Größe des neuen Fonts in Punkten. |
| style | FontStyle | Der [`FontStyle`](../../fontstyle/) des neuen Fonts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* ist kleiner oder gleich 0, ergibt unendlich oder ist keine gültige Zahl. |
| ArgumentNullException | *fontName* ist null. |

### Siehe auch

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Initialisiert einen neuen [`Font`](../) mit einer angegebenen Größe und Einheit. Der Zeichensatz wird auf Default und der Stil auf Regular gesetzt.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenkettenrepräsentation des [`Font`](../)-Namens. |
| emSize | Single | Die Em-Größe des neuen Fonts in den durch den *unit*-Parameter angegebenen Einheiten. |
| unit | GraphicsUnit | Der [`GraphicsUnit`](../../graphicsunit/) des neuen Fonts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* ist kleiner oder gleich 0, ergibt unendlich oder ist keine gültige Zahl. |
| ArgumentNullException | *fontName* ist null. |

### Siehe auch

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Initialisiert ein neues [`Font`](../) mit einer angegebenen Größe, einem Stil, einer Einheit und einem Zeichensatz.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenkettenrepräsentation des [`Font`](../)-Namens. |
| emSize | Single | Die Em-Größe des neuen Fonts in den durch den *unit*-Parameter angegebenen Einheiten. |
| style | FontStyle | Der [`FontStyle`](../../fontstyle/) des neuen Fonts. |
| unit | GraphicsUnit | Der [`GraphicsUnit`](../../graphicsunit/) des neuen Fonts. |
| characterSet | CharacterSet | Ein Zeichensatz, der für diese Schriftart verwendet wird. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* ist kleiner oder gleich 0, ergibt unendlich oder ist keine gültige Zahl. |
| ArgumentNullException | *fontName* ist null. |

### Siehe auch

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Initialisiert ein neues [`Font`](../) mit einer angegebenen Größe, einem Stil und einer Einheit.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Eine Zeichenkettenrepräsentation des [`Font`](../)-Namens. |
| emSize | Single | Die Em-Größe des neuen Fonts in den durch den *unit*-Parameter angegebenen Einheiten. |
| style | FontStyle | Der [`FontStyle`](../../fontstyle/) des neuen Fonts. |
| unit | GraphicsUnit | Der [`GraphicsUnit`](../../graphicsunit/) des neuen Fonts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* ist kleiner oder gleich 0, ergibt unendlich oder ist keine gültige Zahl. |
| ArgumentNullException | *fontName* ist null. |

### Siehe auch

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


