# ARMAGYETDON(아마곗돈)  

## 📅 프로젝트 개요

💵 **기간**

2024.07.26 ~ 2024.09.12

💵 **팀원 소개**

<table>
    <tr>
        <td><img src="https://avatars.githubusercontent.com/ymkdev" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/JaeIn1" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/Leehyeonju0219" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/Elandland" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/kyeongseo90" width="180"></td>
        <td><img src="https://avatars.githubusercontent.com/Yoon-97" width="180"></td>
    </tr>
    <tr align=center>
        <td><a href='https://github.com/ymkdev'>고유민</a></td>
        <td><a href='https://github.com/JaeIn1'>이재인</a></td>
        <td><a href='https://github.com/Leehyeonju0219'>이현주</a></td>
        <td><a href='https://github.com/Elandland'>임찬솔</a></td>
        <td><a href='https://github.com/kyeongseo90'>최경서</a></td>
        <td><a href='https://github.com/Yoon-97'>하윤철</a></td>
    </tr>
</table>

💵 **기획 배경**

흔히 지인이나 친구들과 ***함께 사용하기 위해 모은 돈***을 `곗돈`이라고 합니다.  
요즘은 이러한 곗돈을 `모임통장`으로 관리하는 경우가 많아지고 있습니다.  

`모임통장`은 친구나 지인들과 함께 자금을 모으고 관리하는 데 널리 사용되고 있으며, ***꾸준한 인기***를 끌고 있습니다.  
***하지만,*** 모임통장에 예치된 자산은 종종 사용처 없이 `방치`되거나, `낮은 이자율`로 인해 실질적인 ***수익을 내기는 어렵습니다.***  

저희는 최근 ***은행권 금리 하락세***로 인해 ***시중의 유동 자금이 투자 시장으로 이동***하고 있는 추세를 반영하여, 이러한 자산을 `투자 자본금으로 활용할 수 있는 서비스`를 기획했습니다.  
사용자들은 `신뢰할 수 있는 사람들`과 함께 안전하고 투명한 방식으로 `돈을 모아 불리며`, `공동의 목표`를 달성할 수 있습니다.

> 함께 돈을 모아, 함께 투자하고, 함께 수익을 나눠보세요!

💵 **주요 기능**

-  모임 투자
    -  모임 생성
    -  모임 원칙 생성  
    -  초대장 발송
    -  모임 계좌 계설
    -  모임 포트폴리오 조회
    -  모임 원칙 수정 제안 & 투표
    -  자동이체 및 이체 내역 조회
    -  채팅
    -  알람 
    -  주식 매매  

- 주식 매매  
    -  실시간 차트  
    -  호가창  
    -  지정가 매수/매도 제안  
    -  매수/매도  
    -  거래 내역 조회

💵 **부가 기능**   

- 회원 관리  
    -  회원가입
    -  로그인/로그아웃
    -  개인 계좌 개설
    -  내 정보 수정

-  순위
    -  자산별 평가 수익률 순위  

-  대시보드  
    -  코스피/코스닥 지수  
    -  주요 증권 뉴스  
    -  추천 포트폴리오 순위  
    -  인기 주식 순위  
    -  핫이슈 종목 순위
       
 💵 **데이터 활용**  

 -  한국투자증권 openAPI  
 -  신한투자증권 openAPI  
 -  네이버 증권 주요뉴스, 코스피/코스닥 지수 크롤링  

## 💡서비스 소개

### _ARMAGYETDON(아마곗돈)_  

ARMAGYETDON(아마곗돈)은, 모임 투자 서비스입니다.

> (모임 팀장 & 팀원)  

1. 팀장은 `모임을 생성`합니다.
   - 모임명, 모임 인원, 카테고리, 모임 기간을 입력합니다. 
   - `모임의 원칙`을 정합니다. 추후에 투표를 통해 수정이 가능합니다.
     (1인당 초기 투자금, 기간별 납부 금액, 납부 시작일, 납부 주기, 매매 규칙, 긴급 매도 규칙, 해제 규칙)    

2. 팀장은 `초대장 코드를 공유`하고 초대 받은 팀원은 `초대장 코드를 입력`합니다.
    
3. 인원이 모두 모였다면 `모임을 확정`하고, `모임 계좌를 개설`합니다.

4. `대시보드` 페이지를 통해 투자 정보를 얻고, `채팅`을 통해 이야기를 나눕니다.  

5. 지정가 `매수/매도 제안`을 올려 `투표`를 통해 `자동 매수/매도`합니다.   

6. 상세 포트폴리오 페이지로 이동하여, `보유한 주식 종목`의 `평가금액`, `평균단가`, `현재가`, `매수금액`을 확인합니다.  

**ARMAGYETDON을 통해 함께 투자해보세요!**
### ⚙️ 기술 스택

**프론트엔드**  

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-3178C6.svg?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![tailwindcss](https://img.shields.io/badge/tailwindcss-%06B6D4.svg?style=for-the-badge&logo=tailwindcss&logoColor=white)  

**백엔드**

![SPRING-BOOT](https://img.shields.io/badge/SPRING--BOOT-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![SPRING-CLOUD-GATEWAY](https://img.shields.io/badge/SPRING--CLOUD--GATEWAY-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
![websocket](https://img.shields.io/badge/websocket-%2300D8FF.svg?style=for-the-badge&logo=websocket&logoColor=white)  

**인프라**  

![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![redis](https://img.shields.io/badge/redis-%23DC382D.svg?style=for-the-badge&logo=redis&logoColor=white)  
![rabbitmq](https://img.shields.io/badge/rabbitmq-%23FF6600.svg?style=for-the-badge&logo=rabbitmq&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639.svg?style=for-the-badge&logo=nginx&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)  

**협업툴**  

![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)  

## 📂ERD 및 시스템 아키텍처  

**ERD**  
<img src="https://github.com/user-attachments/assets/2758c181-e7f6-4f0d-9c03-f195cad90f3b" alt="image" width="700"/>

**MSA 아키텍처**  
<img src="https://github.com/user-attachments/assets/8877eaba-30ff-4d58-876c-09933dc68e24" alt="image" width="700"/>  

**인프라 아키텍처**  
<img src="https://github.com/user-attachments/assets/4f595fb5-e4a2-479a-990f-f2de427f9911" alt="image" width="700"/>  

## 🖼 주요 화면

## 랜딩페이지

### 💵 메인

<img src="https://github.com/user-attachments/assets/52455f4b-7304-4801-a4df-ac148d4ffd0c" width="230"/>


## 회원관리

### 💵 회원가입
<img src="https://github.com/user-attachments/assets/95fa5c5a-fb71-4c15-9015-8d7670dce8f7" width="230"/>
<img src="https://github.com/user-attachments/assets/ee88771a-91ca-4ba5-b78b-9a5786e19667" width="230"/>
<img src="https://github.com/user-attachments/assets/8778cff9-aff2-4d73-afbd-37bbab6f13e9" width="230"/>


### 💵 개인 계좌 개설
<img src="https://github.com/user-attachments/assets/d16f3a08-0368-4761-8269-49c14c772419" width="230"/>
<img src="https://github.com/user-attachments/assets/86af278e-c687-4c62-b1e6-5e106e11144d" width="230"/>
<img src="https://github.com/user-attachments/assets/a148de78-daa0-4016-aeeb-a2356ec94449" width="230"/>


## 모임 

### 💵 모임 생성 
<img src="https://github.com/user-attachments/assets/9626c0ce-e1b8-45e8-8e87-df2a6194aa6a" width="230"/>
<img src="https://github.com/user-attachments/assets/1ae6a574-0019-44e6-aaeb-13b56d117ba4" width="230"/>
<img src="https://github.com/user-attachments/assets/ec760354-a4db-4304-9e44-108560a93ed2" width="230"/>
<img src="https://github.com/user-attachments/assets/0fd20f26-8e3b-4dc7-aba3-51d28a7f9320" width="230"/>
<img src="https://github.com/user-attachments/assets/4668c4fd-6ecc-40b8-bd91-6f5286a2aca6" width="230"/>



### 💵 매인 모임 페이지 및 상세 페이지
<img src="https://github.com/user-attachments/assets/c8442cda-8c6f-45da-af25-9852e24938cb" width="230"/>
<img src="https://github.com/user-attachments/assets/3d6c6eba-0581-4483-b5b9-0be0bedbd8ed" width="230"/>


### 💵 규칙 제안 / 매매 제안 
<img src="https://github.com/user-attachments/assets/ff8f78d6-9c55-412a-9ce7-4ee25ea60f2e" width="230"/>
<img src="https://github.com/user-attachments/assets/3d9c3e07-9ec0-4f87-af85-fcce0fc81683" width="230"/>

### 💵 채팅   
<img src="https://github.com/user-attachments/assets/49000ebf-9107-43a9-8ac7-b595eb689e23" width="230"/>


## 주식
<img src="https://github.com/user-attachments/assets/6c5babf2-1abe-4583-af2a-715dec6add5c" width="230"/>
<img src="https://github.com/user-attachments/assets/98821635-2a1d-46a0-91cf-d516ed7de14a" width="230"/>

### 💵 매수 / 매도 제안
<img src="https://github.com/user-attachments/assets/a0734568-9881-43c3-80dc-b55e7327309d" width="230"/>
<img src="https://github.com/user-attachments/assets/e09664d9-09b5-4959-a4ea-ca8ae64e7387" width="230"/>


## 순위 및 대시보드

### 💵 순위 및 대시보드
<img src="https://github.com/user-attachments/assets/2cd7eed3-c395-4002-baaa-5f7cddbfbb15" width="230"/>
<img src="https://github.com/user-attachments/assets/925b28a5-c304-4176-a75a-a4ec66529e45" width="230"/>



## 컨벤션

### 📍 Git 컨벤션

```
<컨벤션> : <설명>
```

| 컨벤션   | 설명                                                                                                                            |
| -------- | ------------------------------------------------------------------------------------------------------------------------------- |
| feat     | 새로운 기능과 관련된 것을 의미한다.                                                                                             |
| fix      | 오류와 같은 것을 수정했을 때 사용한다.                                                                                          |
| docs     | 문서와 관련하여 수정한 부분이 있을 때 사용한다.                                                                                 |
| style    | 코드의 변화와 관련없는 포맷이나 세미콜론을 놓친 것과 같은 부분들을 의미한다.                                                    |
| refactor | 코드의 리팩토링을 의미한다.                                                                                                     |
| test     | test를 추가하거나 수정했을 때를 의미한다.                                                                                       |
| chore    | build와 관련된 부분, 패키지 매니저 설정 등 여러가지 production code와 무관한 부분 들을 의미한다. 말 그대로 자질구레한 일들이다. |
| add      | 이미지 등의 정적 자원 추가를 의미한다.                                                                                          |
| init     | 초기 설정 세팅을 의미한다.                                                                                                      |
| rename   | 파일 혹은 폴더 명을 수정하거나 옮기는 작업을 의미한다.                                                                          |
