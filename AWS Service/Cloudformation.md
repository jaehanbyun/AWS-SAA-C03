## Cloudformation
  * 반복적인 AWS 인프라 구성을 수동으로 프로비저닝하면 시간, 노력이 많이 소요됨
  * EC2 생성, 보안그룹, ALB 등의 인프라 세트를 수백 개로 여러 리전에 배포할 때?
  * 코드로 인프라를 작성하여 자동화할 수 있는 것이 Cloudformation
  * 코드를 통해 자동화하여 AWS 인프라 생성, 업데이트, 삭제 가능
  * 구성 요소
    * Template: 인프라를 구성하기 위한 리소스들을 JSON, YAML 형식의 파일로 정의한 템플릿
    * Stack: Template에 정의되어 생성된 리소스
    * Change Set: Stack 리소스 변경 사항에 대한 셋
  
