---
title: Class VstkResource
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VstkResource clase. Clase de recurso VstkResource. Contiene información sobre Vector Stroke Data. El recurso debe inicializarse mediante el método AssginItems de resourcedata o asignando valores a las propiedades de la clase.
type: docs
weight: 3060
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---
## VstkResource class

Clase de recurso VstkResource. Contiene información sobre Vector Stroke Data. El recurso debe inicializarse mediante el método AssginItems de resourcedata, o asignando valores a las propiedades de la clase.

```csharp
public class VstkResource : LayerResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VstkResource](vstkresource/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FillEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/fillenabled/) { get; set; } | Obtiene o establece un valor que indica si Relleno de trazo está habilitado. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/key/) { get; } | Obtiene la clave de recurso de la capa. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/length/) { get; } | Obtiene la longitud del recurso de la capa en bytes. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/psdversion/) { get; } | Obtiene la versión psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/signature/) { get; } | Obtiene la firma. |
| [StrokeEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokeenabled/) { get; set; } | Obtiene o establece un valor que indica si el efecto de trazo está habilitado. |
| [StrokeStyleBlendMode](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleblendmode/) { get; set; } | Obtiene o establece el modo de combinación de trazos. |
| [StrokeStyleContent](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylecontent/) { get; set; } | Obtiene o establece la entidad Stroke. La propiedad determina la configuración de relleno del trazo. |
| [StrokeStyleLineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/) { get; set; } | Obtiene o establece la alineación de línea de estilo de trazo. |
| [StrokeStyleLineCapType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecaptype/) { get; set; } | Obtiene o establece el tipo de línea de estilo de trazo cap. |
| [StrokeStyleLineCapWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecapwidth/) { get; set; } | Obtiene o establece el ancho de límite de línea de trazo. |
| [StrokeStyleLineDashOffset](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashoffset/) { get; set; } | Obtiene o establece el desplazamiento de guión de línea de estilo de trazo. |
| [StrokeStyleLineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashset/) { get; set; } | Obtiene o establece una matriz de guiones de línea. |
| [StrokeStyleLineJoinType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinejointype/) { get; set; } | Obtiene o establece el tipo de unión de línea de estilo de trazo. |
| [StrokeStyleLineWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/) { get; set; } | Obtiene o establece Ancho de línea de trazo. |
| [StrokeStyleMiterLimit](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylemiterlimit/) { get; set; } | Obtiene o establece el límite de inglete del estilo de trazo. |
| [StrokeStyleOpacity](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleopacity/) { get; set; } | Obtiene o establece la opacidad del estilo del trazo (0-100%). |
| [StrokeStyleResolution](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleresolution/) { get; set; } | Obtiene o establece la resolución del estilo de trazo. |
| [StrokeStyleScaleLock](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylescalelock/) { get; set; } | Obtiene o establece el bloqueo de escala de estilo de trazo. |
| [StrokeStyleStrokeAdjust](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylestrokeadjust/) { get; set; } | Obtiene o establece Ajuste de carrera. |
| [StrokeStyleVersion](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleversion/) { get; set; } | Obtiene o establece la versión del estilo de trazo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/save/)(StreamContainer, int) | Guarda el recurso en el contenedor de flujo especificado. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/typetoolkey/) | La clave de información de la herramienta de tipo. |

### Ejemplos

El código siguiente demuestra la compatibilidad con el recurso VstkResource.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### Ver también

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* asamblea [Aspose.PSD](../../)


