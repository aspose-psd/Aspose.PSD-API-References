---
title: Color.FromArgb
second_title: Aspose.PSD für .NET-API-Referenz
description: Color methode. Erstellt einColor Struktur aus einem 32BitARGBWert.
type: docs
weight: 1430
url: /de/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

Erstellt ein[`Color`](../) Struktur aus einem 32-Bit-ARGB-Wert.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb | Int32 | Ein Wert, der den 32-Bit-ARGB-Wert angibt. |

### Rückgabewert

Der[`Color`](../) Struktur, die diese Methode erzeugt.

### Siehe auch

* struct [Color](../)
* namensraum [Aspose.PSD](../../color/)
* Montage [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Erstellt ein[`Color`](../) Struktur aus den vier Werten der ARGB-Komponenten (Alpha, Rot, Grün und Blau). Obwohl diese Methode die Übergabe eines 32-Bit-Werts für jede Komponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha | Int32 | Die Alpha-Komponente. Gültige Werte sind 0 bis 255. |
| red | Int32 | Die rote Komponente. Gültige Werte sind 0 bis 255. |
| green | Int32 | Die grüne Komponente. Gültige Werte sind 0 bis 255. |
| blue | Int32 | Die blaue Komponente. Gültige Werte sind 0 bis 255. |

### Rückgabewert

Der[`Color`](../) die diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , oder*blue* kleiner als 0 oder größer als 255 ist. |

### Siehe auch

* struct [Color](../)
* namensraum [Aspose.PSD](../../color/)
* Montage [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Erstellt ein[`Color`](../) Struktur aus der angegebenen[`Color`](../) Struktur, aber mit dem neu festgelegten Alpha-Wert. Obwohl diese Methode die Übergabe eines 32-Bit-Werts für den Alphawert zulässt, ist der Wert auf 8 Bit begrenzt.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha | Int32 | Der Alpha-Wert für das Neue[`Color`](../). Gültige Werte sind 0 bis 255. |
| baseColor | Color | Der[`Color`](../) aus der das Neue entsteht[`Color`](../). |

### Rückgabewert

Der[`Color`](../) die diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* kleiner als 0 oder größer als 255 ist. |

### Siehe auch

* struct [Color](../)
* namensraum [Aspose.PSD](../../color/)
* Montage [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Erstellt ein[`Color`](../) Struktur aus den angegebenen 8-Bit-Farbwerten (Rot, Grün und Blau). Der Alpha-Wert ist implizit 255 (vollständig undurchsichtig). Obwohl diese Methode die Übergabe eines 32-Bit-Werts für jede Farbkomponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| red | Int32 | Der rote Komponentenwert für das Neue[`Color`](../). Gültige Werte sind 0 bis 255. |
| green | Int32 | Der grüne Komponentenwert für den Neuen[`Color`](../). Gültige Werte sind 0 bis 255. |
| blue | Int32 | Der blaue Komponentenwert für das Neue[`Color`](../). Gültige Werte sind 0 bis 255. |

### Rückgabewert

Der[`Color`](../) die diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , oder*blue* kleiner als 0 oder größer als 255 ist. |

### Siehe auch

* struct [Color](../)
* namensraum [Aspose.PSD](../../color/)
* Montage [Aspose.PSD](../../../)


