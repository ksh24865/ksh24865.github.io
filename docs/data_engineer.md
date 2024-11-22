<h2>[원본 링크] https://ksh24865.github.io/data_engineer </h2>

<h1>김성호</h1>
<p>안녕하세요. 4년차 백엔드 엔지니어 김성호 입니다.</p>

<br/><br/>

<h1>💻 Career Summary</h1>   

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<div style="flex: 1;">
  <h2>Laplace Technologies, Inc.</h2>
  <p><strong>Backend Engineer</strong><br/>2021.06 - </p>
</div>

<div style="flex: 3;">
  <h3>커머스 데이터 파이프라인 구축</h3>
  
  <p><strong>Description.</strong><br/>
  <br/>
  400개 이상의 고객사를 대상으로 쇼핑몰, 광고 플랫폼, 웹로그 등의 커머스 관련 데이터를 처리하는 ETL 파이프라인을 구축하여 일 평균 200만 개의 데이터를 처리
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>Airflow를 이용해 배치 파이프라인 스케줄링 Dag 개발</li>
    <li>Spark 및 Trino 최적화를 통해 처리 성능 향상(대략 <strong>20%</strong>이상의 데이터 처리 비용 절감)</li>
    <li>데이터 품질 및 쿼리 성능 향상을 위한 데이터 웨어하우스 구축</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>Airflow, Spark, Trino, Iceberg, Deltalake, AwsS3, Kubernetes, Python, Java</p>
  
  <hr/>
  <h3>커머스 데이터 웨어하우스, 데이터 마트 구축</h3>
  <ul>
    <li>trino <-> hive-metastore <-> s3</li>
    <li>내가 롤업하고, ad_order, item_order, .. 등등 데이터 나눠놓은걸 데이터 마트 구축한 것으로 잘 설명 필요</li>
    <li>데이터 품질 및 쿼리 성능 향상을 위한 데이터 웨어하우스 구축</li>
  </ul>
  
  <hr/>
  <h3>대시보드 API 서버 구축</h3>
  
  <p><strong>Description.</strong><br/>
  500개 이상의 커머스 BI 데이터 지표에 대해 분석 및 시각화 하는 대시보드 API 서버를 설계 및 구축
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>대시보드 설정 정보를 요청 받아 데이터를 집계하여 제공하는 서비스 구현</li>
    <li>API 서버 및 분산 쿼리 시스템의 단위별 캐싱을 통해 대시보드 조회 성능 개선</li>
    <li>커스텀 대시보드 쿼리 제너레이터 구축</li>
    <ul>
    <li>데이터 마트 간의 조인을 통해 다양한 데이터 창출 (단례로 웹로그, 회원, 주문 데이터로 퍼널 분석 | 광고, 주문 데이터로 광고 실적 분석</li>
    <li>잘 인터페이스화 해서 trino + mysql + 외부 API로 얻는 보고서데이터 하나의 요청으로 처리 가능 어필 (ga4 API 서버를 하나의 데이터 마트로 취급)</li>
    </ul>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>FastAPI, Trino, Redis, Kubernetes, Python</p>

  <hr/>

  <h3>유지보수 및 모니터링</h3>
  
  <p><strong>Description.</strong><br/>
  개발 경험 향상을 위해 배포 파이프라인 및 모니터링 시스템을 구축
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>GitAction, ArgoCD 기반의 CI-CD 파이프라인 구축</li>
    <li>PagerDuty 및 Sentry 기반의 에러 모니터링 시스템 구축, API 서버와 1만개 이상의 Airflow task의 Failure를 모니터링</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>GitAction, ArgoCD, Helm, Kubernetes, PagerDuty, Sentry</p>
</div>

</div>

<hr/>

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<div style="flex: 1;">
  <h2>Network Computing Lab <br> <span style="font-size: 15px; color: gray;"> 숭실대학교 </span></h2>
  <p><strong>학부 연구생</strong><br>2020.07 - 2021.06</p>
</div>

<div style="flex: 3;">
  <h3>IOT 센서 데이터 파이프라인 구축</h3>
  
  <p><strong>Description.</strong><br/>
  IOT 센서 클러스터들이 제공하는 다양한 데이터를 처리하는 ETL 파이프라인 구축
  </p>

  <p><strong>What did I do.</strong></p>
  <ul>
    <li>센서 데이터를 스트리밍 하기 위한 Kafka 세팅</li>
    <li>데이터를 전처리하고 ElasticSearch, MySQL에 적재하는 서버 구현</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>Kafka, ElasticSearch, Go, MySQL, Docker</p>
</div>

</div>

<br/><br/>

<h1> 🎒 Personal Experience </h1>

<h3> 숭실대학교 </h3>

<p><strong>AI 융합학부생 (2017.03 ~ 2022.06)</strong></p>
<p>- 평균 학점: 4.1/4.5</p>
<p><strong>Network Computing Lab 학부 연구생 (2020.07 ~ 2021.06)</strong></p>
<hr/>

<h3> 해군 1함대 사령부 정보통신 중대 </h3>
<p><strong>전산 · 네트워크병 (2017.08 ~ 2019.06)</strong></p>

<br/><br/>

# 📂 Leading Projects


<div style="display: flex; align-items: flex-start; gap: 2rem;">

<div style="flex: 1;">
  <h2>Laplace Technologies, Inc.</h2>
</div>

<div style="flex: 3;">
<h3> 치명적인 장애 해결 (어댑트의 데이터 안 돌아가는 이슈 해소 -> 롤업)</h3>
<p><strong>Problems.</strong></p>
<ul>
  <li>order + ad + item</li>
  <ul><li>@@@</li></ul>
  <li>@@@</li>
</ul>

<p><strong>Solutions.</strong></p>
<ul>
  <li>@@@</li>
  
</ul>
<p><strong>Results.</strong></p>
<ul>
  <li>@@@</li>
</ul>

<hr/>



<div style="flex: 3;">
<h3> spark 최적화 일대기 + Trino 전환 </h3>
<p><strong>Problems.</strong></p>
<ul>
  <li>spark 너무 비쌈, oome도 터짐 </li>
</ul>

<p><strong>Solutions.</strong></p>
<ul>
  <li>쿼리 최적화</li>
  <li>time_id 별로 partitioning</li>
  <li>dynamicAllocation</li>
  
  <li>Trino 전환</li>
  <ul>
    <li>emr 등 인프라 비용, 전환 사유</li>
    <li>spark를 쓰기엔 작은 데이터 보통 테이블 크기가 N00GB </li>
    <li>deltalake + trino 로는 table을 유지하면서 재집계가 불가능 spark의 overwrite가 불가능 -> iceberg로 바꿔서 create or replace로 해결</li>
    <li>다중 카탈로그 연산 가능 snowflake + s3 + bigquery + mysql ...</li>
  </ul>
  
</ul>
<p><strong>Results.</strong></p>
<ul>
  <li>spark 사용할 때 보다 인프라비용 대량 감소</li>
  <li>spark 사용할 때 보다 인프라비용 대량 감소</li>
</ul>

<hr/>

<h3> 대시보드 API 로딩 속도 개선 </h3>
<p><strong>Problems.</strong></p>
<ul>
  <li>대시보드 API 호출 시 데이터의 양이 많아 30초 이상의 시간이 소요되어 Timeout 발생</li>
  <ul><li>사용자의 활용 경험에 매우 큰 악영향을 주는 문제로 지적됨</li></ul>
  <li>단순히 분산 쿼리 엔진인 Trino의 스펙을 높여서 성능을 개선할 수 있었지만, 이는 클라우드 컴퓨팅 자원의 비용 상승으로 이어짐</li>
</ul>

<p><strong>Solutions.</strong></p>
<ul>
  <li>쿼리 최적화</li>
  <ul>
  <li>dimension 기준 만으로 연산 가능한 데이터들 롤업 </li>
  <li>dimension이 아닌 카디널리티가 높은 키를 기준으로 하는 연산은 롤업을 할 수 없음 -> HLL를 사용하거나, 요청받은 필터링 작업, 필요한 분석단위 + 메져에 필요한 분석단위로 집계한 후에 분석단위 기준으로 조인  </li>
  </ul>
  <li>계층 별 캐싱 전략 도입</li>
  <ul>
  <li>API 서버 캐싱</li>
  <ul>
  <li>Redis를 활용하여 요청 단위로 집계 결과를 캐시하도록 설정</li>
  <li>중복된 요청이 발생했을 때에도 캐싱된 결과를 반환하도록 설정하여, 쿼리 엔진으로 전달되는 쿼리량과, 분석 시간을 대폭 절감</li>
  </ul>
  <li>분산 쿼리 엔진 캐싱</li>
  <ul>
  <li>고객들이 생성한 대시보드 종류의 통계를 보았을 때 동일한 데이터 소스에 다양한 집계를 설정한 다수의 차트를 하나의 대시보드에 위치 시키는 경향을 확인</li>
  <li>Trino가 S3 스토리지에서 읽어온 데이터 마트를 로컬 스토리지에 캐시하도록 설정</li>
  <li>이로 인해 S3에서 Trino로의 데이터 전송 비용 및 처리 시간을 대폭 절감</li>
  </ul>
  </ul>
  <li>적절한 Cache Eviction</li>
  <ul>
  <li>사용자의 데이터가 업데이트 될 경우 캐시된 데이터로 인해 데이터의 일관성에 문제가 생길 수 있음</li>
  <li>사용자 데이터 업데이트 이벤트를 리스닝하는 핸들러에 해당 사용자의 업데이트된 데이터 관련 캐시를 모두 Eviction하도록 하여 데이터의 일관성 확보</li>
  <a>@@@@@@@@ 트리노랑 레디스의 캐시 에빅션은 어케 하는지 공부해야함 @@@@@@@</a>
  </ul>
</ul>
<p><strong>Results.</strong></p>
<ul>
  <li>Trino로 전달되는 쿼리 요청 수가 <strong>50%</strong> 이상 크게 감소</li>
  <li>Grafana 확인 결과 대시보드 API의 평균 응답 속도를 5초 이내로 단축</li>
  <li>사용자의 대시보드 활용 경험을 크게 개선</li>
  <li>인프라 비용의 증가 없이 성능 최적화를 달성할 수 있었음</li>
</ul>

<hr/>

<h3> AWS Elastic Kubernetes Service 최적화 </h3>
<p><strong>Problems.</strong></p>
<ul>
  <li>Kubernetes 클러스터에서 EKS와 EC2를 함께 사용하면서 Pod 수 증가에 따라 자동으로 EC2 노드가 스케일링 되고 있었음</li>
  <li>Airflow on Kubernetes를 사용 중이었으며, 이 때 과도한 Task들로 인해 다수의 Pod가 생성됨</li>
  <li>EC2 노드의 스케일업이 빈번히 발생하여 불필요한 비용이 발생</li>
</ul>

<p><strong>Solutions.</strong></p>
<ul>
  <li>Prometheus로 집계된 리소스 사용률을 Grafana를 이용해 확인한 결과 할당된 리소스 크기에 비해 CPU 사용량이 매우 낮은 다수의 tiny task들이 각각 pod로 생성되는 것이 잦은 스케일 업의 원인임을 확인</li>
  <li>여러 tiny task들을 하나의 task로 chaining 시키거나, 불필요한 dynamic task mappning을 정리하는 등 Airflow의 task를 최적화하여 pod가 과도하게 생성되는 것을 방지</li>
  <li>Task가 실행될 때 최소한의 리소스만 할당하도록 조정</li>
  <li>Karpenter를 Kubernetes의 스케줄러로 도입</li>
  <ul>
    <li>Pod의 리소스 요구 사항과 노드의 리소스 사용률을 기반으로 노드를 동적으로 할당하여, 리소스 낭비를 줄이고 불필요한 노드 스케일링을 방지할 수 있었음</li>
    <li>노드 리소스 사용률이 낮을 때 유휴 노드를 자동으로 축소하고, 반대로 리소스가 과부하될 때는 필요한 만큼만 노드를 확장하여 클러스터를 최적화</li>
  </ul>
</ul>


<p><strong>Results.</strong></p>
<ul>
  <li>Pod 배치가 보다 효율적으로 이루어져 리소스 사용률과 클러스터 효율성 개선</li>
  <li>billing report 확인 결과 EC2 비용을 약 <strong>20%</strong> 절감할 수 있었음</li>
  <li>서비스 운영에 타격을 주지 않고 인프라 운영 비용을 절감하는데 성공</li>
</ul>

<hr/>


</div>

</div>
