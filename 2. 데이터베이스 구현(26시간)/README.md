## 데이터베이스 구현(26시간)
- 1일차(2시간) - DBMS 설치 및 설치 완료 보고서 작성하기
	- <a href='https://drive.google.com/drive/folders/1RWz7xpguByxxLRg2s5pNDiOPpPs-opEU?usp=share_link'>오라클11g 다운로드</a>
	- <a href='https://drive.google.com/drive/folders/133udgiyYSPo-pSAmLOUYkQG_KUrd_ZX2?usp=share_link'>dbweaver 다운로드</a>
	- 설치 완료 보고서
	  
	 <img src="https://raw.githubusercontent.com/yonggyo1125/JavaSpringA/master/2.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4%20%EA%B5%AC%ED%98%84(26%EC%8B%9C%EA%B0%84)/%EA%B0%95%EC%9D%98%EC%9E%90%EB%A3%8C/%EC%84%A4%EC%B9%98%EC%99%84%EB%A3%8C%20%EB%B3%B4%EA%B3%A0%EC%84%9C.png">
	
- 2~7일차(22시간) - 오라클로 배우는 데이터베이스 입문
	- <a href='https://github.com/yonggyo1125/curriculumOracle/tree/master/10%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EC%B6%94%EA%B0%80%2C%20%EC%88%98%EC%A0%95%2C%20%EC%82%AD%EC%A0%9C%ED%95%98%EB%8A%94%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%A1%B0%EC%9E%91%EC%96%B4'>10 데이터를 추가, 수정, 삭제하는 데이터 조작어</a>
	- <a href='https://github.com/yonggyo1125/curriculumOracle/tree/master/11%20%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98%20%EC%A0%9C%EC%96%B4%EC%99%80%20%EC%84%B8%EC%85%98'>11 트랜잭션 제어와 세션</a>
	- <a href='https://github.com/yonggyo1125/curriculumOracle/tree/master/12%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%A0%95%EC%9D%98%EC%96%B4'>12 데이터 정의어</a>
	- <a href='https://github.com/yonggyo1125/curriculumOracle/tree/master/13%20%EA%B0%9D%EC%B2%B4%20%EC%A2%85%EB%A5%98'>13 객체 종류</a>
	- <a href='https://github.com/yonggyo1125/curriculumOracle/tree/master/14%20%EC%A0%9C%EC%95%BD%20%EC%A1%B0%EA%B1%B4'>14 제약조건</a>
	- <a href='https://github.com/yonggyo1125/curriculumOracle/tree/master/15%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EA%B6%8C%ED%95%9C%2C%20%EB%A1%A4%20%EA%B4%80%EB%A6%AC'>15 사용자 권한, 롤 관리</a>
	- 테이블 명세 작성하기
		
- 7일차(2시간) - 본평가 진행


## 오라클 삭제 하기

- 시작 버튼 - 서비스 - 오라클 관련 서비스 모두 중지
- 오라클을 설치 했을때 지정한 경로에서 deinstall/deinstall.bat 파일을 찾아 관리자권한으로 실행한다.
- 레지스트리 제거 - 윈도우 시작버튼 클릭 - 실행 - regedit 엔터를 눌러 레지스트리 편집기를 켠다.
- 아래 경로에 들어가 보면 Oracle 관련 디렉토리들이 몇개 보이는데 모두 삭제하면 삭제가 완료된다.

```
HKEY_LOCAL_MACHINE\SOFTWARE\ORACLE
HKEY_LOCAL_MACHINE\SYSTEM\ORACLE
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet001\Services
HKEY_LOCAL_MACHINE\SYSTEM\ControlSet002\Services
HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services
```