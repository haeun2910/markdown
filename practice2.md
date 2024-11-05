# Markdown 

## 개요

### 소재

## 문단

그냥 작성하면 문단이 됩니다.
엔터를 넣어도 새 문단이 되지는 않아요

새 문단을 만들고 싶다면 엔터를 두번 작성하시면 됩니다.  
스페이스 두개(+엔터)의 경우 줄만 바꿉니다.



## 강조(emphasis)

강조애는 세가지 종류가 있습니다. 
*기울이기*, **굵게하기**, ***굵으면서 기울린***

## 인용문(quotation)

인용문이란 다른 사람이 한 말을 그대로 활용한 문장

> A quotation is written with '>'

즉 내가 작성하게 아닌, 누군가가 작성한 내용을 다시 사용하는 것을 알린다

> 그래도 지구는 돈다. - 갈린레요

## 목록

아침에 일어나서 할일

1. 일어나서
2. 세수하고
3. 공부하기

내가 사용할 수 있는 프로그램밍 언어

- Java
    - 8
    - 11
    - 17
- C
- JavaScript

내가 사용할 수 있는 os

- Windows
- Macos
- Linux
    - Ubuntu
    - Centos


김치볶음밥 재료

- 양념장
    - 감장
    - 고추장
    - 참기름
- 김치 

## 코드 

코드를 문단 내부에서 표현하고 싶다면
백틱을 활용한다. `System.out.printin("Hello World!");``

여러 줄의 코드를 표현하고 싶다면 백틱 세개씩으로 묶어준다.

``` 
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
````

만약 특정 프로그램밍 언어를 사용했다면, 해당 언어를 튿징지어줄 수 있다.

``` Java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

## 구분선

가로로 내용을 분리하고 싶다면

---

가로 구분선을 넣어줄 수 있다. 

## 링크

가장 간단한 인터넷 주소로 링크를 만들고 싶다면 <https://www.naver.com>, <http://google.com>

<https://us06web.zoom.us/j/82308487363?pwd=1umqwuODmzfDir4uyn3IKZqfa4ucxd.1> 킨 링크를 그냥 작성하면 읽기 어려우니까 특정 문자에 링크를 넣고 싶다면 `[]`와 `( )`를 같이 사용한다.  
[줌 링크](https://us06web.zoom.us/j/82308487363?pwd=1umqwuODmzfDir4uyn3IKZqfa4ucxd.1)

[네이버](https://naver.com)  
[google](http://google.com)  
[youtube](http://youtube.com)  
[마크다운](https://namu.wiki/w/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4)

## 이미지

링크를 만들되, 앞에 `!`를 추가하자.

폴더를 만들어서 이미지를 보관한다면,`폴더이름/이미지이름`으로 하면 된다


![마크다운 로고](images/markdown.png)
![Java Logo](images/java.png)

폴더를 만들어서 이미지를 보관한다면,`폴더이름/이미지이름`으로 하면 된다

웹상에서 이미지를 가져오고 싶다면 그냥 그 주소를 넣어주면 된다

![스프링 프레임워크 로고](https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Spring_Boot.svg/120px-Spring_Boot.svg.png)

![wikipedia 로고](https://www.wikipedia.org/portal/wikipedia.org/assets/img/Wikipedia-logo-v2@2x.png)

