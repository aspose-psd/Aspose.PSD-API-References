---
title: Image.Create
second_title: .NET API 참조용 Aspose.PSD
description: Image 방법. 지정된 만들기 옵션을 사용하여 새 이미지를 만듭니다.
type: docs
weight: 10
url: /ko/net/aspose.psd/image/create/
---
## Image.Create method

지정된 만들기 옵션을 사용하여 새 이미지를 만듭니다.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | 이미지 옵션. |
| width | Int32 | 너비. |
| height | Int32 | 높이. |

### 반환 값

새로 생성된 이미지입니다.

### 예

이 예에서는 PsdOptions 인스턴스의 Source 속성에 지정된 일부 디스크 위치에 새 이미지 파일을 만듭니다. 실제 이미지를 생성하기 전에 PsdOptions 인스턴스에 대한 여러 속성이 설정됩니다. 특히 이 경우 실제 디스크 위치를 나타내는 Source 속성입니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource의 인스턴스를 생성하고 PsdOptions 인스턴스의 소스로 할당합니다.
//두 번째 부울 매개변수는 생성할 파일이 IsTemporal인지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Create 메서드를 호출하여 Image 인스턴스를 만들고 PsdOptions 인스턴스로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 일부 이미지 처리 수행

    // 모든 변경 사항 저장
    image.Save();
}
```

### 또한보십시오

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)


