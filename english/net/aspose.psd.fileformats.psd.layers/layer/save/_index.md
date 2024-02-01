---
title: Layer.Save
second_title: Aspose.PSD for .NET API Reference
description: Layer method. Saves the objects data to the specified stream
type: docs
weight: 380
url: /net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

Saves the object's data to the specified stream.

```csharp
public override void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to save the object's data to. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | We should not call Save method without Image options |

### See Also

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Saves the object's data to the specified file location in the specified file format according to save options.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| options | ImageOptionsBase | The options. |

### See Also

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Saves the object's data to the specified file location.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path to save the object's data to. |
| overWrite | Boolean | if set to `true` over write the file contents, otherwise append will occur. |

### See Also

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Saves the image's data to the specified stream in the specified file format according to save options.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to save the image's data to. |
| optionsBase | ImageOptionsBase | The save options. |
| boundsRectangle | Rectangle | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### See Also

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Saves the object's data to the specified file location in the specified file format according to save options.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |
| options | ImageOptionsBase | The options. |
| boundsRectangle | Rectangle | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### See Also

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


