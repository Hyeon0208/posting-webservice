# 개발환경
1. IDE : 인텔리제이 커뮤니티
2. Spring Boot 2.7.12
3. JDK 11
4. MySQL
5. Spring Data JPA
6. Thymeleaf

# 게시판 주요기능
1. 글쓰기(/posts/save)
2. 글목록(/posts/)
3. 글조회(/posts/{id})
4. 글수정(/posts/update/{id})
    - 상세화면에서 수정 버튼 클릭
    - 서버에서 해당 게시글의 정보를 가지고 수정 화면 클릭
    - 제목, 내용 수정 입력 받아서 서버로 요청
    - 수정 처리
5. 글삭제(/posts/delete/{id})
6. 페이징처리(/posts/paging)
   - /posts/paging?page=2
   - /posts/paging/2