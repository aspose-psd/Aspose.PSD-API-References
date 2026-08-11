---
title: "Image.RotateFlip"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Image 메서드. 이미지를 회전, 뒤집기 또는 회전 후 뒤집습니다."
type: docs
weight: 230
url: /ko/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

이미지를 회전하거나 뒤집거나 회전 및 뒤집기를 수행합니다.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | rotate flip의 유형. |

## 예제

이 예제는 이미지에 대한 Rotate 작업 사용을 보여줍니다. 예제는 디스크 위치에서 기존 이미지 파일을 로드하고 Enum Aspose.PSD.RotateFlipType 값에 따라 이미지에 Rotate 작업을 수행합니다.

```csharp
[C#]

//image 클래스의 인스턴스를 생성하고 파일 경로를 통해 기존 이미지 파일로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //이미지를 X축을 기준으로 180도 회전합니다.
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // 모든 변경 사항을 저장합니다.
    image.Save();
}
```

### 또 보기

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


