---
title: "Classe Cache"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Cache. Contient les paramètres du cache"
type: docs
weight: 240
url: /fr/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Contient les paramètres du cache.

```csharp
public static class Cache
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Obtient le nombre d'octets disque alloués. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Obtient le nombre d'octets en mémoire alloués. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Obtient ou définit le dossier du cache. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Obtient ou définit le schéma de cache utilisé. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Obtient ou définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être supérieures. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Obtient ou définit l'espace disque maximal disponible pour le cache. La valeur spécifiée correspond au nombre de mégaoctets. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Obtient ou définit la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée correspond au nombre de mégaoctets. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Définit les paramètres `Cache` aux valeurs par défaut. |

## Exemples

Cet exemple montre l'utilisation de Aspose.PSD.Cache

```csharp
[C#]

// Par défaut, le dossier du cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que le défaut comme suit :
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Le mode automatique est flexible et efficace
Cache.CacheType = CacheType.Auto;

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Il n'est pas recommandé de modifier la propriété suivante car cela peut grandement affecter les performances
Cache.ExactReallocateOnly = false;

// À tout moment, vous pouvez vérifier combien d'octets sont actuellement alloués pour la mémoire ou le disque 
// cache en examinant les propriétés suivantes
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Effectuez un traitement d'image comme ci‑dessous
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // Après l'exécution du code ci‑dessus, 40000 octets seront alloués en mémoire.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.PSD ont été correctement libérés.
// Dans le cas où vous auriez oublié d’appeler dispose sur un objet, les valeurs du cache seront différentes de 0.
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Voir aussi

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


