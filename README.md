# 📜 유교준 포트폴리오

> 유교준(Yoo Gyojun) - Amchoking5 포트폴리오

<br />

# 👋 Intro

> 안녕하세요! ***"밤낮으로 몰입해 사용자의 문제를 해결하는 개발자"*** 유교준입니다!  
> 중학교때 프로그래밍을 시작해 개발의 재미를 알게되어 주변사람들을 위한 프로그램을 만들어 왔습니다.  
> 고등학교때 정보동아리 GSALGO의 부장으로 활동하였으며, 대학교때 로봇제작 동아리 MR와 인공지능 동아리 Include에서 활동했습니다.  
> 대학교 재학중 인턴과 프리랜서 활동으로 Python Fastapi와 AI를 활용한 프로젝트를 진행하였으며, MVP개발을 맡아 진행했습니다.  
> 이러한 서비스 개발 경험을 바탕으로 사용자를 행복하게 만들어주는 개발자를 목표로 끊임없이 노력하고 있습니다.  

<br />

# 🎒 Education

> 경산과학고등학교 입학 2017.03  
> 경산과학고등학교 졸업 2018.02  
> 한국과학기술원(KAIST) 입학 2018.03  
> 한국과학기술원(KAIST) 졸업예정 2026.02   

<br />

# 📝 Intern Projects

> 인턴활동하며 진행했던 주요 프로젝트입니다.  
> 솔리드이엔지 AI부서에서 인턴 및 프리랜서로 근무했습니다.(2024.06 ~ 2025.05)  
> 네이버클라우드 Video Generation부서에서 인턴으로 근무했습니다.(2026.02 ~ 2026.08)   
> ***프로젝트 MVP 핵심 알고리즘 개발***을 맡아 진행했습니다.  

<br />

# 1. 솔리드이엔지 인턴

## 1. 💬 세종시 챗봇 AI 충녕

> 세종시 관련 데이터를 스스로 학습하여 답변을 제공해주는 시스템입니다.  
> Langchain과 RAG를 활용해 질문 query와 관련된 문장을 찾고, LLM을 활용해 답변을 생성합니다.  
>
> - 개발기간 : 2024.06 ~ 2024.10
> - 개발인원 : 3명
> - 핵심 역할 : 답변 정확도 향상 및 할루시네이션 억제 (전처리 구조 개선, 코사인 유사도 Top k 적용, Threshold 적용)
>
>> Back-end
>> - Language : python3  
>> - Skill : Fastapi, Pinecone DB, langchain, poetry
>
>> Front-end
>> - Language : javascript, typescript
>> - Skill : React.js
>>
>> [프로젝트 상세 설명](https://github.com/Amchoking5/Team_Project/tree/main/Intern%20Project/%EC%84%B8%EC%A2%85%EC%8B%9C%20%EC%B1%97%EB%B4%87%20AI%20%EC%B6%A9%EB%85%95)
>> [참고 자료](https://aichat.sejong.go.kr/)

<br />

## 2. 🏭 KAF 방사 공장 매뉴얼 챗봇

> 세종시 챗봇 AI 충녕의 후속 프로젝트입니다.  
> KAF 방사 공장의 메뉴얼 데이터를 학습하여 답변을 제공하고, 매뉴얼 생성을 도와주는 시스템입니다.  
> 다국어 기능, 음성 입출력 기능, LLM 답변 생성시 이미지 출력 기능을 구현했습니다.  
> 관리자 페이지에서 파일 업로드, 검색 삭제 가능하며, 피드백 페이지에서 잘못된 답변을 수정하여 다음 출력을 개선할 수 있습니다.  
>
> - 개발기간 : 2024.11 ~ 2025.01
> - 개발인원 : 3명
> - 핵심 역할 : 관리자 및 피드백 페이지 개발 (Backend, Frontend), 참고자료 및 이미지 출력을 위한 DB 구조 변경
>
>> Back-end
>> - Language : python3  
>> - Skill : Fastapi, Pinecone DB, langchain, poetry, whisper, docker
>
>> Front-end
>> - Language : javascript, typescript
>> - Skill : React.js
>>
>> [프로젝트 상세 설명](https://github.com/Amchoking5/Team_Project/tree/main/Intern%20Project/KAF%20%EB%B0%A9%EC%82%AC%20%EA%B3%B5%EC%9E%A5%20%EB%A7%A4%EB%89%B4%EC%96%BC%20%EC%B1%97%EB%B4%87)

<br />

## 3. 🖼️ 마음돌봄 프로젝트

> AI와 대화하며 위로를 받는 심리 치료 프로젝트입니다.  
> ***주변에 속마음을 표현하지 않는 아동의 감정을 더욱 이해할 수 있게 AI로 이끌어내보자*** 라는 아이디어에서 시작했습니다.  
> 사용자의 성격과 심리 테스트 결과를 받아 본인만의 캐릭터를 생성하고, AI와 대화하며 오늘 하루를 돌아봅니다.  
> 대화 내용은 이미지 생성형 AI를 사용해 그림일기로 만들어지며, 갤러리에서 확인할 수 있습니다.   
>
> - 개발기간 : 2024.02 ~ 2025.05
> - 개발인원 : 3명
> - 핵심 역할 : 멀티턴 LLM, Stable diffusion 3 API 서버 연결, 캐릭터 일관성 향상(프롬프트 딕셔너리, 사용자별 Lora 생성 및 관리)
>
>> Back-end
>> - Language : python3  
>> - Skill : Fastapi, langchain
>
>> Front-end
>> - Language : python, javascript
>> - Skill : gradio, react.js
>>
>> [프로젝트 상세 설명](https://github.com/Amchoking5/Team_Project/tree/main/Intern%20Project/%EB%A7%88%EC%9D%8C%EB%8F%8C%EB%B4%84%20%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)

<br />

# 2. 네이버클라우드 인턴

## 1. 📊 QA 데이터 수집 웹 페이지 : Annohub

> 경쟁사 영상 생성 모델과 비교하여 성능을 파악하기 위한 벤치마크 QA 페이지입니다.   
> Java Script와 Node JS를 사용해 프론트엔드와 벡엔드를 구성했습니다.   
> PairWise, PointWise 방식으로 각각 QA의 점수를 측정하고, 결과를 Chroma DB에 저장합니다.   
>
> - 개발기간 : 2026.02 ~ 2026.03
> - 개발인원 : 1명 + 멘토
> - 핵심 역할 : QA 평가 데이터 수집 파이프라인 구축 및 웹 페이지 제작
>
>> Back-end
>> - Language : javascript
>> - Skill : Node.js, Mongo DB, 공공데이터 포탈 API
>
>> Front-end
>> - Language : javascript, typescript
>> - Skill : React.js
>>
>> [프로젝트 상세 설명](https://github.com/Amchoking5/Team_Project/tree/main/Intern%20Project/Annohub)

<br />

## 2. ⚙️ 스스로 개선하는 AI : Necro Flow

> 영상생성 모델을 고도화 하기위한 프로젝트입니다.   
> 구간별로 체크포인트를 만들어 이전 체크포인트 혹은 타겟 체크포인트의 영상생성 모델과 비교하여 스스로 성능을 개선합니다.   
> Unified reward model을 사용해 두 영상을 비교하여, AI로 약점을 분석한 뒤, 오픈소스 사이트에서 해당 약점을 보완하기 위한 데이터 셋을 추가 수집하여 재학습합니다.   
> 로그를 통해 진행상황 및 AI분석 리포트, 데이터 수집 관계도 등을 확인할 수 있습니다.   
>
> - 개발기간 : 2026.03 ~ 2025.06
> - 개발인원 : 1인 + 멘토
> - 핵심 역할 : 전체 파이프라인 설계, 기존 코드기반 작업들을 fastapi 서버를 활용하여 api통신으로 결합
>
>> Back-end
>> - Language : python3  
>> - Skill : Fastapi, Chroma DB, Mongo DB, langchain, Lightx2v, Unified reward model, face detection, OCR, api data crawl, langchain
>
>> Front-end
>> - Language : javascript, typescript
>> - Skill : React.js, Vite
>>
>> [프로젝트 상세 설명](https://github.com/Amchoking5/Team_Project/blob/main/Intern%20Project/NecroFlow/README.md)

<br />

## 3. 🎨 광고 영상 생성 프로젝트 : ADGen

> 네이버 영상생성 AI를 활용한 광고 생성 프로젝트입니다.    
> 광고 URL을 입력하면 데이터를 수집해 핵심 정보들을 수집하여, 선택한 광고전략과 목표시간에 맞는 스토리보드를 구성합니다.   
> 이후 광고 레퍼런스를 분석하여 시작이미지를 생성한 뒤 I2V로 광고영상을 생성합니다.   
>
> - 개발기간 : 2026.07 ~ 2026.08
> - 개발인원 : 1인 + 멘토
> - 핵심 역할 : 영상생성 일관성 유지, AI 스토리보드 및 광고 생성 파이프라인 설계
>
>> Back-end
>> - Language : python3  
>> - Skill : Fastapi, Chat GPT, langchain, lightx2v
>
>> Front-end
>> - Language : javascript, typescript
>> - Skill : react.js, vite
>>
>> [프로젝트 상세 설명](https://github.com/Amchoking5/Team_Project/tree/main/Intern%20Project/ADGen)

<br />

# 📝 Team Projects

> 대학생활에서 진행한 팀 프로젝트입니다.  
> 동아리 및 연구 수업에서 진행하였습니다.  

<br />

## 1. 🍎 Fruit box RL

> ***심층강화학습과 게임AI*** 강의에서 진행한 팀 프로젝트입니다.  
> 사과게임에서 고득점을 얻기위한 AI를 개발하는 활동을 하였습니다.  
> 파이썬 환경으로 코드를 옮긴 뒤, RLlib, CNN, Monte Carlo, MCTS 등 다양한 방법으로 시도하였습니다.   
>
> - 개발기간 : 2024.05 ~ 2024.06
> - 핵심 역할 : Fruit box 파이썬 클론 코딩, Monte Carlo Search
>
>> - Language : python
>> - Skill : RLlib, numpy
>>
>> [프로젝트 상세 설명](https://github.com/Amchoking5/Team_Project/tree/main/Fruit%20Box)
>
>> [참고 자료](https://www.youtube.com/watch?v=gtc1nRaxyMQ)

<br />

## 2. 🤖 개미 로봇

> 카이스트 로봇제작 동아리 MR에서 진행한 팀 프로젝트입니다.  
> 개미 로봇은 물류 이동 로봇으로, 무거운 물체를 만났을 때 서로 협력하여 물건을 옮기는 로봇입니다.  
>
> - 개발기간 : 2018.03 ~ 2018.12
> - 핵심 역할 : 이동경로 프로토타입 제작, 아두이노 회로 제작 및 코딩
>
>> - Language : C, C++
>> - Skill : arduino
>
>> [참고 자료](https://mr.kaist.ac.kr/projects/74)

<br />

# 📝 Problem Solving

> Baekjoon과 Leetcode에서 문제를 풀며 문제해결능력을 길렀습니다.  
> 주로 C, C++, Python을 활용해 문제를 해결하였습니다.  
> 꾸준한 공부를 통해 백준 프레티넘 등급을 달성하였습니다.  
>
> <img src="https://github.com/user-attachments/assets/7b5b50cb-7615-4dee-bd7c-af8989ed55ff" style="margin-top: 50px" />  
>
>> [참고 자료](https://github.com/Amchoking5/Problem_Solving)

<br />

# 📞 Contact

- 이메일 : amchoking@naver.com  
- 전화번호 : 010-3341-4316  
- 깃허브 : <a href="https://github.com/Amchoking5">
  <img src="https://user-images.githubusercontent.com/68724828/185908612-22f4d219-78a7-4de7-bb02-deecaa63bffa.png" height="28px" style="margin-top: 10px" />
  </a>
