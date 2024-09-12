# API
## 0904 , 회원 등록 API
1. @RestController
    - @Controller 와 @ResponseBody 합쳐진 에노테이션이다.

2. @RequsetBody
   - json,xml등 으로 넘어온 데이터를 변환하여 파라미터에 넣어준다.

3. @Vaild
   - 가 붙어 있으면 검증을 실행한다. @NotEmpty가 붙어있으면 값을 필수적으로 입력해야한다.

4. 실무에서는 엔티티를 파라미터에 노출시키면 안된다. 소위 dto라 하는 객체를 사용한다.

## 0906
1. fetch join
   - fetch join이란  SQL에서 사용하는 조인 종류가 아니고 JPQL에서 사용하는 성능 최적화를 위한 기능이다.
   - 연관된 엔티티나 컬렉션을 한 번에 같이 조회하는 기능이다.

## 0912
1. dsitinct 기능
   - JPA의 distinct는 SQL에 distinct를 추가한다(DB에 distinict 키워드롤 날려준다.)
   - 엔티티가 중복인 경우에 중복을 걸러서 컬랙션에 담아준다.
   - 단점 : 페이징이 불가능하다.
   