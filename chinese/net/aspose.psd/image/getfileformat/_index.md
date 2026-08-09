---
title: "Image.GetFileFormat"
second_title: "Aspose.PSD for .NET API 参考"
description: "Image 方法。获取文件格式"
type: docs
weight: 270
url: /zh/net/aspose.psd/image/getfileformat/
---
{{< psd/tize >}}
## GetFileFormat(string) {#getfileformat_1}

获取文件格式。

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 文件路径。 |

### 返回值

确定的文件格式。

## 备注

确定的文件格式并不意味着可以加载指定的图像。请使用 CanLoad 方法的重载之一来确定文件是否可以加载。

### 另请参阅

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetFileFormat(Stream) {#getfileformat}

获取文件格式。

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 流。 |

### 返回值

确定的文件格式。

## 备注

确定的文件格式并不意味着可以加载指定的图像。请使用 CanLoad 方法的重载之一来确定流是否可以加载。

### 另请参阅

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


