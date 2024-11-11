<h1>김성호</h1>
<p>안녕하세요. 백엔드 엔지니어 김성호 입니다.</p>

<br/><br/>

<h1>💻 Work Experience</h1>

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<div style="flex: 1;">
  <h2>Laplace Technologies, Inc.</h2>
  <p><strong>Backend Engineer</strong><br/>2021.06 - </p>
</div>

<div style="flex: 3;">
  <h3>대시보드 API 서버 구축</h3>
  
  <p><strong>Description.</strong><br/>
  500개 이상의 커머스 BI 데이터 지표에 대해 분석 및 시각화 하는 대시보드 API 서버를 설계 및 구축 하였습니다.
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>대시보드 설정 정보를 요청 받아 데이터를 집계하여 제공하는 서비스 구현</li>
    <li>API 서버 및 분산 쿼리 시스템의 단위별 캐싱을 통해 대시보드 조회 성능 개선</li>
    <li>대시보드를 커스텀하게 다룰 수 있도록 document 기반의 CRUD 기능 구현</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>FastAPI, Trino, Redis, Kubernetes, Python</p>

  <hr/>

  <h3>알림 시스템 구축</h3>
  
  <p><strong>Description.</strong><br/>
  일 평균 1300개 이상의 커머스 BI 리포트 및 CRM 메시지를 발송하는 알림 시스템을 구축 하였습니다. 
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>메시지 큐를 이용한 이벤트 드리븐 기반의 알림 전송 시스템 구축</li>
    <li>설정 정보를 통해 대시보드 API를 호출하고 리포트를 생성하는 서비스 구현</li>
    <li>카카오 알림톡, 슬랙, 이메일 전송 서비스 구현</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>AwsSQS, Airflow, FastAPI, MySQL, Redis, Kubernetes, Python</p>

  <hr/>

  <h3>커머스 데이터 파이프라인 구축</h3>
  
  <p><strong>Description.</strong><br/>
  <br/>
  400개 이상의 고객사를 대상으로 쇼핑몰, 광고 플랫폼, 웹로그 등의 커머스 관련 데이터를 처리하는 ETL 파이프라인을 구축하여 일 평균 200만 개의 데이터를 처리 하였습니다.
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>Airflow를 이용해 파이프라인 스케줄링 Dag 개발</li>
    <li>Spark 및 Trino 최적화를 통해 처리 성능 향상(대략 20%이상의 데이터 처리 비용 절감)</li>
    <li>데이터 품질 및 쿼리 성능 향상을 위한 데이터 웨어하우스 구축</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>Airflow, Spark, Trino, Iceberg, Deltalake, AwsS3, Kubernetes, Python, Java</p>
  
  <hr/>

  <h3>서드파티 권한 인증 서버 구축</h3>
  
  <p><strong>Description.</strong><br/>
  쇼핑, 광고, 웹로그를 다루는 외부 플랫폼의 데이터를 수집하기 위해 권한 및 인증 정보를 제공 받는 서버를 구축 하였습니다.  
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>Oauth, API key, Crawling 등의 방법으로 유저로 부터 권한을 제공 받는 서비스 구현</li>
    <li>인증 정보를 암호화 후 저장</li>
    <li>인증 정보 만료 시 대응 로직 구현</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>FastAPI, MySQL, AwsSecretManager, Kubernetes, Python</p>

  <hr/>

  <h3>유지보수 및 모니터링</h3>
  
  <p><strong>Description.</strong><br/>
  개발 경험 향상을 위해 배포 파이프라인 및 모니터링 시스템을 구축 하였습니다.
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
  <h2>NC Lab <br> <span style="font-size: 15px; color: gray;"> 숭실대학교 </span></h2>
  <p><strong>학부 연구생</strong><br>2020.07 - 2021.06</p>
</div>

<div style="flex: 3;">
  <h3>IOT 센서 데이터 파이프라인 구축</h3>
  
  <p><strong>Description.</strong><br/>
  IOT 센서 클러스터들이 제공하는 다양한 데이터를 처리하는 ETL 파이프라인을 구축하였습니다.
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
<p><strong>NCLab 학부 연구생 (2020.07 ~ 2021.06)</strong></p>
<hr/>

<h3> 해군 1함대 사령부 정보통신 중대 </h3>
<p><strong>전산 · 네트워크병 (2017.08 ~ 2019.06)</strong></p>

<br/><br/>

# Projects


<div style="display: flex; align-items: flex-start; gap: 2rem;">

<div style="flex: 1;">
  <h2>Laplace Technologies, Inc.</h2>
</div>

<div style="flex: 3;">
<h3> AWS Secret Manager 최적화 </h3>
<p><strong>Problem.</strong><br/>
<ul>
  <li>모든 암호 정보를 AWS 클라우드의 SecretManager에 저장하고 있음</li>
  <li>월 1066$가 암호 저장 비용으로 지출</li>
      <ul><li>SecretManager의 비용은 암호 1개당 월 월 0.4$</li></ul>  
</ul>
</p>

<p><strong>Solution.</strong><br/>
<ul>
  <li>1급 비밀을 제외한 암호 정보를 대칭키 암호화 후 RDB로 이관</li>
  <li>대칭키를 SecretManager에 저장</li>
</ul>
</p>


<p><strong>Results.</strong><br/>
<ul>
  <li>보안성을 확보한 채로 SecretManager의 월 비용을 99% 이상 대폭 감소</li>
</ul>
</p>


<hr/>

<h3> AWS Elastic Kubernetes Service 최적화 </h3>
<p><strong>Problem.</strong><br/>
<ul>
  <li>Kubernetes 클러스터에서 EKS와 EC2를 함께 사용하면서 Pod 수 증가에 따라 자동으로 EC2 노드가 스케일링 되고 있음</li>
  <li>Airflow on Kubernetes를 사용 중이었는데, 이 때 불필요한 Task들이 다수의 Pod로 생성됨</li>
  <li>EC2 노드가 자주 확장되면서 불필요한 비용이 발생</li>
</ul>
</p>

<p><strong>Solution.</strong><br/>
<ul>
  <li>TBD</li>
  <li>TBD</li>
</ul>
</p>


<p><strong>Results.</strong><br/>
<ul>
  <li>EC2 비용을 약 20% 절감할 수 있었으며, Pod 배치가 보다 효율적으로 이루어져 리소스 사용률이 개선</li>
  <li>인프라 운영 비용을 절감하면서도 안정적인 서비스 운영을 유지하는 데 성공</li>
</ul>
</p>

<hr/>

<h3> 대시보드 API 리팩토링 </h3>
<p><strong>Problem.</strong><br/>
<ul>
  <li>대시보드의 데이터 종류 및 분석 방법 마다 각기 다른 API로 구현되어있음</li>
  <li>일관성이 없어 코드의 가독성이 떨어지며, 유지보수 및 추가 개발이 어려움</li>
</ul>
</p>

<p><strong>Solution.</strong><br/>
<ul>
  <li>모든 대시보드 API가 공통화 될 수 있도록 리팩토링</li>
  <li>QueryLayer, DataLayer, DashboardLayer로 계층 및 인터페이스를 나눈 후 추상화 전략을 고도화</li>
  <li>데이터와 그 데이터를 제공하는 서버의 종류에 관계 없이 추상 메서드를 잘 Implement한 서비스를 생성하고, 요청에 따라 각 서비스들을 조립 및 재사용 해가며 실행할 수 있도록 구성</li>
</ul>
</p>


<p><strong>Results.</strong><br/>
<ul>
  <li>각 layer의 관심사를 분리하고 의존도를 낮추어 유지보수 용이성이 향상</li>
  <li>데이터 종류, 측정값, 분석단위, 필터, 분석방법 등의 설정값을 받아서 이에 맞는 집계 결과를 반환하는 커스텀 대시보드의 API로 활용</li>
  <li>추후에 `4분면 분석`, `ABC 분석` 등의 추가 기능이 요구 되었었지만, 하위의 공통 Layer만 수정하면 됐을 정도로 개발 용이성 확보</li>
</ul>
</p>

<hr/>

<h3> 데이터 정합성 보완 </h3>
<p><strong>Problem.</strong><br/>
<ul>
  <li>커머스 플랫폼 별로 매출 지표의 집계방식이 다름</li>
  <li>커머스 플랫폼에서 제공하는 API 데이터에 오류가 존재함</li>
  <li>고객사들이 정확한 매출 지표를 확인할 수 없음</li>
</ul>
</p>

<p><strong>Solution.</strong><br/>
<ul>
  <li>1급 비밀을 제외한 암호 정보를 대칭키 암호화 후 RDB로 이관</li>
  <li>대칭키를 SecretManager에 저장</li>
</ul>
</p>

<p><strong>Results.</strong><br/>
<ul>
  <li>보안성을 확보한 채로 SecretManager의 월 비용을 X$로 대폭 감소</li>
</ul>
</p>

<hr/>

<h3> 대시보드 API 로딩 속도 개선 </h3>
<p><strong>Problem.</strong><br/>
<ul>
  <li>모든 암호 정보를 AWS의 SecretManager에 저장하고 있음</li>
  <li>월 1066$가 암호 저장 비용으로 지출 (SecretManager의 비용은 암호 1개당 월 월 0.4$)</li>
</ul>
</p>

<p><strong>Solution.</strong><br/>
<ul>
  <li>1급 비밀을 제외한 암호 정보를 대칭키 암호화 후 RDB로 이관</li>
  <li>대칭키를 SecretManager에 저장</li>
</ul>
</p>


<p><strong>Results.</strong><br/>
<ul>
  <li>보안성을 확보한 채로 SecretManager의 월 비용을 99% 이상 대폭 감소</li>
</ul>
</p>

</div>

</div>
