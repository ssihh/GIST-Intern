######  - MP: MultiProcess / TP: ThreadProcess
### 병렬처리 참고링크

프로세스와 스레드 차이  
: https://gmlwjd9405.github.io/2018/09/14/process-vs-thread.html

병렬처리(Multiprocessing)를 통한 연산속도 개선  
: https://yganalyst.github.io/data_handling/memo_17_parallel/

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
