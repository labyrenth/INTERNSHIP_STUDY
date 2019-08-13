1.Swagger란?
- REST API를 개발할때 문서작업이 최대의 걸림돌.
- 파라미터가 변경되거나 주소가 변경되었으나 실제 문서와 소스와 싱크가 맞지 않으면 아무리 문서를 잘 만들어도 소용이 없다.
- 변경된 소스를 그대로 RESTfull API 문서로 만들어 주는 것이 Swagger로써, NodeJS, Java, Python등 다양한 언어를 지원해준다.

2. Swagger 사용 예시
https://github.com/jojoldu/blog-code/tree/master/swagger

화면의 메소드들중, POST 기능을 하는 /api/member를 클릭하면 아래와 같은 화면이 나온다. 
여기서 Parameters의 Value에 그 메소드가 받을 수 있는 형태의 데이터를 JSON 형식으로 넣어서, 테스트 할 수 있다.
Swagger에선 해당 메소드가 받을 수 있는 Model Schema도 Parameter 화면에 표기해주고 있으니 보고 Value에 그대로 넣어주면 된다.
![ex_screenshot](./img/post-test.png)
위의 사진은 /api/member의 saveMember 메소드를 실행한 결과 (POST 방식)
![ex_screenshot](./img/find-all-result.png)
위의 사진은 /api/member의 findMembers 메소드를 실행한 결과. (GET 방식)
