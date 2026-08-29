---
title: "Color.FromArgb"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Color method. Erstellt eine Color-Struktur aus einem 32‑Bit‑ARGB‑Wert"
type: docs
weight: 1430
url: /de/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

Erstellt eine [`Color`](../)-Struktur aus einem 32‑Bit‑ARGB‑Wert.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb | Int32 | Ein Wert, der den 32‑Bit‑ARGB‑Wert angibt. |

### Rückgabewert

Die [`Color`](../)-Struktur, die diese Methode erstellt.

### Siehe auch

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Erstellt eine [`Color`](../)-Struktur aus den vier ARGB-Komponenten (Alpha, Rot, Grün und Blau). Obwohl diese Methode einen 32‑Bit‑Wert für jede Komponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Alpha | Int32 | Die Alpha‑Komponente. Gültige Werte sind 0 bis 255. |
| rot | Int32 | Die Rot‑Komponente. Gültige Werte sind 0 bis 255. |
| grün | Int32 | Die Grün‑Komponente. Gültige Werte sind 0 bis 255. |
| blau | Int32 | Die Blau‑Komponente. Gültige Werte sind 0 bis 255. |

### Rückgabewert

Das [`Color`](../), das diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *Alpha*, *Rot*, *Grün* oder *Blau* ist kleiner als 0 oder größer als 255. |

### Siehe auch

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Erstellt eine [`Color`](../)-Struktur aus der angegebenen [`Color`](../)-Struktur, jedoch mit dem neu angegebenen Alpha‑Wert. Obwohl diese Methode einen 32‑Bit‑Wert für den Alpha‑Wert zulässt, ist der Wert auf 8 Bit begrenzt.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha | Int32 | Der Alpha‑Wert für das neue [`Color`](../). Gültige Werte sind 0 bis 255. |
| baseColor | Color | Das [`Color`](../), aus dem das neue [`Color`](../) erstellt wird. |

### Rückgabewert

Das [`Color`](../), das diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *Alpha* ist kleiner als 0 oder größer als 255. |

### Siehe auch

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Erstellt eine [`Color`](../)-Struktur aus den angegebenen 8‑Bit‑Farbwerten (Rot, Grün und Blau). Der Alpha‑Wert ist implizit 255 (vollständig undurchsichtig). Obwohl diese Methode einen 32‑Bit‑Wert für jede Farbkomponente zulässt, ist der Wert jeder Komponente auf 8 Bit begrenzt.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| red | Int32 | Der Rot‑Komponentenwert für das neue [`Color`](../). Gültige Werte sind 0 bis 255. |
| green | Int32 | Der Grün‑Komponentenwert für das neue [`Color`](../). Gültige Werte sind 0 bis 255. |
| blue | Int32 | Der Blau‑Komponentenwert für das neue [`Color`](../). Gültige Werte sind 0 bis 255. |

### Rückgabewert

Das [`Color`](../), das diese Methode erstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentOutOfRangeException | *Rot*, *Grün* oder *Blau* ist kleiner als 0 oder größer als 255. |

### Siehe auch

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


