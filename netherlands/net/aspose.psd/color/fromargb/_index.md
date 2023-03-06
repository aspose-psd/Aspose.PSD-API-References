---
title: Color.FromArgb
second_title: Aspose.PSD voor .NET API-referentie
description: Color methode. Creëert eenColor structuur van een 32bits ARGBwaarde.
type: docs
weight: 1430
url: /nl/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

Creëert een[`Color`](../) structuur van een 32-bits ARGB-waarde.

```csharp
public static Color FromArgb(int argb)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb | Int32 | Een waarde die de 32-bits ARGB-waarde specificeert. |

### Winstwaarde

De[`Color`](../) structuur die deze methode creëert.

### Zie ook

* struct [Color](../)
* naamruimte [Aspose.PSD](../../color/)
* montage [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Creëert een[`Color`](../) structuur van de vier ARGB-componentwaarden (alfa, rood, groen en blauw). Hoewel met deze methode een 32-bits waarde voor elke component kan worden doorgegeven, is de waarde van elke component beperkt tot 8 bits.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | Int32 | De alfa-component. Geldige waarden zijn 0 tot en met 255. |
| red | Int32 | Het rode bestanddeel. Geldige waarden zijn 0 tot en met 255. |
| green | Int32 | De groene component. Geldige waarden zijn 0 tot en met 255. |
| blue | Int32 | Het blauwe onderdeel. Geldige waarden zijn 0 tot en met 255. |

### Winstwaarde

De[`Color`](../) die deze methode creëert.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , of*blue* is kleiner dan 0 of groter dan 255. |

### Zie ook

* struct [Color](../)
* naamruimte [Aspose.PSD](../../color/)
* montage [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Creëert een[`Color`](../) structuur van de opgegeven[`Color`](../) structuur, maar met de nieuwe gespecificeerde alfawaarde. Hoewel met deze methode een 32-bits waarde kan worden doorgegeven voor de alpha-waarde, is de waarde beperkt tot 8 bits.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alpha | Int32 | De alfawaarde voor het nieuwe[`Color`](../). Geldige waarden zijn 0 tot en met 255. |
| baseColor | Color | De[`Color`](../) waaruit het nieuwe ontstaat[`Color`](../). |

### Winstwaarde

De[`Color`](../) die deze methode creëert.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* is kleiner dan 0 of groter dan 255. |

### Zie ook

* struct [Color](../)
* naamruimte [Aspose.PSD](../../color/)
* montage [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Creëert een[`Color`](../) structuur van de opgegeven 8-bits kleurwaarden (rood, groen en blauw). De alpha-waarde is impliciet 255 (volledig ondoorzichtig). Hoewel met deze methode een 32-bits waarde kan worden doorgegeven voor elke kleurcomponent, is de waarde van elke component beperkt tot 8 bits.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| red | Int32 | De rode componentwaarde voor de nieuwe[`Color`](../). Geldige waarden zijn 0 tot en met 255. |
| green | Int32 | De groene componentwaarde voor de nieuwe[`Color`](../). Geldige waarden zijn 0 tot en met 255. |
| blue | Int32 | De blauwe componentwaarde voor de nieuwe[`Color`](../). Geldige waarden zijn 0 tot en met 255. |

### Winstwaarde

De[`Color`](../) die deze methode creëert.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , of*blue* is kleiner dan 0 of groter dan 255. |

### Zie ook

* struct [Color](../)
* naamruimte [Aspose.PSD](../../color/)
* montage [Aspose.PSD](../../../)


