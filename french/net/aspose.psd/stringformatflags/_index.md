---
title: "Énum StringFormatFlags"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énum Aspose.PSD.StringFormatFlags. Spécifie les informations d’affichage et de mise en page pour les chaînes de texte"
type: docs
weight: 6180
url: /fr/net/aspose.psd/stringformatflags/
---
{{< psd/tize >}}
## StringFormatFlags enumeration

Spécifie les informations d'affichage et de mise en page pour les chaînes de texte.

```csharp
[Flags]
public enum StringFormatFlags
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Le texte est affiché de droite à gauche. |
| DirectionVertical | `2` | Le texte est aligné verticalement. |
| FitBlackBox | `4` | Les parties des caractères peuvent dépasser le rectangle de mise en page de la chaîne. Par défaut, les caractères sont repositionnés pour éviter tout dépassement. |
| DisplayFormatControl | `20` | Les caractères de contrôle tels que le marqueur de gauche à droite sont affichés dans la sortie avec un glyphe représentatif. |
| NoFontFallback | `400` | Le recours à des polices alternatives pour les caractères non pris en charge par la police demandée est désactivé. Tout caractère manquant est affiché avec le glyphe manquant de la police, généralement un carré ouvert. |
| MeasureTrailingSpaces | `800` | Inclut l’espace de fin à la fin de chaque ligne. Par défaut, le rectangle de délimitation renvoyé par la méthode MeasureString exclut l’espace à la fin de chaque ligne. Activez ce drapeau pour inclure cet espace dans la mesure. |
| NoWrap | `1000` | Le retour à la ligne du texte entre les lignes lors du formatage dans un rectangle est désactivé. Ce drapeau est implicite lorsqu’un point est passé au lieu d’un rectangle, ou lorsque le rectangle spécifié a une longueur de ligne nulle. |
| LineLimit | `2000` | Seules les lignes complètes sont disposées dans le rectangle de formatage. Par défaut, la disposition se poursuit jusqu’à la fin du texte, ou jusqu’à ce qu’aucune ligne supplémentaire ne soit visible à cause du rognage, selon la première éventualité. Notez que les paramètres par défaut permettent à la dernière ligne d’être partiellement masquée par un rectangle de formatage qui n’est pas un multiple entier de la hauteur de ligne. Pour garantir que seules les lignes entières soient visibles, spécifiez cette valeur et veillez à fournir un rectangle de formatage d’au moins la hauteur d’une ligne. |
| NoClip | `4000` | Les parties dépassant des glyphes, ainsi que le texte non enveloppé qui dépasse le rectangle de formatage, sont autorisés à s’afficher. Par défaut, tout texte et toute partie de glyphe qui dépasse le rectangle de formatage est rogné. |
| ExactAlignment | `8000` | L’alignement exact, le remplissage correct GDI+ |

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


