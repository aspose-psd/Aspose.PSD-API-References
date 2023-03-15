---
title: Class Cache
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.Cache 수업. 캐시 설정을 포함합니다.
type: docs
weight: 240
url: /ko/net/aspose.psd/cache/
---
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
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | 사용된 캐시 체계를 가져오거나 설정합니다. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | 재할당이 정확한지 여부를 나타내는 값을 가져오거나 설정합니다. 재할당이 정확하지 않으면 성능이 더 높아야 합니다. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | 캐시에 사용할 수 있는 최대 디스크 공간을 가져오거나 설정합니다. 지정된 값은 메가바이트 count. 입니다. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | 메모리의 캐시에 사용할 수 있는 최대 메모리를 가져오거나 설정합니다. 지정된 값은 메가바이트 count. 입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | 설정`Cache` 기본값으로 설정. |

### 예

이 예제는 Aspose.PSD.Cache의 사용을 보여줍니다.

```csharp
[C#]

// 기본적으로 캐시 폴더는 사용자의 로컬 임시 디렉터리로 설정됩니다.
// 다음과 같이 기본값이 아닌 다른 캐시 폴더를 지정할 수도 있습니다.
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// 자동 모드는 유연하고 효율적입니다.
Cache.CacheType = CacheType.Auto;

// 기본값은 0이며 상한선이 없음을 의미합니다.
Cache.MaxDiskSpaceForCache = 1073741824; // 1기가바이트
Cache.MaxMemoryForCache = 1073741824; // 1기가바이트

// 다음 속성은 성능에 큰 영향을 미칠 수 있으므로 변경하지 않는 것이 좋습니다.
Cache.ExactReallocateOnly = false;

// 언제든지 현재 메모리 또는 디스크에 할당된 바이트 수를 확인할 수 있습니다. 
// 다음 속성을 검사하여 캐시
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// 아래와 같이 일부 이미지 처리를 수행합니다.
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // 위의 코드를 실행한 후 메모리에 40000바이트가 할당됩니다.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// 할당 속성은 모든 Aspose.PSD 개체가 적절하게 배치되었는지 확인하는 데 사용할 수 있습니다.
// 어떤 객체에 대해 dispose를 호출하는 것을 잊은 경우 캐시 값은 0이 아닙니다.            
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


