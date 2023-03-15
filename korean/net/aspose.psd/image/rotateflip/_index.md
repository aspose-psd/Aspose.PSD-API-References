---
title: Image.RotateFlip
second_title: .NET API 참조용 Aspose.PSD
description: Image 방법. 이미지를 회전 뒤집기 또는 회전하고 뒤집습니다.
type: docs
weight: 220
url: /ko/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

이미지를 회전, 뒤집기 또는 회전하고 뒤집습니다.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | 회전 뒤집기의 유형입니다. |

### 예

이 예제는 이미지에서 회전 작업을 사용하는 방법을 보여줍니다. 예제는 일부 디스크 위치에서 기존 이미지 파일을 로드하고 Enum Aspose.PSD.RotateFlipType 값에 따라 이미지에서 회전 작업을 수행합니다.

```csharp
[C#]

//이미지 클래스의 인스턴스를 생성하고 파일 경로를 통해 기존 이미지 파일로 초기화
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //이미지를 X축으로 180도 회전
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // 모든 변경 사항을 저장합니다.
    image.Save();
}
```

### 또한보십시오

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)


