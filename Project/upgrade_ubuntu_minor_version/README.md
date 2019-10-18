# Upgrade Ubuntu Minor Version
Ubuntu14.04.2 -> Ubuntu14.04.6

# README #

Ubuntu 14.04.02 버전을 14.04.6 버전으로 Upgrade 하는 Doc 문서와 Ansible 활용을 위한 YAML 파일 관리

### 이곳에서 관리하는 문서모음 ###

* [ Ubuntu Repository 구축 및 Ansible 을 이용한 패키지 업데이트.doc ] : 배포서버 구축 및 테스트 환경 구축 문서
* [ inven ] : Ansible-playbook에 의해 해석되며, 대상서버 및 변수 정의 파일
* [ main.yml ] : Ansible-playbook에 의해 해석되며, 업데이트 관련 YAML 파일 구동 (Orchestrator)
* [ key_exchange.yml ] : Ansible-playbook에 의해 해석되며, repo 서버와 업데이트 대상 서버와 키 교환  
* [ ubuntu_update.yml ] : Ansible-playbook에 의해 해석되며, 실제 ubuntu 업데이트 
* [ get_upinfo_ubuntu.yml ] : Ansible-playbook에 의해 해석되며, 대상 서버 업데이트 정보 회신 
