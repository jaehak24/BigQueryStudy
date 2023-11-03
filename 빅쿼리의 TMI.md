# BigQuery

## BigQuery란?
> * 분석을 위한 Data Cloud Platform의 엔터프라이즈 데이터 웨어하우스
> * 페타 바이트 급 스토리지 및 쿼리
> * 표준 SQL과 같은 문법으로 편리함
> * 암호화, 내구성 및 높은 가용성
>> 전송 + 저장에 대한 암호화도 진행
> * 완전 관리 및 server-less
> * 스트리밍 데이터에 대한 실시간 분석

## Data storage 측면에서 Big Query의 변천사
1. Data warehous
> 1세대 EDW에서 증가 된 데이터 수집 및 분석은 더 많은 
데이터 기반 비즈니스를 구착하는 데 도움

2. BI foundations
> Data warehousing은 리포팅 및 비즈니스 인텔리전스 기반으로 형성

3. Data Analytics
> BigQuery는 클라우드 Data warehousing과 근본적으로 다른 체계적 Data Analytics 접근 방식을 보여줌

4. Ai foundations
> 비즈니스에서 머신러닝을 활용하여 조직을 위한 Bigquery를 만들기 위해 노력하고 있음


## 분석에만 집중할 수 있도록 <u><b>스토리지 엔진이 데이터 저장 및 복제 방식을 지속적으로 관리</b></u>하기 때문에 Vaccume 프로세스가 필요 없음
> Legion의 capacity에 의해서만 scalabiliy가 영향을 받음

## 기존의 방식인 리소스 접근자에게 데이터를 복사해서 주는 방식이 아니라, 공유 방식으로 리소스를 접근자에게 제공
* 데이터 변경 시 추가 동기화 작업 없이 <b><u>항상 최신 데이터 조회</u></b> 가능
* 컴퓨팅 노드는 직접 돌리는 부서의 자원을 활용하여 비용도 분리 가능
