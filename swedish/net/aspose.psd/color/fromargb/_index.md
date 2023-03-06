---
title: Color.FromArgb
second_title: Aspose.PSD för .NET API-referens
description: Color metod. Skapar enColor struktur från ett 32bitars ARGBvärde.
type: docs
weight: 1430
url: /sv/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

Skapar en[`Color`](../) struktur från ett 32-bitars ARGB-värde.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb | Int32 | Ett värde som anger 32-bitars ARGB-värdet. |

### Returvärde

De[`Color`](../) struktur som denna metod skapar.

### Se även

* struct [Color](../)
* namnutrymme [Aspose.PSD](../../color/)
* hopsättning [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Skapar en[`Color`](../) struktur från de fyra ARGB-komponentvärdena (alfa, röd, grön och blå). Även om denna metod tillåter att ett 32-bitars värde skickas för varje komponent, är värdet för varje komponent begränsat till 8 bitar.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | Int32 | Alfakomponenten. Giltiga värden är 0 till 255. |
| red | Int32 | Den röda komponenten. Giltiga värden är 0 till 255. |
| green | Int32 | Den gröna komponenten. Giltiga värden är 0 till 255. |
| blue | Int32 | Den blå komponenten. Giltiga värden är 0 till 255. |

### Returvärde

De[`Color`](../) som denna metod skapar.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , eller*blue* är mindre än 0 eller större än 255. |

### Se även

* struct [Color](../)
* namnutrymme [Aspose.PSD](../../color/)
* hopsättning [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Skapar en[`Color`](../) struktur från den angivna[`Color`](../) struktur, men med det nya angivna alfavärdet. Även om den här metoden tillåter att ett 32-bitars värde skickas för alfavärdet, är värdet begränsat till 8 bitar.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha | Int32 | Alfavärdet för det nya[`Color`](../). Giltiga värden är 0 till 255. |
| baseColor | Color | De[`Color`](../) varifrån man skapar det nya[`Color`](../). |

### Returvärde

De[`Color`](../) som denna metod skapar.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* är mindre än 0 eller större än 255. |

### Se även

* struct [Color](../)
* namnutrymme [Aspose.PSD](../../color/)
* hopsättning [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Skapar en[`Color`](../) struktur från de angivna 8-bitars färgvärdena (röd, grön och blå). Alfavärdet är implicit 255 (helt ogenomskinligt). Även om denna metod tillåter att ett 32-bitars värde skickas för varje färgkomponent, är värdet för varje komponent begränsat till 8 bitar.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| red | Int32 | Det röda komponentvärdet för den nya[`Color`](../). Giltiga värden är 0 till 255. |
| green | Int32 | Det gröna komponentvärdet för den nya[`Color`](../). Giltiga värden är 0 till 255. |
| blue | Int32 | Det blå komponentvärdet för den nya[`Color`](../). Giltiga värden är 0 till 255. |

### Returvärde

De[`Color`](../) som denna metod skapar.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , eller*blue* är mindre än 0 eller större än 255. |

### Se även

* struct [Color](../)
* namnutrymme [Aspose.PSD](../../color/)
* hopsättning [Aspose.PSD](../../../)


