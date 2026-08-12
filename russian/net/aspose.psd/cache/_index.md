---
title: "Класс Cache"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Cache. Содержит настройки кэша"
type: docs
weight: 240
url: /ru/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Содержит настройки кэша.

```csharp
public static class Cache
```

## Свойства

| Имя | Описание |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Возвращает количество выделенных байтов на диске. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Возвращает количество выделенных байтов в памяти. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Получает или задает папку кэша. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Получает или задает используемую схему кэша. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Получает или задает значение, указывающее, должна ли переалокация быть точной. Если переалокация неточная, производительность должна быть выше. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Получает или задает максимальное доступное дисковое пространство для кэша. Указанное значение — количество мегабайт. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Получает или задает максимальную доступную память для кэша в памяти. Указанное значение — количество мегабайт. |

## Методы

| Имя | Описание |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Устанавливает настройки `Cache` по умолчанию. |

## Примеры

Этот пример демонстрирует использование Aspose.PSD.Cache

```csharp
[C#]

// По умолчанию папка кэша устанавливается в локальный временный каталог пользователя.
// Вы также можете указать другую папку кэша, отличную от значения по умолчанию, как показано ниже:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// Автоматический режим гибок и эффективен
Cache.CacheType = CacheType.Auto;

// Значение по умолчанию — 0, что означает отсутствие верхнего предела
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// Не рекомендуется изменять следующее свойство, так как это может сильно повлиять на производительность
Cache.ExactReallocateOnly = false;

// В любой момент вы можете проверить, сколько байтов в данный момент выделено для памяти или диска
// кэша, изучив следующие свойства
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Выполните обработку изображения, как показано ниже
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // после выполнения приведённого кода будет выделено 40000 байт в памяти.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Свойства выделения могут использоваться для проверки, были ли все объекты Aspose.PSD правильно освобождены.
// В случае, если вы забыли вызвать dispose для какого-либо объекта, значения кэша будут отличаться от 0.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


