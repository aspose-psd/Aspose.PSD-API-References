---
title: "Kelas AnimatedDataSectionResource"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Kelas Aspose.PSD.FileFormats.Psd.Resources.AnimatedDataSectionResource. Sumber daya PlugIn Animated Data Section"
type: docs
weight: 4090
url: /id/net/aspose.psd.fileformats.psd.resources/animateddatasectionresource/
---
{{< psd/tize >}}
## AnimatedDataSectionResource class

Sumber daya Plug-In Animated Data Section.

```csharp
public class AnimatedDataSectionResource : ResourceBlock
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AnimatedDataSection](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/animateddatasection/) { get; } | Mendapatkan atau mengatur struktur bagian data animasi. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/datasize/) { get; } | Mendapatkan ukuran data sumber daya dalam byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik untuk sumber daya. |
| [KeyName](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/keyname/) { get; } | Nama kunci sumber daya. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/animateddatasectionresource/minimalversion/) { get; } | Mendapatkan versi PSD minimal yang diperlukan. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Mendapatkan atau mengatur nama sumber daya. String Pascal, dipadding agar ukuran genap (nama null terdiri dari dua byte 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Mendapatkan tanda tangan sumber daya. Harus selalu '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Mendapatkan ukuran blok sumber daya dalam byte termasuk datanya. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Menyimpan blok sumber daya ke aliran yang ditentukan. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Memvalidasi nilai-nilai sumber daya. |

## Contoh

Kode berikut menunjukkan cara mengatur/memperbarui waktu tunda dalam bingkai timeline data animasi.

```csharp
[C#]

string sourceFile = "3_animated.psd";
string outputPsd = "output_3_animated.psd";

T FindStructure<T>(IEnumerable<OSTypeStructure> structures, string keyName) where T : OSTypeStructure
{
    foreach (var structure in structures)
    {
        if (structure.KeyName.ClassName == keyName)
        {
            return structure as T;
        }
    }

    return null;
}

OSTypeStructure[] AddOrReplaceStructure(IEnumerable<OSTypeStructure> structures, OSTypeStructure newStructure)
{
    List<OSTypeStructure> listOfStructures = new List<OSTypeStructure>(structures);

    for (int i = 0; i < listOfStructures.Count; i++)
    {
        OSTypeStructure structure = listOfStructures[i];
        if (structure.KeyName.ClassName == newStructure.KeyName.ClassName)
        {
            listOfStructures.RemoveAt(i);
            break;
        }
    }

    listOfStructures.Add(newStructure);

    return listOfStructures.ToArray();
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var imageResource in image.ImageResources)
    {
        if (imageResource is AnimatedDataSectionResource)
        {
            var animatedData =
                (AnimatedDataSectionStructure) (imageResource as AnimatedDataSectionResource).AnimatedDataSection;
            var framesList = FindStructure<ListStructure>(animatedData.Items, "FrIn");

            var frame1 = (DescriptorStructure)framesList.Types[1];

            // Membuat catatan penundaan bingkai dengan nilai 100 senti-detik yang setara dengan 1 detik.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // set time in centi-seconds.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Lihat Juga

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


