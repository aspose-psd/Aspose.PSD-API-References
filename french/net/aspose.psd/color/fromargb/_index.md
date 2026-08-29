---
title: "Color.FromArgb"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Color. Crée une structure Color à partir d'une valeur ARGB 32 bits"
type: docs
weight: 1430
url: /fr/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

Crée une structure [`Color`](../) à partir d'une valeur ARGB 32 bits.

```csharp
public static Color FromArgb(int argb)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| argb | Int32 | Une valeur spécifiant la valeur ARGB 32 bits. |

### Valeur de retour

La structure [`Color`](../) que cette méthode crée.

### Voir aussi

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Crée une structure [`Color`](../) à partir des quatre composants ARGB (alpha, red, green, et blue). Bien que cette méthode permette de passer une valeur 32 bits pour chaque composant, la valeur de chaque composant est limitée à 8 bits.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | Int32 | Le composant alpha. Les valeurs valides sont de 0 à 255. |
| rouge | Int32 | Le composant red. Les valeurs valides sont de 0 à 255. |
| vert | Int32 | Le composant green. Les valeurs valides sont de 0 à 255. |
| bleu | Int32 | Le composant blue. Les valeurs valides sont de 0 à 255. |

### Valeur de retour

Le [`Color`](../) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *red*, *green*, ou *blue* est inférieur à 0 ou supérieur à 255. |

### Voir aussi

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Crée une structure [`Color`](../) à partir de la structure [`Color`](../) spécifiée, mais avec la nouvelle valeur alpha spécifiée. Bien que cette méthode permette de passer une valeur de 32 bits pour la valeur alpha, la valeur est limitée à 8 bits.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| alpha | Int32 | La valeur alpha pour le nouveau [`Color`](../). Les valeurs valides sont de 0 à 255. |
| baseColor | Color | Le [`Color`](../) à partir duquel créer le nouveau [`Color`](../). |

### Valeur de retour

Le [`Color`](../) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* est inférieur à 0 ou supérieur à 255. |

### Voir aussi

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Crée une structure [`Color`](../) à partir des valeurs de couleur 8 bits spécifiées (rouge, vert et bleu). La valeur alpha est implicitement 255 (complètement opaque). Bien que cette méthode permette de passer une valeur de 32 bits pour chaque composant de couleur, la valeur de chaque composant est limitée à 8 bits.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| red | Int32 | La valeur du composant rouge pour le nouveau [`Color`](../). Les valeurs valides sont de 0 à 255. |
| green | Int32 | La valeur du composant vert pour le nouveau [`Color`](../). Les valeurs valides sont de 0 à 255. |
| blue | Int32 | La valeur du composant bleu pour le nouveau [`Color`](../). Les valeurs valides sont de 0 à 255. |

### Valeur de retour

Le [`Color`](../) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *red*, *green* ou *blue* est inférieur à 0 ou supérieur à 255. |

### Voir aussi

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


