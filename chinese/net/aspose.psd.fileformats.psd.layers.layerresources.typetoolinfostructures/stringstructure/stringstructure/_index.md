---
title: StringStructure.StringStructure
second_title: Aspose.PSD for .NET API 参考
description: StringStructure 构造函数. 初始化一个新的实例StringStructure类.
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/stringstructure/stringstructure/
---
## StringStructure(ClassID) {#constructor}

初始化一个新的实例[`StringStructure`](../)类.

```csharp
public StringStructure(ClassID keyName)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| keyName | ClassID | 密钥名称。 |

### 也可以看看

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [StringStructure](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../stringstructure/)
* 部件 [Aspose.PSD](../../../)

---

## StringStructure(ClassID, string) {#constructor_1}

初始化一个新的实例[`StringStructure`](../)具有价值的班级.

```csharp
public StringStructure(ClassID keyName, string value)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| keyName | ClassID | 密钥名称。 |
| value | String | 价值。 |

### 例子

此示例演示如何获取和设置 Psd LnkE 资源的属性。

```csharp
[C#]

string message = "The example works incorrectly.";
void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(message);
    }
}

// 此示例演示如何获取和设置包含有关外部链接文件信息的 Psd LnkE 资源的属性。
void ExampleOfLnkEResourceSupport(
    string fileName,
    int length,
    int length2,
    int length3,
    int length4,
    string fullPath,
    string date,
    double assetModTime,
    string childDocId,
    bool locked,
    string uid,
    string name,
    string originalFileName,
    string fileType,
    long size,
    int version)
{
    string outputPath = fileName;
    using (PsdImage image = (PsdImage)Image.Load(fileName))
    {
        LnkeResource lnkeResource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnkeResource = resource as LnkeResource;
            if (lnkeResource != null)
            {
                LiFeDataSource lifeSource = lnkeResource[0];
                AssertAreEqual(lnkeResource.Length, length);
                AssertAreEqual(lifeSource.UniqueId, new Guid(uid));
                AssertAreEqual(lifeSource.FullPath, fullPath);
                AssertAreEqual(lifeSource.Date.ToString(CultureInfo.InvariantCulture), date);
                AssertAreEqual(lifeSource.AssetModTime, assetModTime);
                AssertAreEqual(lifeSource.FileName, name);
                AssertAreEqual(lifeSource.FileSize, size);
                AssertAreEqual(lifeSource.ChildDocId, childDocId);
                AssertAreEqual(lifeSource.Version, version);
                AssertAreEqual(lifeSource.FileType.TrimEnd(' '), fileType);
                AssertAreEqual(lifeSource.FileCreator.TrimEnd(' '), string.Empty);
                AssertAreEqual(lifeSource.OriginalFileName, originalFileName);
                AssertAreEqual(false, lnkeResource.IsEmpty);
                AssertAreEqual(true, lifeSource.Type == LinkDataSourceType.liFE);
                if (version == 7)
                {
                    AssertAreEqual(lifeSource.AssetLockedState, locked);
                }

                if (lifeSource.HasFileOpenDescriptor)
                {
                    AssertAreEqual(lifeSource.CompId, -1);
                    AssertAreEqual(lifeSource.OriginalCompId, -1);
                }

                lifeSource.FullPath =
                    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/SmartObjects/rgb8_2x2.png";
                AssertAreEqual(lnkeResource.Length, length2);
                lifeSource.FileName = "rgb8_2x23.png";
                AssertAreEqual(lnkeResource.Length, length3);
                lifeSource.ChildDocId = Guid.NewGuid().ToString();
                AssertAreEqual(lnkeResource.Length, length4);
                lifeSource.Date = DateTime.Now;
                lifeSource.AssetModTime = double.MaxValue;
                lifeSource.FileSize = long.MaxValue;
                lifeSource.FileType = "test";
                lifeSource.FileCreator = "file";
                lifeSource.CompId = int.MaxValue;
                break;
            }
        }

        AssertAreEqual(true, lnkeResource != null);

        image.Save(outputPath, new PsdOptions(image));
    }
}

// 此示例演示如何获取和设置包含有关外部链接的 JPEG 文件的信息的 Psd LnkeResource 的属性。
ExampleOfLnkEResourceSupport(
    @"photooverlay_5_new.psd",
    0x21c,
    0x26c,
    0x274,
    0x27c,
    @"file:///C:/Users/cvallejo/Desktop/photo.jpg",
    "05/09/2017 22:24:51",
    0,
    "F062B9DB73E8D124167A4186E54664B0",
    false,
    "02df245c-36a2-11e7-a9d8-fdb2b61f07a7",
    "photo.jpg",
    "photo.jpg",
    "JPEG",
    0x1520d,
    7);

// 此示例演示如何获取和设置包含有关外部链接 PNG 文件的信息的 PSD LnkeResource 的属性。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_linked.psd",
    0x284,
    0x290,
    0x294,
    0x2dc,
    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Issues/PSDNET-491/rgb8_2x2.png",
    "04/14/2020 14:23:44",
    0,
    string.Empty,
    false,
    "5867318f-3174-9f41-abca-22f56a75247e",
    "rgb8_2x2.png",
    "rgb8_2x2.png",
    "png",
    0x53,
    7);

// 此示例演示如何获取和设置 PSD LnkeResource 的属性，该资源包含有关两个外部链接的 PNG 和 PSD 文件的信息。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_linked2.psd",
    0x590,
    0x580,
    0x554,
    0x528,
    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/AddColorBalanceAdjustmentLayer.psd",
    "01/15/2020 13:02:00",
    0,
    "adobe:docid:photoshop:9312f484-3403-a644-8973-e725abc95fb7",
    false,
    "78a5b588-364f-0940-a2e5-a450a031aa48",
    "AddColorBalanceAdjustmentLayer.psd",
    "AddColorBalanceAdjustmentLayer.psd",
    "8BPS",
    0x4aea,
    7);

// 此示例演示如何获取和设置 Photoshop Psd LnkeResource 的属性，其中包含有关外部链接的 CC Libraries 资源的信息。
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_asset_linked.psd",
    0x398,
    0x38c,
    0x388,
    0x3d0,
    @"CC Libraries Asset “rgb8_2x2_linked/rgb8_2x2” (Feature is available in Photoshop CC 2015)",
    "01/01/0001 00:00:00",
    1588890915488.0d,
    string.Empty,
    false,
    "ec15f0a8-7f13-a640-b928-7d29c6e9859c",
    "rgb8_2x2_linked",
    "rgb8_2x2.png",
    "png",
    0,
    7);
```

### 也可以看看

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [StringStructure](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../stringstructure/)
* 部件 [Aspose.PSD](../../../)


