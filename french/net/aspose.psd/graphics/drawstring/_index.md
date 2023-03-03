---
title: Graphics.DrawString
second_title: Référence de l'API Aspose.PSD pour .NET
description: Graphics méthode. Dessine la chaîne de texte spécifiée à lemplacement spécifié avec leBrush etFont objets.
type: docs
weight: 320
url: /fr/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../../brush/) et[`Font`](../../font/) objets.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | Single | Coordonnée x du coin supérieur gauche du texte dessiné. |
| y | Single | Coordonnée y du coin supérieur gauche du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir également

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../../brush/) et[`Font`](../../font/) objets.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | PointF | [`PointF`](../../pointf/) structure qui spécifie le coin supérieur gauche du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Exemples

Cet exemple illustre l'utilisation des classes Font et SolidBrush pour dessiner des chaînes sur la surface de l'image. L'exemple crée une nouvelle Image et dessine des formes à l'aide de Figures et GraphicsPath

```csharp
[C#]

// Crée une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crée et initialise une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface graphique
    graphics.Clear(Color.Wheat);

    // Crée une instance de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Créer une instance de SolidBrush ayant la couleur rouge
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Dessine une chaîne
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crée les options d'exportation.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // Enregistrer toutes les modifications
    image.Save("C:\\temp\\output.gif", options);
}
```

### Voir également

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../../brush/) et[`Font`](../../font/) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| x | Single | Coordonnée x du coin supérieur gauche du texte dessiné. |
| y | Single | Coordonnée y du coin supérieur gauche du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat/) qui spécifie les attributs de mise en forme, tels que l'interligne et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir également

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Dessine la chaîne de texte spécifiée à l'emplacement spécifié avec le[`Brush`](../../brush/) et[`Font`](../../font/) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| point | PointF | [`PointF`](../../pointf/) structure qui spécifie le coin supérieur gauche du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat/) qui spécifie les attributs de mise en forme, tels que l'interligne et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir également

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le[`Brush`](../../brush/) et[`Font`](../../font/) objets.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) structure qui spécifie l'emplacement du texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. |

### Voir également

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Dessine la chaîne de texte spécifiée dans le rectangle spécifié avec le[`Brush`](../../brush/) et[`Font`](../../font/) objets utilisant les attributs de mise en forme du spécifié[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| s | String | Chaîne à dessiner. |
| font | Font | [`Font`](../../font/) qui définit le format de texte de la chaîne. |
| brush | Brush | [`Brush`](../../brush/) qui détermine la couleur et la texture du texte dessiné. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) structure qui spécifie l'emplacement du texte dessiné. |
| format | StringFormat | [`StringFormat`](../../stringformat/) qui spécifie les attributs de mise en forme, tels que l'interligne et l'alignement, qui sont appliqués au texte dessiné. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *brush* est nul. -ou- *s* est nul. -ou- *brush* est nul. |

### Voir également

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* espace de noms [Aspose.PSD](../../graphics/)
* Assemblée [Aspose.PSD](../../../)


