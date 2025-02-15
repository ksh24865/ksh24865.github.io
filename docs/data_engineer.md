<h2>[원본 링크] https://ksh24865.github.io/data_engineer </h2>

<h1>김성호</h1>

<p>요구사항, 유지보수성, 성능의 균형을 추구하면서 성장 중인 데이터 엔지니어 입니다. 스타트업의 핵심 인력으로 <strong>2400%의 매출 성장</strong> 달성 경험이 있습니다. <br/>
클라우드 기반 시스템에서 개발해 왔으며, 빅테이터 처리 파이프라인과 웨어하우스를 구축하고, 대시보드 API 서버 개발 경험을 갖고 있습니다.
</p>

<br/>

<h1>💻 Work Experience</h1>   

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<div style="flex: 1;">
  <h2>Laplace Technologies, Inc.</h2>
  <p><strong>Software Engineer, Data</strong><br/>2021.06 - </p>
</div>

<div style="flex: 3;">
  <h3>데이터 파이프라인 구축</h3>
  
  <p><strong>Description.</strong><br/>
  <br/>
  쇼핑몰, 광고 플랫폼, 웹로그 등의 커머스 관련 데이터를 수집 및 처리하는 ELT 파이프라인을 구축

  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>Airflow를 이용한 ELT 파이프라인 Dag 구축</li>
    <ul>
        <li>dynamic dag generation을 통한 파이프라인 생성 자동화</li>
        <li>deferrable sensor를 도입하여 센싱 시 스케줄러 자원이 낭비되는 이슈 해소</li>
        <li>Redis 기반의 체크 포인팅을 통해 task의 failure & retry 에 대한 안정성 확보</li>
    </ul>
    <li>데이터 수집 Task에 버퍼링 및 압축 기능 추가</li>
    <ul>
        <li>Raw 데이터의 총 <strong>용량 92.5% 감소</strong></li>
        <li>반정형 데이터 <strong>Parsing 효율 91% 증가</strong> </li>
    </ul>
    <li>Spark, Trino 기반의 분산 데이터 처리 파이프라인 최적화</li>
    <ul>
        <li>Spark에 Dynamic Resource Allocation를 도입하여 OOME, Idle Executor 이슈 최적화 및 <strong>클러스터 운영 비용 20% 감소</strong> </li>
        <li>Trino 기반 데이터 처리 파이프라인을 도입하여 기존 Spark 대비 <strong>처리 비용 70% 절약, 평균 파이프라인 실행 시간 75% 단축</strong></li>
        <li>Trino에 File System Cache를 도입하여 <strong>트래픽 비용 및 평균 처리 시간 40% 감소</strong> </li>
    </ul>

  </ul>
  
  <p><strong>Tech Stack.</strong><br/>Airflow, AirByte, pySpark, Trino(=Presto), Iceberg, Deltalake, AwsS3, Kubernetes, Python</p>
  
  <hr/>

  <h3>데이터 웨어하우스 구축</h3>
  <p><strong>Description.</strong><br/>
  <br/>
  정합성에 민감한 금액 관련 데이터의 품질을 유지하면서 효율적으로 처리 및 관리되는 데이터 웨어하우스/마트 구축
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>데이터 모델링, 계층화</li>
    <li>Great Expectations 기반의 테이블 정합성 검증 자동화</li>
    <li>롤업 최적화를 통해 row 개수를 1,111,265,510,342,250 -> 127,199,157로 <strong>최대 99% 감소</strong></li>
    <li>파티셔닝 및 버케팅 기반의 DW 최적화를 통해 <strong>쿼리 속도 최대 60% 향상</strong></li>
    <li>Trino UDF 개발</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>Trino, Hive, Iceberg, Deltalake, AwsS3, GreatExpectations, Kubernetes, Python, Java</p>

  
  <hr/>

  <h3>대시보드 API 서버 구축</h3>
  
  <p><strong>Description.</strong><br/>
  500개 이상의 전자상거래 비즈니스 성과를 분석 및 시각화 하는 대시보드 API 서버를 설계 및 구축
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>커스텀한 대시보드 설정 정보를 요청 받아 데이터를 집계하여 제공하는 서비스 구현</li>
    <ul>
        <li>SQL Alchemy 기반 Trino 쿼리 빌더 구현</li>
    </ul>
    <li>API 서버 및 분산 데이터 처리 시스템의 단위별 캐싱을 통해 대시보드 <strong>조회 성능을 80% 개선</strong></li>    
    <li>분석 기능 개발</li>
    <ul>
        <li>period-over-period 분석</li>
        <li>리텐션, 코호트 분석</li>
        <li>4분면 분석</li>
        <li>ABC 분석</li>
        <li>지역 분석</li>
    </ul>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>FastAPI, Trino, Redis, Kubernetes, Python</p>

  <hr/>

  <h3>유지보수 및 모니터링</h3>
  
  <p><strong>Description.</strong><br/>
  개발 경험 향상을 위해 배포 파이프라인 구축 및 모니터링 시스템을 통한 온콜 수행
  </p>
  
  <p><strong>What did I do.</strong></p>
  <ul>
    <li>GitHub Actions, ArgoCD 기반의 CI-CD 파이프라인 구축</li>
    <li>PagerDuty를 통해 API 서버와 1만개 이상의 Airflow task의 Failure를 모니터링</li>
    <ul>
    <li>PagerDuty incident deduplication key와 airflow task retry 최적화를 통해 self-healing system 을 구축하여, 배치 작업의 <strong>오류 알림율을 97% 감소</strong></li>
    </ul>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>GitAction, ArgoCD, Helm, Kubernetes, PagerDuty</p>

</div>

</div>

<hr/>

<br/>

<h1> 🎒 Personal Experience </h1>

<div style="display: flex; align-items: flex-start; gap: 2rem;">

<div style="flex: 1;">
  <h2>토스 Learner's High<br>서버 1기 <br> <span style="font-size: 15px; color: gray;"> toss </span></h2>
  <p><strong>멘티</strong><br>2024.12 - 2025.01</p>
</div>

<div style="flex: 3;">
  <h3>DW 및 대시보드 서버 개선</h3>
  
  <p><strong>Description.</strong><br/>
  토스에서 지향하는 서버 개발자의 성장 방향성을 바탕으로 본인의 업무 목표를 설정하고 실제 업무에 적용
  </p>

  <p><strong>What did I do.</strong></p>
  <ul>
    <li>DW 정합성 장애 감지 자동화</li>
    <ul>
      <li>Great Expectations와 Airflow를 활용하여 DW 테이블의 다양한 정합성 검증 로직 자동화</li>
      <li>PagerDuty와 연동하여 정합성 문제 발생 시 자동으로 Incident를 생성하여 데이터 품질 관리의 용이성 및 신뢰성 증대</li>
    </ul>
    <li>대시보드 서버 성능 최적화</li>
    <ul>
      <li>Modin 기반의 Parallelism 최적화를 적용하여 <strong>처리 시간 60% 감소</strong></li>
    </ul>
  </ul>
  
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
    <li>센서 데이터 스트리밍 Kafka 세팅</li>
    <li>데이터를 전처리하고 ElasticSearch, MySQL에 적재하는 서버 구현</li>
    <li>센서 클러스터 헬스 체크 서버 구현</li>
  </ul>
  
  <p><strong>Tech Stack.</strong><br/>Kafka, ElasticSearch, Go, MySQL, Docker</p>
</div>
</div>
<hr/>
<h3> 숭실대학교 </h3>

<p><strong>AI 융합학부생 (2017.03 ~ 2022.06)</strong></p>
<p>- 평균 학점: 4.1/4.5</p>
<hr/>

<h3> 해군 1함대 사령부 정보통신 중대 </h3>
<p><strong>전산 · 네트워크병 (2017.08 ~ 2019.06)</strong></p>
<hr/>