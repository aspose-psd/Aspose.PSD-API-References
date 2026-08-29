---
title: "Image.Create"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Image 메서드. 지정된 생성 옵션을 사용하여 새 이미지를 생성합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

지정된 생성 옵션을 사용하여 새 이미지를 생성합니다.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 이미지 옵션. |
| width | Int32 | 너비. |
| height | Int32 | 높이. |

### 반환 값

새로 생성된 이미지.

## 예제

이 예제는 PsdOptions 인스턴스의 Source 속성으로 지정된 디스크 위치에 새 Image 파일을 생성합니다. 실제 이미지를 만들기 전에 PsdOptions 인스턴스의 여러 속성이 설정됩니다. 특히 이 경우 실제 디스크 위치를 가리키는 Source 속성이 설정됩니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource의 인스턴스를 생성하고 이를 PsdOptions 인스턴스의 Source로 할당합니다.
//두 번째 Boolean 매개변수는 생성될 파일이 임시 파일인지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image 인스턴스를 생성하고 Create 메서드를 호출하여 PsdOptions 인스턴스로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //이미지 처리를 수행합니다.

    // 모든 변경 사항을 저장합니다.
    image.Save();
}
```

### 또 보기

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


