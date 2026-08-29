---
title: "TiffStreamReader.ReadBytes"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode TiffStreamReader. Lit un tableau de valeurs octet depuis le flux"
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readbytes/
---
{{< psd/tize >}}
## ReadBytes(byte[], int, long, long) {#readbytes_1}

Lit un tableau de valeurs byte depuis le flux.

```csharp
public long ReadBytes(byte[] array, int arrayIndex, long position, long count)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| array | Byte[] | Le tableau à remplir. |
| arrayIndex | Int32 | L'index du tableau où commencer à placer les valeurs. |
| position | Int64 | La position du flux à lire. |
| count | Int64 | Le nombre d'éléments à lire. |

### Valeur de retour

Le tableau de valeurs octet.

### Voir aussi

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)

---

## ReadBytes(long, long) {#readbytes}

Lit un tableau de valeurs unsigned byte depuis le flux.

```csharp
public byte[] ReadBytes(long position, long count)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| position | Int64 | La position à lire. |
| count | Int64 | Le nombre d'éléments. |

### Valeur de retour

Le tableau d'octets non signés.

### Voir aussi

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


