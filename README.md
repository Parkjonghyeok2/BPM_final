# BPM (Block Project Manager)
**Block Project Manager**
### 팀원 및 역할
|       이름         |     역할     |   
| ------------------- | -------------- | 
| 박종혁 |     Full-Stack     |
| 신현성 |     Back-End, DB       | 
| 유영훈 |     Back-End, DB       | 
<br>

## 개요
프로젝트의 현황을 한눈에 확인하고 <br>
업무를 분류별로 나누어 협업과 관리를 도와주는 프로젝트 템플릿 웹서비스 <br>
<br>
대표적인 프로젝트 협업툴인 노션과 지라의 특징적인 기능들을 합쳐 <br>
간단하게 프로젝트 관리를 도와줄 수 있는 템플릿 이다.<br>

### 개발일정
2023.02 ~ 2023.06 
<br>
### 사용 기술 스택
> * `Java 17.0.5`
> * `Spring Boot 2.7.11`
> * `Spring-cloud 1.2.8`
> * `Spring Data JPA`
> * `Thyleaf`
> * `Lombok`
> * `Maria DB 10.11.2`
> * `AWS RDS`
<br>
<br>


## 시나리오 소개

(피라미드 캡처본 필요)
프로젝트를 관리하는 협업툴로 정해진 템플릿을 따른다. <br>
4단계 트리노드로 나누어 져있으며 <br>
**프로젝트**, <br>
**목표**, <br>
**작업**, <br>
**문서**  <br>
라는 이름으로 나누어 져 있다.
<br>
각각의 노드들을 추가 설명하자면, <br>
| 구분 | 설명 | 
| ---- | -- |
| 프로젝트 | 각각의 프로젝트를 의미하며, 사용자들을 초대 할 때 주체가 되는 노드이다.|
| 목표 |  프로젝트를 달성하기 위해 완수되어야 할 큰 단위의 작업을 의미한다. <br> - 작업을 하위노드로 선택 할 수 있다. |
| 작업 | 목표를 달성하기 위해 완수되어야 할 작은 단위의 작업을 의미한다. <br> - 상위 노드로는 목표, 하위 노드로는 문서를 종속 및 선택할 수 있다. |
| 문서 | 작업에 대한 부가적인 설명을 할 수 있는 문서 편집기로 노션과 비슷한 블럭 단위 텍스트 편집기 기능을 가지고 있다.|
<br>
목표와 작업은 서로 종속 되어 확인 할 수 있으며 작업들이 완료 처리가 되면 상위 목표는 자동으로 완료 처리가 된다. <br>

기타 기능 소개는 하단에서 더 설명하겠다. <br>
<br>

## 기능 소개

### 로그인, 회원가입 
기본적인 기능으로 추가 설명 X
<br> 
<br> 
#### 분류별 프로젝트 
회원이 프로젝트의 관리자(생성자) 인지 아닌지 여부에 따라 <br> 
'전체 프로젝트' 와 '내 프로젝트'로 구분 지어 보여준다.
<br> 
<br> 
### 프로젝트 관리 메인
프로젝트 리스트에서 하나를 접속하면 보여지는 프로젝트 관리 main 창으로  <br> 
프로젝트에 관한 정보를 한눈에 확인 할 수 있는 기능이다.
<br> <br> 
### 멤버 초대 및 초대 확인 리스트 
어떤 프로젝트에 초대를 받았는지 여부를 확인할 수 있는 리스트와 <br> 
원하는 멤버를 검색해 초대할 수 있는 기능이다.
<br> <br> 
### 목표 및 작업 
목표와 작업들을 설정해 담당자와 마감기한을 정하는 등 <br> 
협업을 위해 분업을 할 수 있는 기능이다.
<br> <br> 

### 문서
노션을 모티브로 한 문서 편집기로, 태그별로 블럭을 생성해서 텍스트를 기입하거나 위치를 바꿀 수 있고 
<br> 추가로 코드, 이미지, 동영상을 첨부하여 해당 작업에서 추가적으로 설명하거나 코드 구현을 상세하게 표현하기 위해 도와주는 기능이다.
<br> <br> 

### 기타

**메세지** <br> 
프로젝트에 속해 있는 멤버 끼리 간단히 메세지를 주고 받을 수 있는 기능이다.<br> <br> 
**캘린더, 간트차트** <br> 
목표 와 작업을 날짜와 종속 별로 확인할 수 있는 기능으로 google, fullcalender API를 기반으로 구현되어 있다. <br> 
<br> 
<br> 
<br> 

## PPT
![git에 올릴 ppt_1](https://github.com/ppark-jjong/BPM_Final/assets/101304928/b0538ee6-09b1-4052-b4d9-7ab1940bff67)
![git에 올릴 ppt_2](https://github.com/ppark-jjong/BPM_Final/assets/101304928/bb90587a-19da-4ea7-a2c4-76bced2c74ee)
![git에 올릴 ppt_3](https://github.com/ppark-jjong/BPM_Final/assets/101304928/9404815b-5e88-420f-a0f8-a1661f6f6898)
![git에 올릴 ppt_4](https://github.com/ppark-jjong/BPM_Final/assets/101304928/4cb32035-d5a9-4224-aebd-ef2c37da6cf2)
![git에 올릴 ppt_5](https://github.com/ppark-jjong/BPM_Final/assets/101304928/08a82ec1-0cfc-445e-9018-2f64517b3020)
![git에 올릴 ppt_6](https://github.com/ppark-jjong/BPM_Final/assets/101304928/0a5c6f5a-d016-4908-996c-b6a6fbfd97c9)
![git에 올릴 ppt_7](https://github.com/ppark-jjong/BPM_Final/assets/101304928/6117ab2a-b8ad-445c-9ddb-46f1ec629902)
![git에 올릴 ppt_8](https://github.com/ppark-jjong/BPM_Final/assets/101304928/8283cbe1-af79-4efe-9a7f-9e72dc3ee995)
![git에 올릴 ppt_9](https://github.com/ppark-jjong/BPM_Final/assets/101304928/e4297244-e6ae-41a9-966f-6f2074835202)
![git에 올릴 ppt_10](https://github.com/ppark-jjong/BPM_Final/assets/101304928/3a98e069-e1a8-443d-bcf6-71cf412ff710)
![git에 올릴 ppt_11](https://github.com/ppark-jjong/BPM_Final/assets/101304928/a9bfa10d-cfde-46ac-81eb-8618619dcde0)
![git에 올릴 ppt_12](https://github.com/ppark-jjong/BPM_Final/assets/101304928/4bc2a200-af34-4599-9243-f9c50b901c44)
![git에 올릴 ppt_13](https://github.com/ppark-jjong/BPM_Final/assets/101304928/7977bcd5-dd16-4df8-856b-725a13de0d68)
![git에 올릴 ppt_14](https://github.com/ppark-jjong/BPM_Final/assets/101304928/0ea9bcfd-abdd-4813-87e2-494b7cf43f1c)
![git에 올릴 ppt_15](https://github.com/ppark-jjong/BPM_Final/assets/101304928/86dae5a4-7bfb-49a4-9329-ecfdda88bb4d)
![git에 올릴 ppt_16](https://github.com/ppark-jjong/BPM_Final/assets/101304928/1a1c8196-0b07-40c3-b808-9d80229b6831)
![git에 올릴 ppt_17](https://github.com/ppark-jjong/BPM_Final/assets/101304928/2ffe4388-fd69-4910-bf25-9a07729943e9)
![git에 올릴 ppt_18](https://github.com/ppark-jjong/BPM_Final/assets/101304928/30b271d3-9cda-4aab-9d99-260c1a6a2e8e)
![git에 올릴 ppt_19](https://github.com/ppark-jjong/BPM_Final/assets/101304928/70442de7-1f7f-49f3-979b-e5a45d38058c)
![git에 올릴 ppt_20](https://github.com/ppark-jjong/BPM_Final/assets/101304928/978733a8-d622-4c50-ad5f-863e9322137e)
![git에 올릴 ppt_21](https://github.com/ppark-jjong/BPM_Final/assets/101304928/156b0cc6-b8aa-475e-97b9-5514483ab840)
![git에 올릴 ppt_22](https://github.com/ppark-jjong/BPM_Final/assets/101304928/3873a7f8-e9e8-4fbe-ba78-277f9c278867)
![git에 올릴 ppt_23](https://github.com/ppark-jjong/BPM_Final/assets/101304928/5b26b2d0-c238-47a4-9fad-e5efa9109a27)
![git에 올릴 ppt_24](https://github.com/ppark-jjong/BPM_Final/assets/101304928/66fd86fe-045c-4da1-bd6a-7b27adaf731d)
![git에 올릴 ppt_25](https://github.com/ppark-jjong/BPM_Final/assets/101304928/ddd18bfd-5059-4e54-9ed1-31d1f8a7e741)
![git에 올릴 ppt_26](https://github.com/ppark-jjong/BPM_Final/assets/101304928/715b7773-ecc4-421f-85cd-e5b988eec481)
![git에 올릴 ppt_27](https://github.com/ppark-jjong/BPM_Final/assets/101304928/af2aca23-fb3b-4a93-a1e8-f535b3a16117)

