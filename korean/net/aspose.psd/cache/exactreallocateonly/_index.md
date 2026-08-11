---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Cache 속성. 재할당이 정확해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. 재할당이 정확하지 않은 경우 성능이 더 높아야 합니다"
type: docs
weight: 50
url: /ko/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

재할당이 정확해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. 재할당이 정확하지 않을 경우 성능이 더 높아집니다.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true`이면 재할당이 정확하고, 그렇지 않으면 `false`.

## 비고

정확한 재할당은 지정된 상한까지 추가 메모리 재할당을 수행합니다. 재할당 중에 메모리 상한을 지정하면 캐시된 데이터가 가능한 경우 디스크로 복사됩니다. 디스크 메모리 상한을 지정하면 적절한 예외가 발생합니다. 이 옵션을 끄면 추가 복사가 수행되지 않아 성능이 향상될 수 있지만, 메모리 또는 디스크에 지정된 상한을 초과할 수 있습니다.

### 또 보기

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


