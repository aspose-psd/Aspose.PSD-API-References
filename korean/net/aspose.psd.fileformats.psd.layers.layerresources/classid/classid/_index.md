---
title: ClassID.ClassID
second_title: .NET API 참조용 Aspose.PSD
description: ClassID 건설자. 의 새 인스턴스를 초기화합니다.ClassID 클래스.
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources/classid/classid/
---
## ClassID(byte[]) {#constructor}

의 새 인스턴스를 초기화합니다.[`ClassID`](../) 클래스.

```csharp
public ClassID(byte[] classID)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| classID | Byte[] | 일련의 바이트로 된 클래스 ID입니다. |

### 또한보십시오

* class [ClassID](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 집회 [Aspose.PSD](../../../)

---

## ClassID(byte[], bool) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`ClassID`](../) 클래스.

```csharp
public ClassID(byte[] classID, bool isZeroLength)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| classID | Byte[] | 일련의 바이트로 된 클래스 ID입니다. |
| isZeroLength | Boolean | 로 설정된 경우`진실` [길이가 0임]. 기록된 문자열 길이는 0이지만 실제 길이는 4입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | classID가 null입니다. |

### 또한보십시오

* class [ClassID](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 집회 [Aspose.PSD](../../../)

---

## ClassID(int) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`ClassID`](../) 클래스.

```csharp
public ClassID(int classID)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| classID | Int32 | 클래스 ID입니다. |

### 또한보십시오

* class [ClassID](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 집회 [Aspose.PSD](../../../)

---

## ClassID(uint) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`ClassID`](../) 클래스.

```csharp
public ClassID(uint classID)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| classID | UInt32 | 클래스 ID입니다. |

### 또한보십시오

* class [ClassID](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 집회 [Aspose.PSD](../../../)

---

## ClassID(string, bool) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`ClassID`](../) 클래스.

```csharp
public ClassID(string classID, bool isZeroLength)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| classID | String | ASCII 인코딩의 클래스 ID입니다. |
| isZeroLength | Boolean | 로 설정된 경우`진실` [길이가 0입니다]. |

### 예

이 예제는 이미지에서 가져온 레이어가 스마트 오브젝트 레이어로 변환되고 저장된 PSD 파일이 올바른지 보여줍니다.

```csharp
[C#]

// 이미지에서 가져온 레이어가 스마트 오브젝트 레이어로 변환되고 저장된 PSD 파일이 올바른지 테스트합니다.

string outputFilePath = outputFolder + Path.DirectorySeparatorChar + "layerTest2.psd";
string outputPngFilePath = Path.ChangeExtension(outputFilePath, ".png");
using (PsdImage image = (PsdImage)Image.Load(baseFolder + Path.DirectorySeparatorChar + "layerTest1.psd"))
{
    string layerFilePath = baseFolder + Path.DirectorySeparatorChar + "picture.jpg";
    using (var stream = new FileStream(layerFilePath, FileMode.Open))
    {
        Layer layer = null;
        try
        {
            layer = new Layer(stream);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }

        var layer2 = image.Layers[2];
        var layer3 = image.SmartObjectProvider.ConvertToSmartObject(image.Layers.Length - 1);
        var bounds = layer3.Bounds;
        layer3.Left = (image.Width - layer3.Width) / 2;
        layer3.Top = layer2.Top;
        layer3.Right = layer3.Left + bounds.Width;
        layer3.Bottom = layer3.Top + bounds.Height;

        image.Save(outputFilePath);
        image.Save(outputPngFilePath, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 또한보십시오

* class [ClassID](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 집회 [Aspose.PSD](../../../)

---

## ClassID(string) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`ClassID`](../) 클래스.

```csharp
public ClassID(string classID)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| classID | String | ASCII 인코딩의 클래스 ID입니다. |

### 또한보십시오

* class [ClassID](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../classid/)
* 집회 [Aspose.PSD](../../../)


