---
title: "WarpSettings.WarpSettings"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor WarpSettings. Inicializa una nueva instancia de la clase WarpSettings"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Inicializa una nueva instancia de la clase [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| meshPoints | PointF[] | Los puntos de malla de la deformación |
| límites | Rectangle | Los límites de la imagen deformada |

## Ejemplos

El siguiente código demuestra el soporte de la propiedad WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Obtener configuraciones de deformación
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Establecer nuevo tamaño
    // Para Photoshop, el valor puede estar entre 1 y 50 y no se puede guardar el archivo PSD correctamente.
    warpSettings.GridSize = new Size(100, 100);

    // Establecer valor válido
    warpSettings.GridSize = new Size(3, 3);

    // Renderizar archivo de ejemplo con cuadrícula x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Ver también

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Inicializa una nueva instancia de la clase [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| meshPoints | PointF[] | Los puntos de malla de la deformación |
| límites | Rectangle | Los límites de la imagen deformada |
| style | WarpStyles | El estilo de la deformación |

## Ejemplos

El siguiente código demuestra el soporte de la propiedad WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Obtener configuraciones de deformación
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Establecer nuevo tamaño
    // Para Photoshop, el valor puede estar entre 1 y 50 y no se puede guardar el archivo PSD correctamente.
    warpSettings.GridSize = new Size(100, 100);

    // Establecer valor válido
    warpSettings.GridSize = new Size(3, 3);

    // Renderizar archivo de ejemplo con cuadrícula x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Ver también

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Inicializa una nueva instancia de la clase [`WarpSettings`](../).

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | Elementos PS con configuraciones de deformación |
| límites | Rectangle | Los límites de la imagen deformada |

### Ver también

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Inicializa una nueva instancia de la clase [`WarpSettings`](../).

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| placedResource | PlacedResource | El recurso con configuraciones de deformación |

### Ver también

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


