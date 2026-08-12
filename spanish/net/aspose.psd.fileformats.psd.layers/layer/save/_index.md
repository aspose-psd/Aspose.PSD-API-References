---
title: "Layer.Save"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Layer. Guarda los datos del objeto en el flujo especificado"
type: docs
weight: 390
url: /es/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

Guarda los datos del objeto en el flujo especificado.

```csharp
public override void Save(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo donde guardar los datos del objeto. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | No deberíamos llamar al método Save sin opciones de Imagen |

### Ver también

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| opciones | ImageOptionsBase | Las opciones. |

### Ver también

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Guarda los datos del objeto en la ubicación de archivo especificada.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo donde guardar los datos del objeto. |
| overWrite | Boolean | si se establece en `true` sobrescribe el contenido del archivo, de lo contrario se producirá una adición. |

### Ver también

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo al que guardar los datos de la imagen. |
| optionsBase | ImageOptionsBase | Las opciones de guardado. |
| boundsRectangle | Rectangle | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Ver también

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filePath | String | La ruta del archivo. |
| opciones | ImageOptionsBase | Las opciones. |
| boundsRectangle | Rectangle | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Ver también

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


