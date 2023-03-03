---
title: RasterImage.SavePixels
second_title: .NET API 참조용 Aspose.PSD
description: RasterImage 방법. 픽셀을 저장합니다.
type: docs
weight: 520
url: /ko/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

픽셀을 저장합니다.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rectangle | Rectangle | 픽셀을 저장할 사각형입니다. |
| pixels | Color[] | 픽셀 배열입니다. |

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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* 네임스페이스 [Aspose.PSD](../../rasterimage/)
* 집회 [Aspose.PSD](../../../)


