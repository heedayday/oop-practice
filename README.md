# 객체 지향 프로그래밍 4가지 특징
### 추상화, 상속, 다형성, 캡슐화

# 프로젝트 주요내용
### 자바 단위 데스트 프레임워크 JUnit5, AssertJ 학습
https://junit.org/junit5/docs/current/user-guide/#writing-tests
https://www.petrikainulainen.net/programming/testing/junit-5-tutorial-writing-parameterized-tests/
https://assertj.github.io/doc/#assertj-core-assertions-guide

# 
* Calculator 기능
</br>연산자를 통해서 사칙연산 계산하는 계산 프로그램

* 학점계산기
</br>평균학점계산 = (학점수X교과목평점)의 합계/수강신청 총학점 수
</br>Course 객체에서 계산처리하도록 함으로써 해당 객체에게 작업을 위임하여 응집도가 높아짐
</br>이는 getter로 값을 그냥 가져와 처리하는 것이 아니라 해당 데이터를 가진 객체에게 메시지를 던져서 작업을 처리하여 변화에 유연한 코드로 작성
