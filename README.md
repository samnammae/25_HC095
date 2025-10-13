# IncluKiosk: 모두를 위한 적응형 스마트 키오스크

<img src="./file/img/thumbnail.png" alt="아키텍처" style="border-radius:12px;"/>

<br>

## 💡 1. 프로젝트 개요

### 1-1. 프로젝트 소개

**프로젝트 명** : 한이음 드림업 AI검색 서비스  
**프로젝트 정의** : 사용자의 검색 의도를 이해하고 최적의 정보를 제공하는 **AI 기반 맞춤형 검색 서비스**

### 1-2. 개발 배경 및 필요성

현대 사회는 방대한 정보가 실시간으로 생성되고 축적되고 있습니다. 그러나 사용자가 원하는 정확한 정보를 찾기 위해서는 여전히 많은 시간과 노력이 필요합니다.  
기존 키워드 기반 검색 방식은 사용자의 **맥락이나 의도**를 충분히 반영하지 못해 효율성이 떨어집니다.  
따라서 사용자의 검색 목적을 인공지능이 이해하고 **개인화된 결과를 제공하는 맞춤형 검색 서비스**가 필요합니다.

### 1-3. 프로젝트 특장점

- ✅ 사용자의 **검색 의도와 맥락을 이해**하는 자연어 이해 기반 검색 서비스
- 🔍 단순 키워드 매칭이 아닌 **의미 기반 정보 추천 및 순위화**
- 👤 개인별 기록과 관심사를 반영한 **맞춤형 검색 결과 제공**
- 🌐 다양한 데이터 소스를 연동해 **멀티도메인 활용 가능성 확보**
- 🤖 최신 AI/ML 프레임워크와 대규모 언어모델(LLM)을 활용한 **최적화된 사용자 경험**

### 1-4. 주요 기능

- **AI 맞춤 검색 서비스** : 검색 의도를 분석하고 개인화된 결과 제공
- **자연어 질의 처리** : 키워드뿐 아니라 문장 단위 질문도 이해 가능
- **의미 기반 추천** : 단순한 ‘정확 단어 일치’가 아닌 맥락과 의미 기반 결과 제공
- **맞춤형 필터링 및 정렬** : 사용자 성향에 따른 결과 필터 및 순위 조정
- **멀티플랫폼 지원** : 웹·모바일 등 다양한 환경에서 최적화된 검색 경험 제공

### 1-5. 기대 효과 및 활용 분야

**기대 효과**

- 검색 품질 향상 및 정보 탐색 효율 극대화
- 다양한 산업 분야에서 데이터 활용성 확대

**활용 분야**

- 학술·연구
- 커머스·쇼핑
- 헬스케어
- 뉴스·미디어
- 기업 내부 문서 검색 등

### 1-6. 기술 스택

| 구분                    | 기술                                                                                                                                                                                                                                                                                                          |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **프론트엔드**          | React.js, Next.js, TypeScript, react-query, zustand, Electron,                                                                                                                                                                                                                                                |
| **백엔드**              | Java, Spring Boot                                                                                                                                                                                                                                                                                             |
| **AI/ML**               | Mediapipe, OpenCV, PyCoral                                                                                                                                                                                                                                                                                    |
| **하드웨어 제어 (IoT)** | Python, websockets                                                                                                                                                                                                                                                                                            |
| **데이터베이스**        | MongoDB, MySQL                                                                                                                                                                                                                                                                                                |
| **클라우드**            | AWS (EC2 · S3 · CloudFront · Route53)                                                                                                                                                                                                                                                                         |
| **하드웨어 구성**       | 라즈베리파이 4 Model B (8GB RAM), 라즈베리파이 카메라모듈 V2, 리니어 엑추에이터, TB6600 스테핑 모터 드라이버, DC 24V 파워서플라이, 적외선 인체 감지센서(HC-SR501), 15.6인치 정전식 터치 디스플레이, 노이즈 억제·방향 인식 마이크 (Seeed ReSpeaker Mic Array), DC-DC 컨버터(3.3V 출력), 점퍼와이어 및 커넥터류 |

## 🧑🏻‍💻 2. 팀원 소개

|                                                             **김도영 멘토**                                                              |                                                                                  **정한울**                                                                                   |                                                                                       **강은송**                                                                                        |                                                                                   **김도현**                                                                                    |
| :--------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="./file/profile/doyeong.jpeg" alt="김도영" style="height:240px; width:180px; object-fit:cover; border-radius:8px; "><br/> <br/> | <img src="./file/profile/hanuljeong.jpg" alt="정한울" style="height:240px; width:180px; object-fit:cover; border-radius:8px;"><br/>_[ @jho7535 ](https://github.com/jho7535)_ | <img src="./file/profile/kangeunsong.jpeg" alt="강은송" style="height:240px; width:180px; object-fit:cover; border-radius:8px;"><br/>_[ @kangeunsong ](https://github.com/kangeunsong)_ | <img src="./file/profile/dohyun.png" alt="김도현" style="height:240px; width:180px; object-fit:cover; border-radius:8px;"><br/>_[ @kdhqwe1030 ](https://github.com/kdhqwe1030)_ |
|                                                     • 프로젝트 멘토 <br> • 기술 자문                                                     |                                                                        • 백엔드 개발 <br> • 서버 관리                                                                         |                                                                           • 하드웨어 제어 <br> • AI 모델 개발                                                                           |                                                                       • 프론트엔드 개발 <br> • UI/UX 설계                                                                       |

<br>

<br>

## 💡 3. 시스템 구성도

#### 🧩 서비스 구성도

<div style="background-color:white; border-radius:12px;"><img src="./file/img/architecture.png" alt="아키텍처"/></div>

#### 🗂️ 엔티티 관계도

image

> (참고) S/W 구성도, H/W 구성도, 서비스 흐름도 등을 작성합니다.  
> 시스템의 동작 과정 등을 추가할 수도 있습니다.

<br>

<br>

## 📽️ 4. 작품 소개영상

[![한이음 드림업 프로젝트 소개](https://img.youtube.com/vi/61OIRqonIQM/0.jpg)](https://www.youtube.com/watch?v=61OIRqonIQM)

<br>

<br>

## 💡 5. 핵심 소스코드

소스코드 설명 : API를 활용해서 자동 배포를 생성하는 메서드입니다.

```java
private static void start_deployment(JsonObject jsonObject) {
    String user = jsonObject.get("user").getAsJsonObject().get("login").getAsString();
    Map<String, String> map = new HashMap<>();
    map.put("environment", "QA");
    map.put("deploy_user", user);
    Gson gson = new Gson();
    String payload = gson.toJson(map);

    try {
        GitHub gitHub = GitHubBuilder.fromEnvironment().build();
        GHRepository repository = gitHub.getRepository(
                jsonObject.get("head").getAsJsonObject()
                        .get("repo").getAsJsonObject()
                        .get("full_name").getAsString());
        GHDeployment deployment =
                new GHDeploymentBuilder(
                        repository,
                        jsonObject.get("head").getAsJsonObject().get("sha").getAsString()
                ).description("Auto Deploy after merge").payload(payload).autoMerge(false).create();
    } catch (IOException e) {
        e.printStackTrace();
    }
}
```
