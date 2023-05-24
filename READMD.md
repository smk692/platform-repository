# AWS EKS 생성 Iac 코드 

### 1. 인프라 저장소 생성
```
cd aws/terraform-backend

# 테라폼 설정
terraform init 

# 플랜 
terraform plan

# 생성
terraform apply
```

### 2. 인프라 생성 
```
Vpc, 라우팅테이블, S3 인터넷 게이트웨이, 보안그룹, EKS, EKS node group 등등 

cd aws/terraform-code

# 테라폼 설정
terraform init 

# 플랜 
terraform plan

# 생성
terraform apply


```