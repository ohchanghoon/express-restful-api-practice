### Express RESTful API 연습


클라이언트에게 데이터를 전송하는 방식은 3가지가 있다.
1. Query Params (req.query.user_id)
2. Body (req.body.user_id)
3. Path Variables (req.params.user_id)

GET ( 조회 )
POST ( 생성 ) : 보통 Body에 데이터를 담아서 전송
PUT ( 전체 데이터 수정 ) : 보통 Body에 수정할 데이터 담아서 전송
PATCH ( 단일 데이터 수정 ) : 보통 Query Params, Path Variables와 Body를 혼합 사용
DELETE ( 삭제 ) : 보통 Query Params, Path Variables를 사용