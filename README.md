# errorMessage

####java.lang.NoClassDefFoundError: org/apache/ibatis/cursor/Cursor

이것을 spring과 연동해 주는 mybatis-spring의 버전을 맞춰줘야 하는데 그렇지  않아서 발생하였다.

그러면 각각의 버전이 서로 다양한데 어떤 버전이 어떻게 매칭되는지 어떻게 알수 있을까?

http://mvnrepository.com/ 에서 사용하고자 하는 라이브러리를 검색하고 해당 버전을

선택하면

 다음과 같이 매칭되는 관련 라이브러리와 버전이 명시되어 있다..

따라서 개발시 반드시 관련 라이브러리를 사용한다면 버전을 맞춰줘야 할 것이다.

####org.springframework.beans.factory.BeanCreationException
bean이 객체를 찾지 못해서 발생하는 현상(annotation)

@Repository를 붙여보기

    @Repository
    public class 클리스이름 {

    }
