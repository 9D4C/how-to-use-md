
# MARKEDOWN

�������������

---
TIP��Ctrl+�������л���Ӣ������

## һ���༶����
��������,������
># һ������
>## ��������
>### ��������

## ��������
### б��or����
>*б��* 
__����__ 
***��б��***

��ݼ� **�Ӵ�Ctrl+B** *б��Ctrl+I*
###
## ��������
ֱ����һ�仰���������ո�   
���仰֮���һ������

������ڱ༭��ʱ������һ����������ʾ��ʱ����<br/>�������м��***br/***.

## �ġ�����
>����
>>Ƕ������
>>>����

## �塢����
[��������](���ӵ�ַ)
<���ӵ�ַ>

>[�ö���](https://www.roxylib.com/)
or
><https://www.roxylib.com/>

## ����ͼƬ
>![ͼƬ��������д�ɲ�д������������Ҫ��](ͼƬ��ַ���������ӻ���URL��ַ��)

![Ҳ�Ǻö���](FUN.png)
�����һ���ļ�����

![][ / ͼƬ��.ͼƬ��ʽ]ת��Ϊ<img src = �ļ��� . ͼ Ƭ��ʽ / *�л�PDF*

## �ߡ��б�
�����б�ʹ��*��+��-���ټ�һ���ո���Ϊ�б�ı��

�����б�ʹ�����ֲ�����.�ţ��ټ�һ���ո���Ϊ�б�ı��
>���룺
* part one
+ part two
  - inside part 
    + TAB��������
>���룺
1. ����A
2. ����B
   1.  �ڲ�����TAB

## �ˡ�����
### �ָ���
---
д�ָ���ǰ��Ҫ��һ��֮��д������ᵼ��ǰһ������Ŵ�

---
***
- - -
* * *

### ɾ����
---
~~����Ҫ��ɾ��������~~

### �»���
---
<u>���������ѱ�����»���</u>

### �����
---
�����һ������Ҫ���ô��룬ֻ��Ҫ�÷�����`�������ͺ��ˡ�

`Hello` World.

---
�������һ��������Ҫ���ô��룬������Ҫ���õĴ�����ǰһ�кͺ�һ��ʹ�����������ţ�ͬʱ��ǰһ�������ź�д���������ԡ�
>֧����������bash,c��clojure��cpp��cs��css,dart,dockerfile, diff,erlang,go��gradle��groovy,haskell,java��javascript��json��julia,kotlin,lisp��lua,makefile��markdown��matlab,objectivec,perl��php��python,r��ruby��rust,scala��shell��sql��swift,tex��typescript,verilog��vhdl,xml,yaml

```c
#include<stdio.h>
int main (void)
{
    printf("fuck you");
    return 0;
}
```

### ��ע
---
- ʹ�� Markdown[^1]����Ч�ʵ���д�ĵ�, ֱ��ת���� HTML[^2], �����ʹ�� Typora[^T] �༭��������д��
  - [^1]:Markdown��һ�ִ��ı��������
  - [^2]:HyperText Markup Language ���ı��������
  - [^T]:NEW WAY TO READ & WRITE MARKDOWN.


### �������
---
����Markdown�е��﷨���ţ�ǰ��ҷ�б��\��������ʾ���ű���
>\\  
>\*  
>\_  
>\+  
>\.  
### ���
---
- ���ʹ��|���ָͬ�ĵ�Ԫ��ʹ��-���ָ���ͷ��������
  - :-  ����ͷ����Ԫ�����������
  - -:  ����ͷ����Ԫ�������Ҷ���
  - :-: ����ͷ����Ԫ�����ݾ���

| ��Ŀ   |   �۸� | ����  |
| :----- | -----: | :---: |
| ����� | \$1600 |   5   |
| �ֻ�   |   \$12 |  12   |
| ����   |    \$1 |  234  |

##  �š��߼��÷�

### ֧��HTMLԪ��
ʹ�� <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd> ����

### ��������
���ǿ���ʹ��Markdown������һ�����������ʽΪ��-[] ��ʾδ��ɣ�-[x]��ʾ�����
- [x] ����
- [ ] ������

### ��д��ʽ
����ʹ�� 2����Ԫ�� $ ���� TeX �� LaTeX ��ʽ����ѧ��ʽ��ʵ�֡�
/$$��ʾ���й�ʽ  
$$E=mc^2$$

�ϱ�ʹ�÷��� ^ ��Χ���±�ʹ�÷��� ~ ��Χ���༭����֧��ʱ���ɷֱ�ʹ�� HTML ��ǩ 6<sup>��superscript���� 6<sub>��subscript�������

### ����ͼ
#### ����ͼ
```mermaid
graph TD;
A-->B
A-->C
B-->D
C-->B
C-->D
```

---
```mermaid
graph TB
 
  id1(Բ�Ǿ���)--��ͨ��-->id2[����];
  subgraph ��ͼ
   id2==����==>id3{����}
   id3-.����.->id4>��������]
   id3--�޼�ͷ---id5((Բ��))
  end
```

---
#### ʱ��ͼ
```mermaid
sequenceDiagram
 
Alice->>John: Hello John, how are you?
loop Healthcheck
    John->>John: Fight against hypochondria
end
Note right of John: Rational thoughts!
     John-->>Alice: Great!
     John->>Bob   : How about you?
     Bob-->>John  : Jolly good!
```

---
#### ����ͼ
```mermaid
gantt
 
section Section
          Completed: done,   des1,       2014-01-06, 2014-01-08
          Active   : active, des2,       2014-01-07, 3d
         Parallel 1        : des3,   after des1, 1d
         Parallel 2        : des4,   after des1, 1d
         Parallel 3        : des5,   after des3, 1d
         Parallel 4        : des6,   after des4, 1d
```

---
#### ��ͼ
```mermaid
pie
 
  title Key elements in Product X
  "Calcium" : 42.96
  "Potassium" : 50.05
  "Magnesium" : 10.01
  "Iron" :  5
```

---
#### ״̬ͼ
```mermaid
stateDiagram
 
    [*]-->Active
    state Active {
        [*]-->NumLockOff
        NumLockOff-->NumLockOn : EvNumLockPressed
        NumLockOn-->NumLockOff : EvNumLockPressed
        --
        [*]-->CapsLockOff
        CapsLockOff-->CapsLockOn : EvCapsLockPressed
        CapsLockOn-->CapsLockOff : EvCapsLockPressed
        --
        [*]-->ScrollLockOff
        ScrollLockOff-->ScrollLockOn : EvCapsLockPressed
        ScrollLockOn-->ScrollLockOff : EvCapsLockPressed
            }
```

---
#### ���ͼ
```mermaid
classDiagram
 
  Class01 <|-- AveryLongClass: Cool
  <<interface>> Class01
  Class09-->C2: Where am i?
  Class09 --* C3
  Class09 --|> Class07
  Class07: equals()
  Class07: Object[] elementData
  Class01: size()
  Class01: int chimp
  Class01: int gorilla
  class Class10 {
    <<service>>
    int id
    size()
  }
```

---
#### ʵ���ϵͼ
```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```

---