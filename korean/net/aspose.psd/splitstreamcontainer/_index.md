---
title: Class SplitStreamContainer
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.SplitStreamContainer 수업. 스트림을 포함하고 스트림 처리 루틴을 제공하는 분할 스트림 컨테이너를 나타냅니다.
type: docs
weight: 5630
url: /ko/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

스트림을 포함하고 스트림 처리 루틴을 제공하는 분할 스트림 컨테이너를 나타냅니다.

```csharp
public class SplitStreamContainer : StreamContainer
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | 의 새 인스턴스를 초기화합니다.`SplitStreamContainer` 클래스. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | 의 새 인스턴스를 초기화합니다.`SplitStreamContainer` 클래스. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | 의 새 인스턴스를 초기화합니다.`SplitStreamContainer` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | 스트림이 읽기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | 스트림이 검색을 지원하는지 여부를 나타내는 값을 가져옵니다. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | 스트림이 쓰기를 지원하는지 여부를 나타내는 값을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | 이 스트림이 닫힐 때 폐기되는지 여부를 나타내는 값을 가져옵니다. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | 스트림 길이를 바이트 단위로 가져오거나 설정합니다. 이 값은 다음보다 작습니다.LengthStreamContainer 생성자에 전달된 시작 스트림 위치로. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | 스트림 내의 현재 위치를 가져오거나 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | 데이터 스트림을 가져옵니다. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | 동기화된 리소스에 대한 액세스를 동기화하는 데 사용할 수 있는 개체를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | 이 스트림에 대한 모든 버퍼를 지우고 버퍼링된 데이터가 기본 장치에 기록되도록 합니다. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | 지정된 위치에 스트림 컨테이너를 삽입합니다. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | 바이트를 읽어 지정된 바이트 버퍼를 채웁니다. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | 현재 스트림에서 바이트 시퀀스를 읽고 읽은 바이트 수만큼 스트림 내의 위치를 앞으로 이동합니다. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | 스트림에서 바이트를 읽고 스트림 내의 위치를 1바이트씩 앞으로 이동하거나 스트림 끝에 있으면 -1을 반환합니다. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 사용[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 그리고 스트림[`Length`](../streamcontainer/length/) 값. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 기본 버퍼 크기 사용[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) 그리고 스트림[`Length`](../streamcontainer/length/) 값. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | 모든 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 스트림 사용[`Length`](../streamcontainer/length/) 값. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. 스트림 사용[`Length`](../streamcontainer/length/) 값. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | 스트림의 데이터를 지정된 스트림에 저장(복사)합니다. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | 현재 스트림 내의 위치를 설정합니다. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | 스트림 위치를 스트림의 시작 부분으로 설정합니다. 이 값은 StreamContainer 생성자에 전달된 시작 스트림 위치로부터의 오프셋을 나타냅니다. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | 스트림 데이터를Byte 배열. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | 스트림 데이터를Byte 배열. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | 지정된 모든 바이트를 스트림에 씁니다. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | 바이트 시퀀스를 현재 스트림에 쓰고 이 스트림 내에서 현재 위치를 쓴 바이트 수만큼 앞으로 이동합니다. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | 스트림의 현재 위치에 바이트를 쓰고 스트림 내의 위치를 1바이트씩 앞으로 이동합니다. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | 포함된 데이터를 다른 데이터로 복사합니다.[`StreamContainer`](../streamcontainer/) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | 포함된 데이터를 다른 데이터로 복사합니다.[`StreamContainer`](../streamcontainer/) . |

### 또한보십시오

* class [StreamContainer](../streamcontainer/)
* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


