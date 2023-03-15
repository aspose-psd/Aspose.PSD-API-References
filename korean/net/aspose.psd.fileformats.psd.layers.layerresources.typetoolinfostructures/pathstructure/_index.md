---
title: Class PathStructure
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures.PathStructure 수업. 경로 구조.
type: docs
weight: 3220
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/
---
## PathStructure class

경로 구조.

```csharp
public sealed class PathStructure : OSTypeStructure
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PathStructure](pathstructure/)(ClassID) | 의 새 인스턴스를 초기화합니다.`PathStructure` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/) { get; } | 구조 키를 가져옵니다. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | 키 이름을 가져오거나 설정합니다. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/) { get; } | 가져오기[`OSTypeStructure`](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) 바이트 길이. |
| [Path](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/) { get; set; } | 경로를 가져오거나 설정합니다. |
| [Prefix](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/) { get; set; } | 경로 접두사를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | 헤더 길이를 가져옵니다. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | 지정된 스트림 컨테이너에 구조를 저장합니다. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | 지정된 스트림 컨테이너에 구조를 저장합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/) | 구조 키를 식별합니다. |

### 예

다음 코드는 PathStructure 구조로 파일을 로드하는 기능을 보여줍니다.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### 또한보십시오

* class [OSTypeStructure](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* 집회 [Aspose.PSD](../../)


