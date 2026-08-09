---
title: "Graphics.DrawString"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Graphics. Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets Brush et Font spécifiés."
type: docs
weight: 330
url: /fr/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [`Brush`](../../brush/) et [`Font`](../../font/) spécifiés.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format du texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | Single | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | Single | La coordonnée y du coin supérieur gauche du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir aussi

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [`Brush`](../../brush/) et [`Font`](../../font/) spécifiés.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format du texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | PointF | Structure [`PointF`](../../pointf/) qui spécifie le coin supérieur gauche du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

## Exemples

Cet exemple montre l'utilisation des classes Font et SolidBrush pour dessiner des chaînes sur la surface Image. L'exemple crée une nouvelle Image et dessine des formes à l'aide de Figures et de GraphicsPath

```csharp
[C#]

//Crée une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crée et initialise une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics
    graphics.Clear(Color.Wheat);

    //Crée une instance de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crée une instance de SolidBrush avec la couleur rouge
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Dessine une chaîne
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crée des options d'exportation.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // enregistrez toutes les modifications
    image.Save("C:\\temp\\output.gif", options);
}
```

### Voir aussi

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [`Brush`](../../brush/) et [`Font`](../../font/) en utilisant les attributs de formatage du [`StringFormat`](../../stringformat/) spécifié.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format du texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | Single | La coordonnée x du coin supérieur gauche du texte dessiné. |
| y | Single | La coordonnée y du coin supérieur gauche du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat/) qui spécifie les attributs de formatage, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir aussi

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec les objets [`Brush`](../../brush/) et [`Font`](../../font/) en utilisant les attributs de formatage du [`StringFormat`](../../stringformat/) spécifié.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format du texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | PointF | Structure [`PointF`](../../pointf/) qui spécifie le coin supérieur gauche du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat/) qui spécifie les attributs de formatage, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir aussi

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets [`Brush`](../../brush/) et [`Font`](../../font/) spécifiés.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format du texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | RectangleF | Structure [`RectangleF`](../../rectanglef/) qui spécifie l'emplacement du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir aussi

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec les objets [`Brush`](../../brush/) et [`Font`](../../font/) en utilisant les attributs de formatage du [`StringFormat`](../../stringformat/) spécifié.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format du texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | RectangleF | Structure [`RectangleF`](../../rectanglef/) qui spécifie l'emplacement du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat/) qui spécifie les attributs de formatage, tels que l'espacement des lignes et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. -ou- *brush* est nul. |

### Voir aussi

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


