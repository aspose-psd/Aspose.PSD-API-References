---
title: "Sınıf PathStructure"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure sınıfı. Yol yapısı"
type: docs
weight: 3610
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
{{< psd/tize >}}
## PathStructure class

Yol yapısı.

```csharp
public sealed class PathStructure : OSTypeStructure
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PathStructure](pathstructure/#constructor)(ClassID) | Yeni bir `PathStructure` sınıfı örneği başlatır. |
| [PathStructure](pathstructure/#constructor_1)(ClassID, string) | Bir yol ile `PathStructure` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | Yapı anahtarını alır. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Anahtar adını alır veya ayarlar. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) uzunluğunu bayt cinsinden alır. |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | Yolu alır veya ayarlar (TypeTool yol formatı için). |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | Eski yol önekini alır veya ayarlar (TypeTool yol formatı için). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Başlık uzunluğunu alır. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Yapıyı belirtilen akış konteynerine kaydeder. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Yapıyı belirtilen akış konteynerine kaydeder. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | Yapı anahtarını tanımlar. |

## Örnekler

Aşağıdaki kod, PathStructure yapısıyla dosya yükleme yeteneğini gösterir.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Ayrıca Bakınız

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


