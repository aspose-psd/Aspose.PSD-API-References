---
title: Class Cache
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.Cache classe. Contient les paramètres de cache.
type: docs
weight: 240
url: /fr/net/aspose.psd/cache/
---
## Cache class

Contient les paramètres de cache.

```csharp
public static class Cache
```

## Propriétés

| Nom | La description |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Obtient le nombre d'octets de disque alloués. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Obtient le nombre d'octets alloués en mémoire. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Obtient ou définit le dossier de cache. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Obtient ou définit le schéma de cache utilisé. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Obtient ou définit une valeur indiquant si la réallocation doit être exacte ou non. Si la réallocation n'est pas exacte, les performances devraient être plus élevées. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Obtient ou définit l'espace disque disponible maximum pour le cache. La valeur spécifiée est le nombre de mégaoctets. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Obtient ou définit la mémoire maximale disponible pour le cache en mémoire. La valeur spécifiée est le nombre de mégaoctets. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Définit le`Cache` paramètres par défaut. |

### Exemples

Cet exemple montre l'utilisation de Aspose.PSD.Cache

```csharp
[C#]

// Par défaut, le dossier de cache est défini sur le répertoire temporaire local de l'utilisateur.
// Vous pouvez également spécifier un autre dossier de cache que celui par défaut comme suit :
// Cache.CacheFolder = @"D:\\MaTemp" ;

string path = "C:\\temp\\image.psd";

// Le mode automatique est flexible et efficace
Cache.CacheType = CacheType.Auto;

// La valeur par défaut est 0, ce qui signifie qu'il n'y a pas de limite supérieure
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigaoctet
Cache.MaxMemoryForCache = 1073741824; // 1 gigaoctet

// Il n'est pas recommandé de modifier la propriété suivante car cela peut grandement affecter les performances
Cache.ExactReallocateOnly = false;

// A tout moment, vous pouvez vérifier le nombre d'octets actuellement alloués pour la mémoire ou le disque 
// cache en examinant les propriétés suivantes
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Effectuez un traitement d'image comme ci-dessous
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // après avoir exécuté le code ci-dessus, 40 000 octets seront alloués en mémoire.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Les propriétés d'allocation peuvent être utilisées pour vérifier si tous les objets Aspose.PSD ont été correctement supprimés.
// Si vous avez oublié d'appeler dispose sur un objet, les valeurs du cache seront différentes de 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Voir également

* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


