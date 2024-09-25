- ADF IaC 동작 확인
	- [x] ADF 생성
	- [x] Azure Blob 4개 생성
	- [x] Azure Blob linked Service
	- [x] NAT G/W 생성
	- [x] ADF NSG 적용
	- [x] AWS S3 linked Service
		- [x] key vault access policy 관리
		- [x] self IR - 테스트 커넥션 확인
		- [x] VM 접속 using Terraform (접속 에러) 하여 access key 적용
		- [x] key reset 확인
		- [x] 6시간 마다 리셋 동작 확인
	- [x] AWS data Set
	- [x] Azure linked Service
	- [x] Azure data Set
	- [x] pipeline 구축
	- [x] trigger
- Issue 
	- [ ] ADF - sdp admin publish sync fail 
		- 잘못된 경로 // 문제
	- [ ] Partner DB 접속 간헐적으로 끊김 
		- idle timeout but not sure
	- [ ] private zone - 다른 문제
	- [ ] appg/w - private zone / dns zone 관계 파악 어려움
	- [ ] ip 고정 시 - preview 사용 (azapi)
	- [ ] SSL 적용 시 (self / CA 다름)
	- [ ] Front Door Service Tag 등록해야 동작되는 부분. protection / detection mode 설정
	- [ ] RBAC / Access Policy / AD 개념 등이 AWS와 상이함.
	- [ ] ADF - public ip 대역대 허용
	- [ ] 3.5 ver VS 3.6 System Assigned 추가된 부분
- More 
	- vpc - interface endpoint
	- private link 적용
	- ADF 자동화 방법 생각해보기.
	- 구조 정리.

12월 k8s 