---
title: "Timeline.Save"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Timeline. Guarda los PsdImages y los datos de Timeline en la ubicación de archivo especificada en el formato especificado según las opciones de guardado"
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Guarda los datos de PsdImage y Timeline en la ubicación de archivo especificada en el formato especificado según las opciones de guardado.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| opciones | ImageOptionsBase | Las opciones. |

## Ejemplos

El siguiente código demuestra el soporte de exportar Timeline a una imagen Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Ver también

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Guarda los datos de PsdImage y Timeline en el flujo especificado en el formato especificado según las opciones de guardado.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Flujo | El flujo de salida. |
| opciones | ImageOptionsBase | Las opciones. |

## Ejemplos

El siguiente código demuestra el soporte de exportar Timeline a una imagen Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### Ver también

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


