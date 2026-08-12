---
title: "Clase GdFlResource"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GdFlResource. Clase GdFlResource. Este recurso contiene información sobre la fusión del elemento recortado"
type: docs
weight: 2760
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---
{{< psd/tize >}}
## GdFlResource class

Clase GdFlResource. Este recurso contiene información sobre la fusión del elemento recortado.

```csharp
public class GdFlResource : FillLayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GdFlResource](gdflresource/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/alignwithlayer/) { get; set; } | Obtiene o establece un valor que indica si [align with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/angle/) { get; set; } | Obtiene o establece el ángulo. |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/color/) { get; set; } | Obtiene el color del RGB. |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colormodel/) { get; set; } | Modelo de color - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/colorpoints/) { get; set; } | Obtiene los puntos de color. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/dither/) { get; set; } | Obtiene o establece un valor que indica si este `GdFlResource` está con dithering. |
| [GradientInterval](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientinterval/) { get; set; } | Obtiene o establece el intervalo del gradiente. |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientmode/) { get; set; } | Modo para este gradiente. Determina 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs". |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradientname/) { get; set; } | Obtiene o establece el nombre del degradado. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/gradienttype/) { get; set; } | Obtiene o establece el tipo del degradado. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/horizontaloffset/) { get; set; } | Obtiene o establece el desplazamiento horizontal. |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/interpolationmethod/) { get; set; } | Obtiene o establece el método de interpolación para el degradado. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtiene la clave del recurso de capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/length/) { get; } | Obtiene la longitud del recurso de capa en bytes. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/maximumcolor/) { get; set; } | Color máximo de PixelDataFormat. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/minimumcolor/) { get; set; } | Color mínimo de PixelDataFormat. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtiene la versión mínima de PSD requerida para el recurso de capa. 0 indica que no hay restricciones. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/reverse/) { get; set; } | Obtiene o establece un valor que indica si este `GdFlResource` está invertido. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/rndnumberseed/) { get; set; } | La semilla de número aleatorio utilizada para generar colores para el gradiente Noise. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/roughness/) { get; set; } | Factor de aspereza. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/scale/) { get; set; } | Obtiene o establece la escala. |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/showtransparency/) { get; set; } | Indicador para mostrar transparencia. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtiene la firma. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/transparencypoints/) { get; set; } | Obtiene los puntos de transparencia. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/usevectorcolor/) { get; set; } | Indicador para usar color vectorial. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/verticaloffset/) { get; set; } | Obtiene o establece el desplazamiento vertical. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve una String que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/gdflresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

## Ejemplos

El siguiente ejemplo demuestra el soporte de la carga de recursos GdFlResource.

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
                    // Lectura
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
                    // Edición
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

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


