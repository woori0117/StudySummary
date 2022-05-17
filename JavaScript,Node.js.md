스터디 요약 및 정리

<     JavaScript     >

데이터 타입 => 문자열,숫자,Boolean(true,false),배열....

비교연산자 c언어 == -> ===

css 선택자 => class=“” 제어 .js{} 광범위 / id=“” 제어 #id이름 예외 처리

조건문 => if(조건){ } else{ }

리펙토링 => 중복의 제거 => ‘중복된 것들을 줄이다 보면 좋은 코딩이 된다‘

배열 => var 변수이름 = [“배열1”,“배열2”,“배열3”]; / 파이썬의 list 와 동일하다보면 될 듯
        변수이름.length -> 변수 개수

반복문 => while(조건){반복할 명령} -> 조건을 만족하지 않으면 반복 중단

함수 => function 함수이름(자기자신,다른 변수...등){함수}

객체 => 이름이 있는 정리정돈 상자
        var 객체이름 = { “정보 이름”:“정보”} ex) “programmer”:“woori”
        정보 꺼내오기 document.write(“programmer : ”+ 객체이름.programmer);
        var 부분을 수정하지않고 중간에 정보추가 가능 
        공백을 넣고 싶을 때 -> 객체이름[“정보이름”]=“정보”

<     Node.js     >

서버열기 => 열고 싶은 웹페이지의 파일경로로 설정 -> node 이름.js 입력

접속 => localhost:port

데이터 타입 => 문자열,숫자,Boolean,배열....

URL => protocol://host(doamin):port(숫자)/path?query string

파이썬의 format string 기능 => ${변수이름}

파일 읽기 => fs.readdir('./data', function(error, filelist){ };

== -> 좌항과 우항이 같으냐 / === -> 정확히 같냐

제어문 => cosole.log()

조건문,반복문,배열 => JavaScript 와 동일

함수 => function 함수명(){명령}

Math.round(소수) => 반올림 or 반내림

function 함수명(변수1, 변수2){ } => 변수 2개 사용

함숫값은 항상 console.log를 통해서 출력 -> return 사용 시 함숫값을 더 광범위하게 사용가능 

Form => <input type="text" name="title"> <textarea name="description"></textarea>

객체 안의 함수 => 함수이름:function(){ }   / 호출 => 객체이름.함수이름() -> 이런 식으로 사용하면 함수이름 중복 사용 가능

모듈 => 가장 큰 정리 도구 -> var M = { v:'v',f:function() { console.log(this.v);}} 
                                    module.exports = M;
                                  => 외부에서도 M 객체를 호출하여 사용가능

 






