# GitHub Flavored Markdown

## Styling text
취소선도 사용할 수 있다.

`This is ~~Strikethrough~~.`  
This is ~~Strikethrough~~.

## Task lists
체크박스를 만들 수 있다.
```
- [x] Task1
- [x] Task2
- [ ] Taks3
```
- [x] Task1
- [x] Task2
- [ ] Taks3

## Using emoji
이모티콘을 사용할 수 있다.  
`:+1: :-1:`  
👍 👎

## Creating a table
표를 만들 수 있다.
```
C datatype
| Data type  | Storage size  |
| ---------- | ------------- |
| char   | 1byte  |
| int    | 4byte  |
| double | 8byte  |
```
C datatype
| Data type  | Storage size  |
| ---------- | ------------- |
| char   | 1byte  |
| int    | 4byte  |
| double | 8byte  |

## Fenced code blocks
코드를 표현할 때 IDE와 동일하게 구문 강조를 해준다.

\`\`\` (언어)  
  (코드)  
\`\`\`  
형식으로 작성
``````
``` c
//C
#include <stdio.h>
int main(){
  printf("Hello World\n");
  return 0;
}
```
``````

``` c
//C
#include <stdio.h>
int main(){
  printf("Hello World\n");
  return 0;
}
```

``` python
#Python
print("Hello World")
```

``` java
//Java
public class HelloWorld {
  public static void main(String[] args){
    System.out.println("Hello World");
  }
}
```
