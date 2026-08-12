---
title: "Color.FromArgb"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Color-metod. Skapar en Color-struktur från ett 32‑bit ARGB‑värde"
type: docs
weight: 1430
url: /sv/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

Skapar en [`Color`](../) struktur från ett 32‑bit ARGB‑värde.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | Int32 | Ett värde som specificerar det 32‑bit ARGB‑värdet. |

### Returvärde

Den [`Color`](../) struktur som denna metod skapar.

### Se även

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Skapar en [`Color`](../)-struktur från de fyra ARGB-komponenterna (alpha, röd, grön och blå) värdena. Även om den här metoden tillåter ett 32‑bit‑värde att skickas för varje komponent, är värdet för varje komponent begränsat till 8 bitar.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | Int32 | Alfakomponenten. Giltiga värden är 0 till 255. |
| röd | Int32 | Rödkomponenten. Giltiga värden är 0 till 255. |
| grön | Int32 | Grönkomponenten. Giltiga värden är 0 till 255. |
| blå | Int32 | Blåkomponenten. Giltiga värden är 0 till 255. |

### Returvärde

Den [`Color`](../) som denna metod skapar.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *röd*, *grön* eller *blå* är mindre än 0 eller större än 255. |

### Se även

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Skapar en [`Color`](../)-struktur från den angivna [`Color`](../)-strukturen, men med det nya angivna alfavärdet. Även om den här metoden tillåter ett 32‑bit‑värde att skickas för alfavärdet, är värdet begränsat till 8 bitar.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | Int32 | Alfavärdet för den nya [`Color`](../). Giltiga värden är 0 till 255. |
| baseColor | Color | Den [`Color`](../) som ska användas för att skapa den nya [`Color`](../). |

### Returvärde

Den [`Color`](../) som denna metod skapar.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* är mindre än 0 eller större än 255. |

### Se även

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Skapar en [`Color`](../)-struktur från de angivna 8‑bitars färgvärdena (röd, grön och blå). Alfavärdet är implicit 255 (fullt ogenomskinligt). Även om den här metoden tillåter ett 32‑bit‑värde att skickas för varje färgkomponent, är värdet för varje komponent begränsat till 8 bitar.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| red | Int32 | Rödkomponentens värde för den nya [`Color`](../). Giltiga värden är 0 till 255. |
| green | Int32 | Grönkomponentens värde för den nya [`Color`](../). Giltiga värden är 0 till 255. |
| blue | Int32 | Blåkomponentens värde för den nya [`Color`](../). Giltiga värden är 0 till 255. |

### Returvärde

Den [`Color`](../) som denna metod skapar.

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentOutOfRangeException | *röd*, *grön* eller *blå* är mindre än 0 eller större än 255. |

### Se även

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


