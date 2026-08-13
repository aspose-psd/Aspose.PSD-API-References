---
title: "Énumération StringFormatFlags"
type: docs
weight: 6300
url: /fr/python-net/aspose.psd/stringformatflags/
---

Spécifie les informations d'affichage et de mise en page pour les chaînes de texte.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormatFlags

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Le texte est affiché de droite à gauche. |
| DIRECTION_VERTICAL | Le texte est aligné verticalement. |
| DISPLAY_FORMAT_CONTROL | Les caractères de contrôle tels que la marque de gauche à droite sont affichés dans la sortie avec un glyphe représentatif. |
| EXACT_ALIGNMENT | L'alignement exact, remplissage correct GDI+ |
| FIT_BLACK_BOX | Les parties de caractères peuvent dépasser le rectangle de mise en page de la chaîne. Par défaut, les caractères sont repositionnés pour éviter tout dépassement. |
| LINE_LIMIT | Seules les lignes complètes sont disposées dans le rectangle de formatage. Par défaut, la mise en page continue jusqu'à la fin du texte, ou jusqu'à ce qu'aucune ligne supplémentaire ne soit visible à cause du rognage, selon la première condition qui se produit.<br/>            Notez que les paramètres par défaut permettent à la dernière ligne d'être partiellement masquée par un rectangle de formatage qui n'est pas un multiple entier de la hauteur de ligne. Pour garantir que seules des lignes entières soient visibles,<br/>            spécifiez cette valeur et veillez à fournir un rectangle de formatage d'au moins la hauteur d'une ligne. |
| MEASURE_TRAILING_SPACES | Inclut l'espace de fin à la fin de chaque ligne. Par défaut, le rectangle de délimitation renvoyé par la méthode MeasureString exclut l'espace à la fin de chaque ligne. Activez ce drapeau pour inclure cet espace dans la mesure. |
| NO_CLIP | Les parties dépassant des glyphes, ainsi que le texte non enveloppé qui dépasse le rectangle de formatage, sont autorisés à s'afficher. Par défaut, tout texte et toute partie de glyphe dépassant le rectangle de formatage sont rognés. |
| NO_FONT_FALLBACK | Le recours à des polices alternatives pour les caractères non pris en charge par la police demandée est désactivé. Tout caractère manquant est affiché avec le glyphe manquant de la police, généralement un carré ouvert. |
| NO_WRAP | Le retour à la ligne du texte entre les lignes lors du formatage dans un rectangle est désactivé. Ce drapeau est implicite lorsqu'un point est passé au lieu d'un rectangle, ou lorsque le rectangle spécifié a une longueur de ligne nulle. |
