---
title: "Image.Resize"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode Image. Redimensionne l'image"
type: docs
weight: 200
url: /fr/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Redimensionne l'image.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| resizeType | ResizeType | Le type de redimensionnement. |

### Voir aussi

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Redimensionne l'image. Le redimensionnement par plus proche voisin par défaut est utilisé.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |

## Exemples

L'exemple suivant montre comment redimensionner une image PSD et le résultat obtenu avec Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir aussi

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Redimensionne l'image.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| paramètres | ImageResizeSettings | Les paramètres de redimensionnement. |

### Voir aussi

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


