---
title: StreamSource.StreamSource
second_title: .NET API 참조용 Aspose.PSD
description: StreamSource 건설자. 의 새 인스턴스를 초기화합니다.StreamSource 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

의 새 인스턴스를 초기화합니다.[`StreamSource`](../) 클래스.

```csharp
public StreamSource(Stream stream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 열 스트림입니다. |

### 예

이 예제는 색상 유형의 배열에서 픽셀 정보를 로드하고 배열을 조작하여 이미지로 다시 설정하는 방법을 보여줍니다. 이러한 작업을 수행하기 위해 이 예제에서는 MemoryStream 개체를 사용하여 새 이미지 파일(PSD 형식)을 만듭니다.

```csharp
[C#]

//MemoryStream 인스턴스 생성
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions의 인스턴스를 만들고 Source 속성을 비롯한 다양한 속성을 설정합니다.
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //이미지 인스턴스 생성
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //영역을 이미지 경계로 지정하여 이미지의 픽셀을 가져옵니다.
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //배열을 반복하고 대체 인덱스 픽셀의 색상을 설정합니다.
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //인덱스 픽셀 색상을 노란색으로 설정
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //인덱스 픽셀 색상을 파란색으로 설정
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //픽셀 변경 사항을 이미지에 적용
        image.SavePixels(image.Bounds, pixels);

        // 모든 변경 사항을 저장합니다.
        image.Save();
    }

    //MemoryStream을 파일에 쓰기
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 또한보십시오

* class [StreamSource](../)
* 네임스페이스 [Aspose.PSD.Sources](../../streamsource/)
* 집회 [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`StreamSource`](../) 클래스.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 열 스트림입니다. |
| disposeStream | Boolean | 로 설정된 경우`진실` 스트림이 삭제됩니다. |

### 예

이 예제는 System.IO.Stream을 사용하여 새 이미지 파일을 만드는 방법을 보여줍니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream의 인스턴스 생성
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions 인스턴스의 소스 속성을 정의합니다.
//두 번째 부울 매개변수는 범위를 벗어나면 스트림이 삭제되는지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image 인스턴스를 생성하고 PsdOptions를 매개변수로 사용하여 Create 메서드를 호출하여 Image 객체를 초기화합니다.   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 일부 이미지 처리 수행
}
```

### 또한보십시오

* class [StreamSource](../)
* 네임스페이스 [Aspose.PSD.Sources](../../streamsource/)
* 집회 [Aspose.PSD](../../../)


