---
title: Image.Resize
second_title: Référence de l'API Aspose.PSD pour .NET
description: Image méthode. Redimensionne limage.
type: docs
weight: 190
url: /fr/net/aspose.psd/image/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Redimensionne l'image.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| resizeType | ResizeType | Le type de redimensionnement. |

### Voir également

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* espace de noms [Aspose.PSD](../../image/)
* Assemblée [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Redimensionne l'image. Le défautLeftTopToLeftTopest utilisé.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |

### Exemples

L'exemple suivant montre comment redimensionner l'image PSD et le résultat que nous obtenons avec Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir également

* class [Image](../)
* espace de noms [Aspose.PSD](../../image/)
* Assemblée [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Redimensionne l'image.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| settings | ImageResizeSettings | Les paramètres de redimensionnement. |

### Voir également

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* espace de noms [Aspose.PSD](../../image/)
* Assemblée [Aspose.PSD](../../../)


