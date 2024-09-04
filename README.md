# API
## 0904 , 회원 등록 API
1. @RestController
    - @Controller 와 @ResponseBody 합쳐진 에노테이션이다.

2. @RequsetBody
   - json,xml등 으로 넘어온 데이터를 변환하여 파라미터에 넣어준다.

3. @Vaild
   - 가 붙어 있으면 검증을 실행한다. @NotEmpty가 붙어있으면 값을 필수적으로 입력해야한다.

4. 실무에서는 엔티티를 파라미터에 노출시키면 안된다. 소위 dto라 하는 객체를 사용한다.