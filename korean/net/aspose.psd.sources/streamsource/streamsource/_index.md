---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "StreamSource 생성자. StreamSource 클래스의 새 인스턴스를 초기화합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

[`StreamSource`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public StreamSource(Stream stream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 열 스트림. |

## 예제

이 예제는 Color 유형의 배열에 픽셀 정보를 로드하고, 배열을 조작한 뒤 이미지에 다시 설정하는 방법을 보여줍니다. 이러한 작업을 수행하기 위해 이 예제는 MemoryStream 객체를 사용하여 새 Image 파일(PSD 형식)을 생성합니다.

```csharp
[C#]

//MemoryStream의 인스턴스를 생성합니다.
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Source 속성을 포함한 다양한 속성을 설정하면서 PsdOptions의 인스턴스를 생성합니다.
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image의 인스턴스를 생성합니다.
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //이미지 경계를 영역으로 지정하여 이미지의 픽셀을 가져옵니다
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //배열을 순회하고 대체 인덱스 픽셀의 색상을 설정합니다
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //인덱스된 픽셀 색상을 노란색으로 설정합니다
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //인덱스된 픽셀 색상을 파란색으로 설정합니다
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //픽셀 변경을 이미지에 적용합니다
        image.SavePixels(image.Bounds, pixels);

        // 모든 변경 사항을 저장합니다.
        image.Save();
    }

    //MemoryStream을 파일에 씁니다
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### 또 보기

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

[`StreamSource`](../) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 열 스트림. |
| disposeStream | Boolean | `true` 로 설정하면 스트림이 해제됩니다. |

## 예제

이 예제는 System.IO.Stream을 사용하여 새 이미지 파일을 생성하는 방법을 보여줍니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream의 인스턴스를 생성합니다.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions 인스턴스의 source 속성을 정의합니다.
//두 번째 부울 매개변수는 스트림이 범위를 벗어나면 폐기되는지를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image의 인스턴스를 생성하고 PsdOptions를 매개변수로 전달하여 Create 메서드를 호출해 Image 객체를 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //이미지 처리를 수행합니다.
}
```

### 또 보기

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


