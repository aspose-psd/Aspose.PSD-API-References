---
title: "클래스 StreamContainer"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.StreamContainer 클래스. 스트림을 포함하고 스트림 처리 루틴을 제공하는 스트림 컨테이너를 나타냅니다."
type: docs
weight: 6140
url: /ko/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

스트림을 포함하고 스트림 처리 루틴을 제공하는 스트림 컨테이너를 나타냅니다.

```csharp
public class StreamContainer : DisposableObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | 새 `StreamContainer` 클래스 인스턴스를 초기화합니다. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | 새 `StreamContainer` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | 스트림이 읽기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | 스트림이 탐색을 지원하는지 여부를 나타내는 값을 가져옵니다. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | 스트림이 쓰기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | 이 스트림이 닫힐 때 해제되는지 여부를 나타내는 값을 가져옵니다. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | 스트림 길이를 바이트 단위로 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치만큼 Length보다 작습니다. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | 스트림 내 현재 위치를 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | 데이터 스트림을 가져옵니다. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | 동기화된 리소스에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | 이 스트림의 모든 버퍼를 지우고 버퍼링된 데이터를 기본 장치에 기록하도록 합니다. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | 지정된 바이트 버퍼를 채우기 위해 바이트를 읽습니다. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | 현재 스트림에서 바이트 시퀀스를 읽고, 읽은 바이트 수만큼 스트림 내 위치를 이동합니다. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | 스트림에서 바이트를 읽고 스트림 내 위치를 한 바이트만큼 이동합니다. 스트림 끝에 도달하면 -1을 반환합니다. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 [`ReadWriteBytesCount`](./readwritebytescount/)와 스트림 [`Length`](./length/) 값을 사용합니다. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 [`ReadWriteBytesCount`](./readwritebytescount/)와 스트림 [`Length`](./length/) 값을 사용합니다. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | 스트림의 모든 데이터를 지정된 스트림에 저장(복사)합니다. 스트림 [`Length`](./length/) 값을 사용합니다. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 스트림 [`Length`](./length/) 값을 사용합니다. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | 현재 스트림 내 위치를 설정합니다. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | 스트림 위치를 스트림의 시작으로 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | 스트림 데이터를 바이트 배열로 변환합니다. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | 스트림 데이터를 바이트 배열로 변환합니다. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | 지정된 모든 바이트를 스트림에 씁니다. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | 바이트 시퀀스를 현재 스트림에 쓰고, 쓰여진 바이트 수만큼 이 스트림 내 현재 위치를 이동합니다. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | 스트림의 현재 위치에 바이트를 쓰고 스트림 내 위치를 한 바이트만큼 이동합니다. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | 포함된 데이터를 다른 `StreamContainer`에 복사합니다. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | 포함된 데이터를 다른 `StreamContainer`에 복사합니다. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | `StreamContainer`에서 Stream으로 명시적 변환을 수행합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | 순차적으로 읽을 때 읽기 및 쓰기 바이트 수를 지정합니다. |

### 또 보기

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


