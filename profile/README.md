## Hi there 👋

# 🎮 Word Game Project Overview

  ## 📌 프로젝트 소개
  분산화된 단어 추측 게임으로, AI가 선정한 단어를 플레이어가 맞추는 방식입니다. 블록체인 기술과 AI를 결합하여 공정성과 투명성을 보장합니다.

  ## 🏗 시스템 아키텍처

  ![image](https://github.com/user-attachments/assets/7b867dfc-1e72-4b5b-b911-0c476400550b)

  ### Frontend (FE)
  - **주요 기능**
    - 사용자 인터페이스 제공
    - 단어 입력 및 예측 기능
    - 게임 상태 실시간 표시
    - 상금 수령 현황 표시
  - **기술 스택**
    - Web3 지원 웹 애플리케이션

  ### Backend (BE)
  - **주요 기능**
    - 게임 로직 처리
    - 유사도 데이터 관리
    - Proof Generation
    - AI 백엔드와의 통신 관리
  - **핵심 처리**
    - 유사도 기반 힌트 시스템
    - ZK Proof 생성

  ### AI Backend (AI_BE)
  - **주요 기능**
    - 게임용 단어 선정
    - 단어 유사도 계산
    - 상위 1000개 유사 단어 제공
  - **특징**
    - 공정한 단어 선정 알고리즘
    - 효율적인 유사도 계산 시스템

  ### Smart Contract
  - **주요 기능**
    - 게임 상금 관리
    - 검증 키 저장 및 관리
    - ZK Proof 검증
    - 자동 상금 지급
  - **보안 특징**
    - 투명한 검증 시스템
    - 안전한 자금 관리

  ## 🔄 게임 프로세스

  1. **게임 초기화**
     - AI 시스템의 단어 선정
     - 스마트 컨트랙트에 게임 정보 등록
     - 상금 풀 설정

  2. **게임 진행**
     - 플레이어의 단어 예측
     - 실시간 피드백 제공
     - 유사도 기반 힌트 시스템

  3. **정답 처리**
     - 정답 확인 및 검증
     - ZK Proof 생성 및 검증
     - 스마트 컨트랙트 기반 상금 지급






<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
