---
title: Image.GetFileFormat
second_title: Aspose.PSD for .NET API Reference
description: Image method. Gets the file format
type: docs
weight: 270
url: /net/aspose.psd/image/getfileformat/
---
{{< psd/tize >}}
## GetFileFormat(string) {#getfileformat_1}

Gets the file format.

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The file path. |

### Return Value

The determined file format.

## Remarks

The file format determined does not mean that the specified image may be loaded. Use one of the CanLoad method overloads to determine whether file may be loaded.

### See Also

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetFileFormat(Stream) {#getfileformat}

Gets the file format.

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |

### Return Value

The determined file format.

## Remarks

The file format determined does not mean that the specified image may be loaded. Use one of the CanLoad method overloads to determine whether stream may be loaded.

### See Also

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


