### Architecture

![3조_DAPANDA_CloudArchitecture](https://github.com/user-attachments/assets/7e80841c-aa72-4027-8db6-87cee1053a65)



**Ⅰ. 프로젝트개요**

1. 프로젝트명

- 중고 물품 경매 웹사이트 구축 및 배포

2. 프로젝트기간

- 2024년 05월 29일 ~ 2024년 07월 31일

3. 프로젝트배경 및 필요성

3.1 프로젝트배경

- 중고 거래 시 흥정이나 시간 약속 등의 부정적인 경험 해소 필요
- 경매에 대한 접근성 향상 및 이미지 제고

3.2 프로젝트목적

- 중고 물품 거래의 편리성을 높이기 위해 경매 시스템을 도입하며, 경매에 대한 이미지를 친숙하게 변화
- MSA (Micro Services Architecture) 기반의 시스템 설계 및 확장성과 고가용성을 보장하기 위한 구조 구축
- AWS의 다양한 서비스를 활용하여 시스템을 구축하며, 동시에 FinOps 관점에서 클라우드 비용 최적화
- DevSecOps 접근을 통해 CI/CD 파이프라인을 구축하여 개발 프로세스를 자동화하고, 최소 권한 원칙(POLP)을 준수하여 보안 강화

4. 프로젝트범위

4.1 프로젝트의 대상

- On-Premise(VM) 기반의 인프라 구축
- AWS 클라우드 기반의 인프라 환경으로 마이그레이션
    
    - 홈페이지 트래픽 증가에 능동적으로 대응하기 위한 시스템 기획 및 설계
    
    - 오픈소스 기반의 클라우드 환경 구현을 통하여 트래픽양에 따른 자동화된 ‘Scale Out’ 기능 구현
    
    - 요구사항 분석 및 업무 서비스와 시스템 간 연계 방안을 고려하여 구현
    
    - 다양한 보안 요소를 고려하여 안정적인 서비스 제공 환경 구현방안 수립
    
    - 웹 개발등에 필요한 서버를 능동적이고 빠르게 배포할 수 있는 방안을 고려하여 구현
    
- 지속적 관찰을 위한 모니터링 서버 구축
    
    - log 및 metric 정보를 확인하고 분석할 수 있는 시스템 설계
    
- 유연성있는 홈페이지 운영이 가능한 오토 스케일링 구현
    
    - 오토스케일링 기능을 구현하여 트래픽, 서버의 CPU 또는 RAM 사용량에 따른 유연한 대응이 가능하도록 시스템 설계
    - 백업 및 복구 전략 구축
    
![image](https://github.com/user-attachments/assets/5901e260-36ad-49ce-bb33-5039b3fe74fb)

![image (1)](https://github.com/user-attachments/assets/d35a5a6a-2225-4a8c-a20d-cd01daeb288a)

![image (2)](https://github.com/user-attachments/assets/7be2fe03-75fe-4480-bb08-23596aed1e35)

![image (3)](https://github.com/user-attachments/assets/f222a62b-5456-4a02-9bde-42002967ff81)

![image (4)](https://github.com/user-attachments/assets/06e25dc5-719c-4ca7-b5f4-a417ce690d23)

![image (5)](https://github.com/user-attachments/assets/b847ca6b-b14e-4dff-bd1e-efaf5a942639)

![image (6)](https://github.com/user-attachments/assets/66607292-1761-4480-9e72-c572f2347f33)
