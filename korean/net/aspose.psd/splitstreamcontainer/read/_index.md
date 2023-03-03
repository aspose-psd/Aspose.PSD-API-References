---
title: SplitStreamContainer.Read
second_title: .NET API 참조용 Aspose.PSD
description: SplitStreamContainer 방법. 바이트를 읽어 지정된 바이트 버퍼를 채웁니다.
type: docs
weight: 110
url: /ko/net/aspose.psd/splitstreamcontainer/read/
---
## Read(byte[]) {#read}

바이트를 읽어 지정된 바이트 버퍼를 채웁니다.

```csharp
public override int Read(byte[] bytes)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | Byte[] | 채울 바이트입니다. |

### 반환 값

읽은 바이트 수입니다. 스트림에 바이트가 충분하지 않은 경우 이 값은 버퍼의 바이트 수보다 작을 수 있습니다.

### 또한보십시오

* class [SplitStreamContainer](../)
* 네임스페이스 [Aspose.PSD](../../splitstreamcontainer/)
* 집회 [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내의 위치를 앞으로 이동합니다.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| buffer | Byte[] | 바이트 배열입니다. 이 메서드가 반환되면 버퍼에는 다음 사이의 값을 가진 지정된 바이트 배열이 포함됩니다.*offset* 그리고 (*offset* +*count* - 1) 현재 소스에서 읽은 바이트로 대체됩니다. |
| offset | Int32 | 0부터 시작하는 바이트 오프셋*buffer* 현재 스트림에서 읽은 데이터를 저장하기 시작합니다. |
| count | Int32 | 현재 스트림에서 읽을 최대 바이트 수입니다. |

### 반환 값

버퍼로 읽은 총 바이트 수입니다. 이것은 많은 바이트가 현재 사용 가능하지 않은 경우 요청된 바이트 수보다 작거나 스트림 끝에 도달한 경우 0일 수 있습니다.

### 또한보십시오

* class [SplitStreamContainer](../)
* 네임스페이스 [Aspose.PSD](../../splitstreamcontainer/)
* 집회 [Aspose.PSD](../../../)


