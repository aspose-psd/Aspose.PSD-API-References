---
title: Cache.ExactReallocateOnly
second_title: .NET API 참조용 Aspose.PSD
description: Cache 재산. 재할당이 정확한지 여부를 나타내는 값을 가져오거나 설정합니다. 재할당이 정확하지 않으면 성능이 더 높아야 합니다.
type: docs
weight: 50
url: /ko/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

재할당이 정확한지 여부를 나타내는 값을 가져오거나 설정합니다. 재할당이 정확하지 않으면 성능이 더 높아야 합니다.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### 자산 가치

`진실` 재할당이 정확한 경우; 그렇지 않으면,`거짓` .

### 비고

정확한 재할당은 지정된 상한까지만 추가 메모리 재할당을 수행합니다. 재할당 중 인 메모리 상한을 초과하면 캐시된 데이터가 가능한 경우 디스크에 복사됩니다. 재할당 중 디스크 메모리 상한을 초과하면 적절한 예외가 발생합니다. 가능한 경우 추가 복사가 수행되지 않으므로 이 옵션을 끄면 성능이 더 높아야 합니다.

### 또한보십시오

* class [Cache](../)
* 네임스페이스 [Aspose.PSD](../../cache/)
* 집회 [Aspose.PSD](../../../)


