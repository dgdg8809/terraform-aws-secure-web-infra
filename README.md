# Terraform 기반 AWS Secure Web Infrastructure

Terraform을 활용하여 AWS 환경에 고가용성과 보안을 고려한 웹 인프라를 구축한 프로젝트입니다.
수동으로 관리되던 인프라를 IaC(Infrastructure as Code) 방식으로 자동화하고,
Auto Scaling과 AWS WAF를 통해 장애 복구 및 보안 대응이 가능한 환경을 구성하였습니다.

## Architecture
<img width="736" height="591" alt="image" src="https://github.com/user-attachments/assets/43932714-aa68-4baf-ae04-84cb62025516" />

## 주요 기술

- Terraform
- AWS VPC
- EC2
- Auto Scaling
- ALB
- RDS
- Route53
- CloudWatch
- AWS WAF

## 주요 구현 내용

- IaC 기반 인프라 자동화
- Multi-AZ 구성
- Auto Scaling 기반 장애 복구
- AWS WAF 기반 SQL Injection/XSS 차단

## My Role

- 프로젝트 PM 및 AWS인프라 설계 총괄
- Terraform 기반 AWS 인프라 설계 및 구축 주도
- ALB 및 Auto Scaling Group 구성
- AWS WAF 적용 및 보안 검증 수행
- CloudWatch 모니터링 환경 구축
- 장애 복구 및 공격 차단 테스트 수행

# Validation

## Auto Scaling 검증

- EC2 장애 발생 시 Auto Scaling 기반 자동 복구 검증

## AWS WAF 검증

- DVWA, WORDPRESS, GNUBOARD 환경 구성
- SQL Injection 차단 확인
- XSS 공격 차단 확인

## Monitoring

- CloudWatch 기반 리소스 모니터링
- 상태 확인 및 장애 대응 테스트 수행
