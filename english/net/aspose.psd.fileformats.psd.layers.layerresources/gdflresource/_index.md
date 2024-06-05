---
title: Class GdFlResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GdFlResource class. Class GdFlResource. This resource contains information about blending of clipped element
type: docs
weight: 2640
url: /net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---
{{< psd/tize >}}
## GdFlResource class

Class GdFlResource. This resource contains information about blending of clipped element.

```csharp
public class GdFlResource : FillLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [GdFlResource](gdflresource/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/alignwithlayer/) { get; set; } | Gets or sets a value indicating whether [align with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/angle/) { get; set; } | Gets or sets the angle. |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/color/) { get; set; } | Gets the color of the RGB. |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colormodel/) { get; set; } | Color Model - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colorpoints/) { get; set; } | Gets the color points. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/dither/) { get; set; } | Gets or sets a value indicating whether this `GdFlResource` is dither. |
| [GradientInterval](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientinterval/) { get; set; } | Gets or sets the gradient interval. |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientmode/) { get; set; } | Mode for this gradient. Determines 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs". |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientname/) { get; set; } | Gets or sets the name of the gradient. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradienttype/) { get; set; } | Gets or sets the type of the gradient. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/horizontaloffset/) { get; set; } | Gets or sets the horizontal offset. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/length/) { get; } | Gets the layer resource length in bytes. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/maximumcolor/) { get; set; } | Maximum color of PixelDataFormat. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/minimumcolor/) { get; set; } | Minimum color of PixelDataFormat. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/reverse/) { get; set; } | Gets or sets a value indicating whether this `GdFlResource` is reverse. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/rndnumberseed/) { get; set; } | The random number seed used to generate colors for Noise gradient. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/roughness/) { get; set; } | Roughness factor. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/scale/) { get; set; } | Gets or sets the scale. |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/showtransparency/) { get; set; } | Flag for showing transparency. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/signature/) { get; } | Gets the layer resource signature. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/transparencypoints/) { get; set; } | Gets the transparency points. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/usevectorcolor/) { get; set; } | Flag for using vector color. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/verticaloffset/) { get; set; } | Gets or sets the vertical offset. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/typetoolkey/) | The type tool info key. |

## Examples

The following example demonstrates the support of GdFlResource resource loading.

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string exportPath = "ComplexGradientFillLayer_after.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is GdFlResource)
                {
                    // Reading
                    var resource = (GdFlResource)res;
                    if (resource.AlignWithLayer != false ||
                     (Math.Abs(resource.Angle - 45.0) > 0.001) ||
                     resource.Dither != true ||
                     resource.Reverse != false ||
                     resource.Color != Color.Empty ||
                     Math.Abs(resource.HorizontalOffset - (-39)) > 0.001 ||
                     Math.Abs(resource.VerticalOffset - (-5)) > 0.001 ||
                     resource.TransparencyPoints.Length != 3 ||
                     resource.ColorPoints.Length != 2)
                    {
                        throw new Exception("Resource Parameters were read wrong");
                    }
                    var transparencyPoints = resource.TransparencyPoints;
                    if (Math.Abs(100.0 - transparencyPoints[0].Opacity) > 0.25 ||
                     transparencyPoints[0].Location != 0 ||
                     transparencyPoints[0].MedianPointLocation != 50 ||
                     Math.Abs(50.0 - transparencyPoints[1].Opacity) > 0.25 ||
                     transparencyPoints[1].Location != 2048 ||
                     transparencyPoints[1].MedianPointLocation != 50 ||
                     Math.Abs(100.0 - transparencyPoints[2].Opacity) > 0.25 ||
                     transparencyPoints[2].Location != 4096 ||
                     transparencyPoints[2].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Transparency Points were read Wrong");
                    }
                    var colorPoints = resource.ColorPoints;
                    if (colorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
                     colorPoints[0].Location != 0 ||
                     colorPoints[0].MedianPointLocation != 50 ||
                     colorPoints[1].Color != Color.FromArgb(203, 0, 0) ||
                     colorPoints[1].Location != 4096 ||
                     colorPoints[1].MedianPointLocation != 50)
                    {
                        throw new Exception("Gradient Color Points were read Wrong");
                    }
                    // Editing
                    resource.Angle = 30.0;
                    resource.Dither = false;
                    resource.AlignWithLayer = true;
                    resource.Reverse = true;
                    resource.HorizontalOffset = 25;
                    resource.VerticalOffset = -15;
                    var newColorPoints = new List<IGradientColorPoint>(resource.ColorPoints);
                    var
                     newTransparencyPoints = new
                    List<IGradientTransparencyPoint>(resource.TransparencyPoints);
                    newColorPoints.Add(new GradientColorPoint()
                    {
                        Color = Color.Violet,
                        Location = 4096,
                        MedianPointLocation = 75
                    });
                    colorPoints[1].Location = 3000;
                    newTransparencyPoints.Add(new GradientTransparencyPoint()
                    {
                        Opacity = 80.0,
                        Location = 4096,
                        MedianPointLocation = 25
                    });
                    transparencyPoints[2].Location = 3000;
                    resource.ColorPoints = newColorPoints.ToArray();
                    resource.TransparencyPoints = newTransparencyPoints.ToArray();
                    im.Save(exportPath);
                }
                break;
            }
            break;
        }
    }
}
```

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


