---
title: LayerMaskData.MaskRectangle
second_title: .NET API 참조용 Aspose.PSD
description: LayerMaskData 재산. 마스크를 가져오거나 설정합니다.RectanglePSD 파일에서 레이어 마스크의 왼쪽 오른쪽 위쪽 아래쪽 속성을 가져와 생성합니다.Rectangle
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/
---
## LayerMaskData.MaskRectangle property

마스크를 가져오거나 설정합니다.[`Rectangle`](../../../aspose.psd/rectangle/)PSD 파일에서 레이어 마스크의 왼쪽, 오른쪽, 위쪽, 아래쪽 속성을 가져와 생성합니다.[`Rectangle`](../../../aspose.psd/rectangle/)

```csharp
public Rectangle MaskRectangle { get; set; }
```

### 자산 가치

마스크 사각형.

### 예

이 예제는 프로그래밍 방식으로 Adobe® Photoshop® 파일에서 래스터 레이어 마스크를 가져오고, 업데이트하고, 제거하고, 추가하는 방법을 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(
            string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

// big-endian 바이트 순서로 변환된 int 값을 가져옵니다.
byte[] GetBigEndianBytesInt32(int value)
{
    byte[] bytes = new byte[4];
    bytes[0] = (byte)((value >> 24) & 0x000000FF);
    bytes[1] = (byte)((value >> 16) & 0x000000FF);
    bytes[2] = (byte)((value >> 8) & 0x000000FF);
    bytes[3] = (byte)value;
    return bytes;
}

// big endian에서 Int32로 변환된 값을 가져옵니다.
int FromBigEndianToInt32(byte[] bytes, int index)
{
    if (bytes == null)
    {
        throw new ArgumentNullException("bytes");
    }

    if (index < 0 || index + 4 > bytes.Length)
    {
        throw new ArgumentOutOfRangeException("index", "The index falls outside the bytes array.");
    }

    return (bytes[index] << 24) | (bytes[index + 1] << 16) | (bytes[index + 2] << 8) | bytes[index + 3];
}

// PSD 이미지의 레이어에서 래스터 마스크를 가져와 파일에 저장
void SaveRasterMask(string maskFilePath, Layer layer)
{
    LayerMaskDataShort maskData = (LayerMaskDataShort)layer.LayerMaskData;

    using (var container = FileStreamContainer.CreateFileStream(maskFilePath, false))
    {
        container.Write(GetBigEndianBytesInt32(maskData.Top));
        container.Write(GetBigEndianBytesInt32(maskData.Left));
        container.Write(GetBigEndianBytesInt32(maskData.Bottom));
        container.Write(GetBigEndianBytesInt32(maskData.Right));
        container.WriteByte(maskData.DefaultColor);
        container.WriteByte((byte)maskData.Flags);
        container.Write(GetBigEndianBytesInt32(maskData.ImageData.Length));
        container.Write(maskData.ImageData, 0, maskData.ImageData.Length);
    }
}

// 파일에서 레이어로 래스터 마스크를 추가하고 PSD 형식 이미지로 저장합니다.
void AddRasterMask(Layer layer, string maskSourcePath)
{
    var maskData = new LayerMaskDataShort();
    using (FileStreamContainer container = FileStreamContainer.OpenFileStream(maskSourcePath))
    {
        byte[] bytes = new byte[22];
        AssertAreEqual(container.Read(bytes), 22);
        maskData.Top = FromBigEndianToInt32(bytes, 0);
        maskData.Left = FromBigEndianToInt32(bytes, 4);
        maskData.Bottom = FromBigEndianToInt32(bytes, 8);
        maskData.Right = FromBigEndianToInt32(bytes, 12);
        maskData.DefaultColor = bytes[16];
        maskData.Flags = (LayerMaskFlags)bytes[17];
        int imageDataLength = FromBigEndianToInt32(bytes, 18);
        byte[] data = new byte[imageDataLength];
        AssertAreEqual(maskData.MaskRectangle.Width * maskData.MaskRectangle.Height, imageDataLength);
        AssertAreEqual(container.Read(data), imageDataLength);
        maskData.ImageData = data;
    }

    // LayerMaskData를 추가하는 것만으로는 채널이 업데이트되지 않기 때문에 올바른 저장에 충분하지 않습니다.
    // layer.LayerMaskData = 마스크; // 이것은 마스크 채널을 추가하지 않습니다.

    // 마스크 추가(또는 업데이트)
    layer.AddLayerMask(maskData); // 그러나 이것은 마스크와 채널을 모두 추가/업데이트합니다!
}

// 이 예제는 프로그래밍 방식으로 Adobe® Photoshop® 파일에서 래스터 레이어 마스크를 가져오고, 업데이트하고, 제거하고, 추가하는 방법을 보여줍니다.
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
var sourceFilePath = "FourWithMasks.psd";
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    Layer layer = image.Layers[2];

    // 레이어에서 래스터 마스크를 가져와 파일에 저장
    SaveRasterMask("FourWithMasks2.msk", layer);

    // 레이어 마스크 변경(반전) 및 이미지 저장
    var mask = layer.LayerMaskData;
    byte[] maskData = mask.ImageData;
    for (int i = 0; i < maskData.Length; i++)
    {
        maskData[i] = (byte)~maskData[i];
    }

    // LayerMaskData를 변경하는 것만으로도 렌더링 효과를 얻을 수 있습니다.
    image.Save("FourWithMasksUpdated2.png", pngOptions);

    // 그러나 LayerMaskData를 변경하는 것만으로는 채널이 업데이트되지 않기 때문에 올바른 저장에 충분하지 않습니다.
    layer.LayerMaskData = mask; // 이것도 작동하지 않습니다
    layer.AddLayerMask(mask); // 그러나 이것은 마스크와 채널을 모두 업데이트합니다!
    image.Save("FourWithMasksUpdated2.psd");

    // 레이어에서 래스터 마스크를 제거하고 이미지를 저장합니다.
    layer.LayerMaskData = null; // LayerMaskData를 제거하는 것만으로도 렌더링 효과를 얻을 수 있지만 PSD 형식으로 저장하기에는 충분하지 않습니다.
    image.Save("FourWithMasksRemoved2.png", pngOptions);

    layer.AddLayerMask(null); // 그러나 이것은 마스크와 마스크 채널을 모두 제거합니다!
    image.Save("FourWithMasksRemoved2.psd");

    // 파일의 래스터 마스크를 레이어에 추가하고 이미지를 저장합니다.
    AddRasterMask(layer, "raster.msk");
    image.Save("FourWithMasksAdded2.png", pngOptions);
    image.Save("FourWithMasksAdded2.psd");
}
```

### 또한보십시오

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [LayerMaskData](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers](../../layermaskdata/)
* 집회 [Aspose.PSD](../../../)


