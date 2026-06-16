# Terraform 기반 AWS Secure Web Infrastructure

Terraform을 활용하여 AWS 환경에 고가용성과 보안을 고려한 웹 인프라를 구축한 프로젝트입니다.

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

# Validation

## Auto Scaling 검증

- EC2 강제 종료
- Auto Scaling 자동 복구 확인

## AWS WAF 검증

- DVWA 환경 구성
- SQL Injection 차단 확인
- XSS 공격 차단 확인
