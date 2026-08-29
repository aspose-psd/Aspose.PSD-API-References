---
title: "IOrderedShape"
second_title: "Java용 Aspose.PSD API 참조"
description: "정렬된 형태를 나타냅니다."
type: docs
weight: 129
url: /ko/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

정렬된 형태를 나타냅니다. 정렬된 형태는 시작점과 끝점을 갖는 연속적인 점들의 집합이며, 특정 규칙을 사용하여 연결된 연속적인 점들의 집합입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | 끝 형태 점을 가져옵니다. |
| [getStartPoint()](#getStartPoint--) | 시작 형태 점을 가져옵니다. |
| [isClosed()](#isClosed--) | 정렬된 형태가 닫혀 있는지 여부를 나타내는 값을 가져옵니다. |
| [reverse()](#reverse--) | 이 형태의 점 순서를 반전시킵니다. |
| [setClosed(boolean value)](#setClosed-boolean-) | 정렬된 도형이 닫혀 있는지 여부를 나타내는 값을 설정합니다. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


끝 형태 점을 가져옵니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


시작 형태 점을 가져옵니다.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


정렬된 도형이 닫혀 있는지 여부를 나타내는 값을 가져옵니다. 닫힌 정렬된 도형을 처리할 때 시작점과 끝점은 의미가 없습니다.

**Returns:**
boolean - 이 정렬된 도형이 닫혀 있으면 true; 그렇지 않으면 false.
### reverse() {#reverse--}
```
public abstract void reverse()
```


이 형태의 점 순서를 반전시킵니다.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


정렬된 도형이 닫혀 있는지 여부를 나타내는 값을 설정합니다. 닫힌 정렬된 도형을 처리할 때 시작점과 끝점은 의미가 없습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 정렬된 도형이 닫혀 있으면 true; 그렇지 않으면 false. |

