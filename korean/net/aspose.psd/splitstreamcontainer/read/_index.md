---
title: "SplitStreamContainer.Read"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "SplitStreamContainer 메서드. 지정된 바이트 버퍼를 채우기 위해 바이트를 읽습니다."
type: docs
weight: 110
url: /ko/net/aspose.psd/splitstreamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

지정된 바이트 버퍼를 채우기 위해 바이트를 읽습니다.

```csharp
public override int Read(byte[] bytes)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 바이트 | Byte[] | 채울 바이트. |

### 반환 값

읽은 바이트 수. 스트림에 바이트가 충분하지 않을 경우 이 값은 버퍼의 바이트 수보다 작을 수 있습니다.

### 또 보기

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

현재 스트림에서 바이트 시퀀스를 읽고, 읽은 바이트 수만큼 스트림 내 위치를 이동합니다.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | Byte[] | 바이트 배열. 이 메서드가 반환될 때, 버퍼는 지정된 바이트 배열을 포함하며, *offset*와 (*offset* + *count* - 1) 사이의 값은 현재 소스에서 읽은 바이트로 교체됩니다. |
| offset | Int32 | 현재 스트림에서 읽은 데이터를 저장하기 시작하는 *buffer* 내의 0부터 시작하는 바이트 오프셋입니다. |
| count | Int32 | 현재 스트림에서 읽을 최대 바이트 수입니다. |

### 반환 값

버퍼에 읽힌 총 바이트 수입니다. 요청한 바이트 수보다 적을 수 있으며, 이는 해당 바이트가 현재 사용 가능하지 않거나 스트림 끝에 도달한 경우 0(0)이 될 수 있습니다.

### 또 보기

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


