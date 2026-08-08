---
title: "LayerHashCalculator"
second_title: "Java용 Aspose.PSD API 참조"
description: "PSD 레이어용 해시 계산기."
type: docs
weight: 20
url: /ko/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

PSD 레이어용 해시 계산기. 서로 다른 PSD 파일에서 동일하거나 다른 레이어를 찾는 데 사용할 수 있습니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | 새 인스턴스를 초기화합니다. [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | 블렌딩 해시를 가져옵니다. |
| [getChannelsHash()](#getChannelsHash--) | 채널 해시를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | 콘텐츠 해시를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerHashCalculator(Layer layer) {#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public LayerHashCalculator(Layer layer)
```


새 인스턴스를 초기화합니다. [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator) 클래스.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | 레이어. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


블렌딩 해시를 가져옵니다.

**Returns:**
int - 레이어 블렌딩 옵션에 대한 고유 해시
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


채널 해시를 가져옵니다.

**Returns:**
int - 모든 레이어 채널의 해시
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentHash() {#getContentHash--}
```
public final int getContentHash()
```


콘텐츠 해시를 가져옵니다.

**Returns:**
int - 레이어의 중요한 매개변수에 대한 해시입니다. 이 해시는 모든 레이어 유형마다 다릅니다.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

