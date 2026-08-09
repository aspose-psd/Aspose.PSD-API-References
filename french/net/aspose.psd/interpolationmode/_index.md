---
title: "Enum InterpolationMode"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Enum Aspose.PSD.InterpolationMode. L'énumération InterpolationMode spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou pivotées"
type: docs
weight: 5520
url: /fr/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

L'énumération `InterpolationMode` spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou pivotées.

```csharp
public enum InterpolationMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Invalid | `-1` | Mode d'interpolation invalide. |
| Default | `0` | Spécifie le mode par défaut. |
| Low | `1` | Spécifie une interpolation de basse qualité. |
| High | `2` | Spécifie une interpolation de haute qualité. |
| Bilinear | `3` | Spécifie une interpolation bilinéaire. Aucun préfiltrage n'est effectué. Ce mode n'est pas adapté à la réduction d'une image à moins de 50 % de sa taille originale. |
| Bicubic | `4` | Spécifie une interpolation bicubique. Aucun préfiltrage n'est effectué. Ce mode n'est pas adapté à la réduction d'une image à moins de 25 % de sa taille originale. |
| NearestNeighbor | `5` | Spécifie une interpolation du plus proche voisin. |
| HighQualityBilinear | `6` | Spécifie une interpolation bilinéaire de haute qualité. Un préfiltrage est effectué pour garantir une réduction de haute qualité. |
| HighQualityBicubic | `7` | Spécifie une interpolation bicubique de haute qualité. Un préfiltrage est effectué pour garantir une réduction de haute qualité. Ce mode produit les images transformées de la plus haute qualité. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


