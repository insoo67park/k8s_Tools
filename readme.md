Tools for kubernetes  
1. backup/recovery
   - k10  
     상용, 한달 50 node, 평생 10 node 무료  
     https://www.kasten.io/  
     data management  
   - kanister  
     data management workflow, framework for data management in k8s  
     오픈소스, https://github.com/kanisterio/kanister
   - veloro  
     보통 오브젝트 스토리지인 minio와 함께 적용  
2. 스토리지  
   - 오브젝트 스토리지   
     minio, ceph   
     minio: 설치 쉬움. 별도의 개발자 매뉴얼 없이도 직관적 사용이 가능했음.  가용성 등 나머지 부분은 어떨지...
     ceph: 한번 설치 및 테스트 해 봐야지...  
   - 블럭 스토리지   
     
