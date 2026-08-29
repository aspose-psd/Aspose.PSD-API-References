---
title: "클래스 Cache"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.Cache 클래스. 캐시 설정을 포함합니다"
type: docs
weight: 240
url: /ko/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

캐시 설정을 포함합니다.

```csharp
public static class Cache
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | 할당된 디스크 바이트 수를 가져옵니다. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | 할당된 메모리 내 바이트 수를 가져옵니다. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | 캐시 폴더를 가져오거나 설정합니다. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | 사용되는 캐시 스킴을 가져오거나 설정합니다. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | 재할당이 정확해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. 재할당이 정확하지 않을 경우 성능이 더 높아집니다. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | 캐시용 최대 사용 가능한 디스크 공간을 가져오거나 설정합니다. 지정된 값은 메가바이트 수입니다. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | 메모리 내 캐시용 최대 사용 가능한 메모리를 가져오거나 설정합니다. 지정된 값은 메가바이트 수입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | `Cache` 설정을 기본값으로 설정합니다. |

## 예제

이 예제는 Aspose.PSD.Cache의 사용을 보여줍니다

```csharp
[C#]

// 기본적으로 캐시 폴더는 사용자의 로컬 임시 디렉터리로 설정됩니다.
// 다음과 같이 기본값이 아닌 다른 캐시 폴더를 지정할 수도 있습니다:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// 자동 모드는 유연하고 효율적입니다
Cache.CacheType = CacheType.Auto;

// 기본값은 0이며, 이는 상한이 없음을 의미합니다
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// 다음 속성을 변경하는 것은 성능에 큰 영향을 줄 수 있으므로 권장되지 않습니다
Cache.ExactReallocateOnly = false;

// 언제든지 메모리 또는 디스크에 현재 할당된 바이트 수를 확인할 수 있습니다
// 다음 속성을 검사하여 캐시를 확인합니다
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// 아래와 같이 이미지 처리를 수행합니다
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // 위 코드를 실행한 후 메모리 내에 40000 바이트가 할당됩니다.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// 할당 속성을 사용하여 모든 Aspose.PSD 객체가 올바르게 해제되었는지 확인할 수 있습니다.
// 일부 객체에 대해 dispose 호출을 잊은 경우 캐시 값이 0이 아닌 다른 값이 됩니다.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


