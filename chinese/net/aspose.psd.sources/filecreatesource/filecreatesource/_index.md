---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD for .NET API 参考
description: FileCreateSource 构造函数. 初始化一个新的实例FileCreateSource类.
type: docs
weight: 10
url: /zh/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

初始化一个新的实例[`FileCreateSource`](../)类.

```csharp
public FileCreateSource(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要创建的文件路径。 |

### 例子

此示例在 BmpOptions 实例的 Source 属性指定的某个磁盘位置创建一个新的图像文件。如果第二个参数未传递给 FileCreateSource 的构造函数，则默认情况下要创建的文件的属性 IsTemporal 设置为 True。当 IsTemporal 设置为 True 时，执行结束时不会将任何文件保存在磁盘上。

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//创建 PsdOptions 的实例并设置其各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 FileCreateSource 的实例并将其指定为 PsdOptions 实例的源
//如果没有传递第二个参数，则默认情况下文件的 IsTemporal 设置为 True
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//创建图像实例 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //做一些图像处理
}
```

### 也可以看看

* class [FileCreateSource](../)
* 命名空间 [Aspose.PSD.Sources](../../filecreatesource/)
* 部件 [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

初始化一个新的实例[`FileCreateSource`](../)类.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要创建的文件路径。 |
| isTemporal | Boolean | 如果设置为`真的`创建的文件将是临时的。 |

### 例子

此示例在 PsdOptions 实例的 Source 属性指定的某个磁盘位置创建一个新的图像文件。在创建实际图像之前设置 PsdOptions 实例的几个属性。特别是 Source 属性，在这种情况下指的是实际磁盘位置。

```csharp
[C#]

//创建 PsdOptions 实例并设置其各种属性
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//创建 FileCreateSource 的实例并将其指定为 PsdOptions 实例的源
//第二个布尔参数确定要创建的文件是否为IsTemporal
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//创建Image的实例并通过调用Create方法用PsdOptions的实例初始化它
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //做一些图像处理

    // 保存所有更改
    image.Save();
}
```

### 也可以看看

* class [FileCreateSource](../)
* 命名空间 [Aspose.PSD.Sources](../../filecreatesource/)
* 部件 [Aspose.PSD](../../../)


