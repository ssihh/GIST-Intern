# GIST-Intern
2020.10~12 광주과학기술원 기계공학부 인턴 기간 중, 작성한 Python 코드

####  - MP: MultiProcess / TP: ThreadProcess

### 참고링크

프로세스 계획서 양식  
: http://www.swbank.kr/html/pdf/sample/project_plan_guide.pdf

NoSQL 배경  
: https://kin.naver.com/qna/detail.nhn?d1id=1&dirId=10205&docId=345252384&qb=bm9zcWwgaGFkb29w&enc=utf8&section=kin.ext&rank=1&search_sort=0&spq=0

프로세스와 스레드 차이  
: https://gmlwjd9405.github.io/2018/09/14/process-vs-thread.html

병렬처리(Multiprocessing)를 통한 연산속도 개선  
: https://yganalyst.github.io/data_handling/memo_17_parallel/

인공지능데이터셋구축  
:https://aihub.or.kr/sample/intro/%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%85%8B%20%EA%B5%AC%EC%B6%95%20%EA%B0%80%EC%9D%B4%EB%93%9C%EB%B6%81_2%EC%87%84.pdf

기술 검토의견 예시  
: http://ebook.qia.go.kr/src/viewer/main.php?host=main&site=20180911_085516&category=1&page=93&search=%C1%B6%B7%F9%C0%CE%C7%C3%B7%E7%BF%A3%C0%DA%BF%A1+%B4%EB%C7%D1+%C0%CC%C7%D8

가이드라인 검토의견서 예시  
: http://www.pjgs.es.kr/wah/main/bbs/board/view.htm?menuCode=1673&pageNo=2&scale=10&searchField=&searchKeyword=&cateCode=&domain.topThread=51667&domain.depth=0&domain.dataNo=53455


파일, 폴더 복사  
: https://code.tutsplus.com/ko/tutorials/file-and-directory-operations-using-python--cms-25817

파일리스트  
: https://minstar0410.tistory.com/18

파이썬 GIL 정책 멀티프로세싱  
: https://monkey3199.github.io/develop/python/2018/12/04/python-pararrel.html

Pool 멀티프로세싱  
: https://niceman.tistory.com/145

#### - cpu 개수 확인 코드  
import multiprocessing  
num_cores = multiprocessing.cpu_count()  
print(num_cores) # 8


멀티스레드, 멀티프로세스 시간 단축(크롤링.ver)  
: https://medium.com/@keyhyuk.kim/python-%ED%81%AC%EB%A1%A4%EB%9F%AC-%EB%A9%80%ED%8B%B0%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4-%EB%A9%80%ED%8B%B0%EC%8A%A4%EB%A0%88%EB%93%9C%EB%A1%9C-%EC%84%B1%EB%8A%A5-%EC%A5%90%EC%96%B4%EC%A7%9C%EA%B8%B0-a7712bcbaa4
