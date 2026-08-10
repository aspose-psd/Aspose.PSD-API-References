---
title: "AiImage.PageCount"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti AiImage. Jumlah halaman. Untuk gambar format AI lama selalu bernilai 0"
type: docs
weight: 110
url: /id/net/aspose.psd.fileformats.ai/aiimage/pagecount/
---
{{< psd/tize >}}
## AiImage.PageCount property

Jumlah halaman. Untuk gambar format AI lama selalu bernilai 0.

```csharp
public int PageCount { get; }
```

### Property Value

Jumlah halaman.

## Contoh

Kode berikut menunjukkan dukungan properti AiImage untuk jumlah halaman AiImage.PageCount.

```csharp
[C#]

string sourceFile = "2241.ai";
string[] outputFiles = new string[3]
{
    "2241_pageNumber_0.png",
    "2241_pageNumber_1.png",
    "2241_pageNumber_2.png",
};

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.PageCount, 3);

    for (int i = 0; i < image.PageCount; i++)
    {
        image.ActivePageIndex = i;
        image.Save(outputFiles[i], new PngOptions());
    }
}
```

### Lihat Juga

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


