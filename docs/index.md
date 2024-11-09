# 김성호
안녕하세요. 백엔드 엔지니어 김성호 입니다.

<br/><br/>

# 💻 Work Experience.

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
    <li>인증 정보를 암호화된 storage에 저장</li>
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
    <li>데이터를 전처리하고 Elastic search, MySQL에 적재하는 서버 구현</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>Kafka, ElasticSearch, Go, MySQL, Docker</p>
</div>

</div>


<br/><br/>

# 🎒 Personal Experience

### 숭실대학교

**AI 융합학부생 (2017.03 ~ 2022.06)**
- 평균 학점: 4.1/4.5

**NCLab 학부 연구생 (2020.07 ~ 2021.06)**

### 해군 1함대 사령부 정보통신 중대

**전산 · 네트워크병 (2017.08 ~ 2019.06)**