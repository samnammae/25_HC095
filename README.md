# IncluKiosk: 모두를 위한 적응형 스마트 키오스크

<img src="./file/img/thumbnail.png" alt="아키텍처" style="border-radius:12px;"/>

<br>

## 💡 1. 프로젝트 개요

### 1-1. 프로젝트 소개

* **프로젝트 명**: IncluKiosk
* **프로젝트 정의**: AI 기술(컴퓨터 비전, 시선 추적, LLM)을 활용하여 모든 사용자를 위한 **맞춤형 멀티모달 인터페이스**를 제공하는 포용적(Inclusive) 키오스크 시스템

### 1-2. 개발 배경 및 필요성

* **문제 인식**: 키오스크 보편화에 따른 디지털 격차 심화
    * 고정된 화면 높이와 터치 중심의 단일 방식으로 인해 특정 사용자층(휠체어 사용자, 노인, 시각장애인 등)의 이용이 어려움
* **사회적 요구**: 포용적 기술과 보편적 디자인에 대한 사회적 필요성 증대
* **프로젝트 목표**: 모든 사용자가 차별 없이 서비스를 이용하는 환경을 조성하여 디지털 소외 문제 해결

### 1-3. 프로젝트 특장점

* **사용자 자동 인식 및 화면 최적화**
    * 컴퓨터 비전으로 사용자 신장을 인식, 최적의 높이로 자동 조절
    * 사용자 상황에 맞는 맞춤형 UI 제공
* **다중 입력 방식을 지원하는 멀티모달 인터페이스**
    * 기본 터치 방식에 시선 추적(Eye-tracking) 및 음성 인식 기능 통합
    * 사용자가 자신에게 가장 편리한 입력 방식을 선택 가능
* **LLM 기반 지능형 대화 시스템**
    * 단순 명령어를 넘어, 문맥을 이해하는 자연어 처리 능력 확보
    * 메뉴 추천, 특정 성분 문의 등 복합적인 질문에 대한 대화형 응대 가능

### 1-4. 주요 기능

* **적응형 화면 높이 조절**: AI 기반 사용자 인식 및 화면 높이 자동 조절
* **아이트래킹 인터페이스**: 시선 움직임을 통한 메뉴 선택 및 제어
* **음성 챗봇**: LLM 기반 음성 주문 및 대화형 질의응답
* **다국어 지원**: 한국어, 영어, 중국어 등 다국어 인터페이스 제공
* **통합 아키텍처**: RESTful API 기반의 일관된 사용자 경험

### 1-5. 기대 효과 및 활용 분야

* **기대 효과**
    * **기술적 측면**: 멀티모달 AI 인터페이스로 고도화된 사용자 경험 제공
    * **사회적 측면**: 디지털 약자의 정보 접근성 및 자립도 향상을 통한 디지털 포용성 실현
    * **시장성**: 고령화 및 장애인 권익 확대에 따른 접근성 중심 키오스크 수요 충족

* **활용 분야**
    * **공공기관**: 민원 접수 및 안내 시스템
    * **의료기관**: 접수, 수납, 안내 시스템
    * **교통시설**: 발권 및 다국어 안내 시스템 (공항, 터미널 등)
    * **상업시설**: 주문 시스템 (카페, 식당 등)
    * **교육·문화시설**: 안내 및 예약 시스템 (도서관, 박물관 등)

### 1-6. 기술 스택

| 구분                    | 기술                                                                                                                                                                                                                                                                                                          |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **FE**          | React.js, Next.js, TypeScript, react-query, zustand, Electron,                                                                                                                                                                                                                                                |
| **BE**              | Java, Spring Boot, Gemini API                                                                                                                                                                                                                                                                                            |
| **AI/ML**               | MediaPipe, OpenCV, PyCoral, TensorFlowLite, MobileNet-V2                                                                                                                                                                                                                                                                                    |
| **HW (IoT)** | Python, WebSockets                                                                                                                                                                                                                                                                                            |
| **DB**        | MongoDB, MySQL                                                                                                                                                                                                                                                                                                |
| **Cloud**            | AWS (EC2 · S3 · CloudFront · Route53)                                                                                                                                                                                                                                                                         |
| **HW**       | 라즈베리파이 4 Model B (8GB RAM), 라즈베리파이 카메라모듈 V2, <br> Seeed ReSpeaker Mic Array, 15.6인치 정전식 터치 디스플레이, <br> 리니어 액추에이터 및 TB6600 모터 드라이버 |

## 🧑🏻‍💻 2. 팀원 소개

<div align="center">

| **정한울** (_[@jho7535](https://github.com/jho7535)_) | **강은송** (_[@kangeunsong](https://github.com/kangeunsong)_) | **김도현** (_[@kdhqwe1030](https://github.com/kdhqwe1030)_) | **김도영** |
|:---:|:---:|:---:|:---:|
| <img src="./file/profile/hanuljeong.jpg" alt="정한울" style="height:240px; width:180px; object-fit:cover; border-radius:8px;"> | <img src="./file/profile/kangeunsong.jpeg" alt="강은송" style="height:240px; width:180px; object-fit:cover; border-radius:8px;"> | <img src="./file/profile/dohyun.png" alt="김도현" style="height:240px; width:180px; object-fit:cover; border-radius:8px;"> | <img src="./file/profile/doyeong.jpeg" alt="김도영" style="height:240px; width:180px; object-fit:cover; border-radius:8px;"> |
|  • 백엔드 개발<br>• 서버 관리 | • 하드웨어 제어<br>• AI 모델 개발 | • 프론트엔드 개발<br>• UI/UX 설계 | • 프로젝트 멘토<br>• 기술 자문 |

</div>

<br>

## 💡 3. 시스템 구성도

#### 🧩 시스템 아키텍처

<img src="./file/img/architecture.png" width="100%" height="100%" />

<br>

#### 🗂️ ERD

<img src="./file/img/ERD.png" width="100%" height="100%" />

<br>

<br>

## 📽️ 4. 작품 소개영상

[![한이음 드림업 프로젝트 소개](./file/img/youtube_thumbnail.png)](https://www.youtube.com/watch?v=61OIRqonIQM)

<br>

<br>

## 💡 5. 핵심 소스코드

### 5-1. WebSocket 통신

 - 라즈베리파이와의 WebSocket 통신을 통해 STT/TTS 흐름을 제어하고, 백엔드 REST API(ChatAPI) 를 통해 챗봇 대화를 처리하는 핵심 로직입니다.

```tsx
// [핵심 함수] Chat.tsx
// - sendMessage(): 프론트 → 라즈베리파이 명령 전송
// - chatAPI.sendChat(): 프론트 → 백엔드 챗봇 대화 요청
// - case 구문: 라즈베리파이 → 프론트로 수신되는 메시지 제어

useEffect(() => {
  if (!isConnected) return;

  const handle = async (msg: SocketMessage) => {
    switch (msg.type) {

      // 1️⃣ 안내 음성 종료 → STT 시작 (라즈베리파이로부터 수신)
      case "END_GUIDE":
        sendMessage({ type: "STT_ON" }); // 라즈베리파이에 음성인식 시작 명령
        setIsListening(true);
        break;

      // 2️⃣ 음성 인식 완료(STT_OFF) → 백엔드로 사용자 발화 전달
      case "STT_OFF":
        setChatLogs(prev => […prev, { message: msg.message, isBot: false }]);

        const res = await chatAPI.sendChat(shopId, {
          sessionId,
          message: msg.message,
          storeId: Number(shopId),
          storeName: shopName,
        });

        const answer = res?.aiMessage || "죄송합니다, 답변을 불러오지 못했습니다.";
        setChatLogs(prev => […prev, { message: answer, isBot: true }]);

        // 챗봇 응답을 라즈베리파이에 전달 → 음성 출력(TTS)
        sendMessage({ type: "TTS_ON", message: answer });
        break;

      // 3️⃣ 음성 출력 종료(TTS_OFF) → 다음 발화 대기
      case "TTS_OFF":
        sendMessage({ type: "STT_ON" }); // 다음 음성인식 시작
        setIsListening(true);
        break;
    }
  };

  addOnMessage(handle);
  return () => removeOnMessage(handle);
}, [isConnected]);
```