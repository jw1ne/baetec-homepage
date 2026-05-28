# 🏢 비에이텍 주식회사(BAETEC) 기업 공식 홈페이지 개발 프로젝트
> **Project Type:** 기업 정보 기반의 반응형 웹 퍼블리싱 및 Front-end 개발  
> **Deployment:** [🚀 Netlify를 통해 배포된 실시간 웹사이트 보기](https://euphonious-nasturtium-ff5516.netlify.app)

---

## 📌 프로젝트 소개
모터펌프 및 진공 시스템 전문 제조 기업인 **비에이텍(주)**의 브랜드 가치를 극대화하기 위해 제작한 공식 웹 홈페이지 프로젝트입니다. 
대기업(한화에어로스페이스)의 세련되고 신뢰감 주는 **딥 네이비(#0b0f19)** 및 **오렌지 포인트 컬러(#ff6b00)** 톤앤매너를 벤치마킹하여, 
제조업 기반 기업의 투박한 이미지를 탈피하고 미래지향적인 웹 인터페이스를 구현했습니다.

## ✨ 핵심 개발 및 디자인 요소
* **시그니처 디자인 (Tone & Manner):** 신뢰도를 높여주는 다크 모드 기반 인프라스트럭처 테마와 핵심 영역에 시선을 끄는 고대비 오렌지 하이라이트 컬러 매칭
* **반응형 웹 디자인 (Responsive Web):** 미디어 쿼리(Media Query)를 활용하여 PC, 태블릿, 모바일 등 모든 디바이스 환경에서 UI가 깨지지 않고 최적화되는 Flex/Grid 레이아웃 설계
* **컴포넌트 기반 제품 소개:** 비에이텍의 주력 생산 라인인 *모터펌프, 전진공동펌프, 부스터펌프*를 카드 세션으로 시각화하여 사용자가 제품 정보를 직관적으로 파악할 수 있도록 구성
* **Netlify 자동 배포 자동화:** GitHub 저장소와 Netlify 호스팅 서비스를 연동하여 소스코드 푸시(Push) 시 웹사이트에 실시간으로 반영되는 CI/CD 파이프라인 경험

## 🛠️ 사용 기술 및 개발 환경 (Tech Stack)
* **Structure:** HTML5 (웹 표준 및 시맨틱 태그 준수)
* **Styling:** CSS3 (CSS Variables 기반 테마 커스텀, Flexbox, Grid Layout, Media Queries)
* **Font / Icons:** Pretendard (가독성을 극대화한 시스템 폰트 적용)
* **Hosting & Deployment:** Netlify

---

## 💻 소스코드 하이라이트 (CSS Architecture)
유지보수가 용이하도록 CSS 변수(`:root`)를 활용해 기업 고유의 컬러 시스템을 정의하고 일관성 있게 설계했습니다.

```css
:root {
    --bg-primary: #0b0f19;       /* 딥 네이비 블랙 (주 배경) */
    --bg-secondary: #161c2d;     /* 카드 및 섹션 배경 */
    --text-main: #ffffff;        /* 메인 텍스트 */
    --text-sub: #94a3b8;         /* 서브 텍스트 */
    --point-color: #ff6b00;      /* 비에이텍 오렌지 포인트 */
    --border-color: #2d3748;
}
