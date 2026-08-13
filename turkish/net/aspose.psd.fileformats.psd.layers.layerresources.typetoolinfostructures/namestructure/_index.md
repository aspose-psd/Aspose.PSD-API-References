---
title: "Sınıf NameStructure"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.NameStructure sınıfı. Name yapı anahtarı 0x6E616D65, ASCII'de 'name' olarak yazılır, bir katman yolu veya ayar gibi bir öğenin adını temsil eden Unicode veya Pascal tarzı bir dize depolamak için kullanılan basit bir yapıdır."
type: docs
weight: 3580
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/
---
{{< psd/tize >}}
## NameStructure class

Name yapısı (anahtar: 0x6E616D65, ASCII'de "name" olarak yazılır) bir katman, yol veya ayar gibi bir öğenin adını temsil eden Unicode veya Pascal tarzı bir dizeyi depolamak için kullanılan basit bir yapıdır.

```csharp
public sealed class NameStructure : OSTypeStructure
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [NameStructure](namestructure/)(ClassID) | `NameStructure` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/key/) { get; } | Anahtarı alır. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Anahtar adını alır veya ayarlar. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/length/) { get; } | [`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) uzunluğunu bayt cinsinden alır. |
| [Value](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/value/) { get; set; } | Name yapısının değerini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Başlık uzunluğunu alır. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Yapıyı belirtilen akış konteynerine kaydeder. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Yapıyı belirtilen akış konteynerine kaydeder. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/namestructure/structurekey/) | Name yapı anahtarı. |

## Örnekler

Aşağıdaki kod NameStructure desteğini gösterir.

```csharp
[C#]

string inputFile = "Mixer_ipad_Hand_W_crash.psd";
string outputFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(inputFile, new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    //// Dosya başarıyla yüklendi

    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);

    // Test dosyasını değişiklik yapmadan kaydet
    psdImage.Save(outputFile);

    //// Dosya PS'de hatasız açılmalıdır
}

// Aydınlatma efektlerinin yapıların doğru kaydedildiğini kontrol edin
using (var psdImage = (PsdImage)Image.Load(
           outputFile,
           new PsdLoadOptions { DataRecoveryMode = DataRecoveryMode.MaximalRecover }))
{
    SmartObjectLayer layer = (SmartObjectLayer)psdImage.Layers[3];
    SoLdResource resource = (SoLdResource)layer.Resources[9];

    DescriptorStructure struct1 = (DescriptorStructure)resource.Items[15];
    ListStructure struct2 = (ListStructure)struct1.Structures[5];
    DescriptorStructure struct3 = (DescriptorStructure)struct2.Types[0];
    DescriptorStructure struct4 = (DescriptorStructure)struct3.Structures[6];
    ReferenceStructure struct5 = (ReferenceStructure)struct4.Structures[8];
    NameStructure nameStructure = (NameStructure)struct5.Items[0];

    AssertIsNotNull(nameStructure);
    AssertAreEqual(37, nameStructure.Length);
    AssertAreEqual("None\0", nameStructure.Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

void AssertIsNotNull(object actual)
{
    if (actual == null)
    {
        throw new Exception("Object is null.");
    }
}
```

### Ayrıca Bakınız

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../)


