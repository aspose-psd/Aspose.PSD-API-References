---
title: Color.FromArgb
second_title: Référence de l'API Aspose.PSD pour .NET
description: Color méthode. Crée unColor structure à partir dune valeur ARGB 32 bits.
type: docs
weight: 1430
url: /fr/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

Crée un[`Color`](../) structure à partir d'une valeur ARGB 32 bits.

```csharp
public static Color FromArgb(int argb)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| argb | Int32 | Une valeur spécifiant la valeur ARGB 32 bits. |

### Return_Value

Le[`Color`](../) structure créée par cette méthode.

### Voir également

* struct [Color](../)
* espace de noms [Aspose.PSD](../../color/)
* Assemblée [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Crée un[`Color`](../) structure à partir des quatre valeurs du composant ARGB (alpha, rouge, vert et bleu). Bien que cette méthode permette de transmettre une valeur 32 bits pour chaque composant, la valeur de chaque composant est limitée à 8 bits.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| alpha | Int32 | La composante alpha. Les valeurs valides sont comprises entre 0 et 255. |
| red | Int32 | La composante rouge. Les valeurs valides sont comprises entre 0 et 255. |
| green | Int32 | La composante verte. Les valeurs valides sont comprises entre 0 et 255. |
| blue | Int32 | Le composant bleu. Les valeurs valides sont comprises entre 0 et 255. |

### Return_Value

Le[`Color`](../) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , ou*blue* est inférieur à 0 ou supérieur à 255. |

### Voir également

* struct [Color](../)
* espace de noms [Aspose.PSD](../../color/)
* Assemblée [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Crée un[`Color`](../) structure du spécifié[`Color`](../) structure, mais avec la nouvelle valeur alpha spécifiée. Bien que cette méthode permette de transmettre une valeur 32 bits pour la valeur alpha, la valeur est limitée à 8 bits.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| alpha | Int32 | La valeur alpha du nouveau[`Color`](../). Les valeurs valides sont comprises entre 0 et 255. |
| baseColor | Color | Le[`Color`](../) à partir de laquelle créer le nouveau[`Color`](../). |

### Return_Value

Le[`Color`](../) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* est inférieur à 0 ou supérieur à 255. |

### Voir également

* struct [Color](../)
* espace de noms [Aspose.PSD](../../color/)
* Assemblée [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Crée un[`Color`](../) structure à partir des valeurs de couleur 8 bits spécifiées (rouge, vert et bleu). La valeur alpha est implicitement 255 (entièrement opaque). Bien que cette méthode permette de transmettre une valeur de 32 bits pour chaque composant de couleur, la valeur de chaque composant est limitée à 8 bits.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| red | Int32 | La valeur du composant rouge pour le nouveau[`Color`](../). Les valeurs valides sont comprises entre 0 et 255. |
| green | Int32 | La valeur du composant vert pour le nouveau[`Color`](../). Les valeurs valides sont comprises entre 0 et 255. |
| blue | Int32 | La valeur du composant bleu pour le nouveau[`Color`](../). Les valeurs valides sont comprises entre 0 et 255. |

### Return_Value

Le[`Color`](../) que cette méthode crée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , ou*blue* est inférieur à 0 ou supérieur à 255. |

### Voir également

* struct [Color](../)
* espace de noms [Aspose.PSD](../../color/)
* Assemblée [Aspose.PSD](../../../)


