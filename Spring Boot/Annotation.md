## Annotation 이란?
자바에서 어노테이션은 사전적의미로 주석이라는 의미로 소스코드에 추가해서 사용할 수 있는 메타 데이터의 일종이다.

여기서 메타데이터란 애플리케이션이 처리해야할 데이터가 아닌, 컴파일 과정과 실행 과정에서 코드를 어떻게 처리해야하는지 알려주기 위한 추가 정보다

## @Override

```java
@Override 
public void getInfo() {
    System.out.println("test");
}
```
메소드를 오버라이딩 하겠다는 의미로 메소드의 선언 앞에 붙여준다. 

## @Nullable 
```java
	Model addAttribute(String attributeName, @Nullable Object attributeValue);

```
널도 허용한다.