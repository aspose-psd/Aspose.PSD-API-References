---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD for .NET API 参考"
description: "FileCreateSource 构造函数。初始化 FileCreateSource 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

初始化 [`FileCreateSource`](../) 类的新实例。

```csharp
public FileCreateSource(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要创建的文件路径。 |

## 示例

此示例在磁盘的某个位置创建一个新的 Image 文件，位置由 BmpOptions 实例的 Source 属性指定。如果在 FileCreateSource 的构造函数中未传入第二个参数，则默认创建的文件的 IsTemporal 属性设置为 True。IsTemporal 设置为 True 时，执行结束后不会在磁盘上保存文件。

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//创建 PsdOptions 的实例并设置其各项属性。
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 FileCreateSource 的实例并将其分配为 PsdOptions 实例的 Source
//如果未传入第二个参数，则默认文件的 IsTemporal 设置为 True。
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//创建 Image 的实例
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //进行一些图像处理。
}
```

### 另请参阅

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

初始化 [`FileCreateSource`](../) 类的新实例。

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要创建的文件路径。 |
| isTemporal | 布尔 | 如果设置为 `true`，创建的文件将是临时的。 |

## 示例

此示例在由 PsdOptions 实例的 Source 属性指定的磁盘位置创建一个新的 Image 文件。在创建实际图像之前，会设置 PsdOptions 实例的多个属性。尤其是指向此案例实际磁盘位置的 Source 属性。

```csharp
[C#]

//创建 PsdOptions 的实例并设置其各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 FileCreateSource 的实例并将其分配为 PsdOptions 实例的 Source
//第二个布尔参数决定要创建的文件是否为临时文件
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//创建 Image 的实例，并通过调用 Create 方法使用 PsdOptions 实例进行初始化
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //进行一些图像处理。

    // 保存所有更改
    image.Save();
}
```

### 另请参阅

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


