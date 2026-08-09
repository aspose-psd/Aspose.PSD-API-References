---
title: "Enum TextRenderingHint"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.TextRenderingHint enum. Spécifie la qualité du rendu du texte."
type: docs
weight: 6200
url: /fr/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

Spécifie la qualité du rendu du texte.

```csharp
public enum TextRenderingHint
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| SystemDefault | `0` | Chaque caractère est dessiné en utilisant son bitmap de glyphe, avec l'indice de rendu par défaut du système. Le texte sera dessiné en fonction des paramètres de lissage des polices que l'utilisateur a sélectionnés pour le système. |
| SingleBitPerPixelGridFit | `1` | Chaque caractère est dessiné en utilisant son bitmap de glyphe. Hinting est utilisé pour améliorer l'apparence des caractères sur les tiges et les courbures. |
| SingleBitPerPixel | `2` | Chaque caractère est dessiné en utilisant son bitmap de glyphe. Le hinting n'est pas utilisé. |
| AntiAliasGridFit | `3` | Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé avec hinting. Qualité bien meilleure grâce à l'antialiasing, mais à un coût de performance plus élevé. |
| AntiAlias | `4` | Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé sans hinting. Qualité supérieure grâce à l'antialiasing. Les différences de largeur des tiges peuvent être perceptibles car le hinting est désactivé. |
| ClearTypeGridFit | `5` | Chaque caractère est dessiné en utilisant son bitmap de glyphe ClearType avec hinting. Le réglage de la plus haute qualité. Utilisé pour tirer parti des fonctionnalités de police ClearType. |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


