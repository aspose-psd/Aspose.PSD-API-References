---
title: "Classe CmxRasterizationOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.ImageOptions.CmxRasterizationOptions classe. les options d'exportation CMX"
type: docs
weight: 5290
url: /fr/net/aspose.psd.imageoptions/cmxrasterizationoptions/
---
{{< psd/tize >}}
## CmxRasterizationOptions class

Les options de l'exportateur CMX.

```csharp
public class CmxRasterizationOptions : VectorRasterizationOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [CmxRasterizationOptions](cmxrasterizationoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | Obtient ou définit une couleur d'arrière-plan. |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | Obtient ou définit la bordure X. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | Obtient ou définit la bordure Y. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | Obtient ou définit une valeur indiquant si le dessin est centré. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner le texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système). Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | Obtient ou définit une couleur de premier plan. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtient ou définit une valeur indiquant si [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Les options multipages |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | Obtient ou définit la hauteur de la page. |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | Obtient ou définit la taille de la page. |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | Obtient ou définit la largeur de la page. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtient ou définit la palette de couleurs. |
| [Positioning](../../aspose.psd.imageoptions/cmxrasterizationoptions/positioning/) { get; set; } | Obtient ou définit le positionnement. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événement de progression. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtient ou définit les paramètres de résolution. |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | Obtient ou définit le mode d'anticrénelage. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtient ou définit la source dans laquelle créer l'image. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | Obtient ou définit l'indice de rendu du texte. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtient ou définit les options de rasterisation vectorielle. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Obtient ou définit le conteneur de métadonnées XMP. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clone cette instance. |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | Copie vers. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |

### Voir aussi

* class [VectorRasterizationOptions](../vectorrasterizationoptions/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


