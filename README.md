<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A0B1220%2C50%3A123047%2C100%3A0B7F79&height=90&section=header&text=&fontSize=1&desc=" width="100%" alt="" />

  <h1>김동현</h1>

  풀스택 개발자 · LLM · RAG · Agent

  <br />

  <img src="https://readme-typing-svg.demolab.com?font=Fira%20Code&weight=500&size=20&pause=800&color=0B7F79&center=true&vCenter=true&width=520&height=28&repeat=false&lines=LLM%20%20%C2%B7%20%20RAG%20%20%C2%B7%20%20Agent%20%20%C2%B7%20%20Fullstack" alt="LLM · RAG · Agent · Fullstack" />
</div>

## 소개

- Next.js · NestJS로 웹 서비스를 설계하고, 프론트와 백엔드를 함께 만들어 왔습니다.
- 지금은 그 경험 위에 LLM 검색·생성 파이프라인(RAG, Agent)을 붙이는 쪽으로 이동하고 있습니다.
- FastAPI와 PostgreSQL(pgvector + FTS/Kiwi)로 하이브리드 검색 RAG를 만들고, LangGraph 채팅 에이전트에서 검색 충분성을 평가해 retrieval depth를 조절합니다.
- 문서·이미지 파이프라인 PoC도 함께 진행하고 있습니다.

## Tech

<div align="center">
  <p><strong>AI / ML</strong></p>
  <img src="https://skillicons.dev/icons?i=python,pytorch" alt="Python, PyTorch" />
  <p><strong>Backend</strong></p>
  <img src="https://skillicons.dev/icons?i=nestjs,spring,fastapi,postgres,docker" alt="NestJS, Spring, FastAPI, PostgreSQL, Docker" />
  <p><strong>Frontend</strong></p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,vue,ts" alt="React, Next.js, Vue, TypeScript" />
</div>

## AI / LLM 프로젝트

<table width="100%">
  <tr>
    <td valign="top" width="50%">
      <b>Hybrid RAG</b><br>
      <sub>비공개 저장소</sub>
      <br><br>
      PostgreSQL pgvector(Dense)와 FTS + Kiwi(Sparse)를 결합한 하이브리드 검색. BGE rerank와 출처 기반 답변을 제공하며, Docker 배포를 지원합니다.
      <br><br>
      <img src="https://img.shields.io/badge/FastAPI-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="FastAPI" /> <img src="https://img.shields.io/badge/PostgreSQL-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="PostgreSQL" /> <img src="https://img.shields.io/badge/pgvector-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="pgvector" /> <img src="https://img.shields.io/badge/Docker-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Docker" />
    </td>
    <td valign="top" width="50%">
      <b>chat-agent</b><br>
      <sub>비공개 저장소</sub>
      <br><br>
      LangGraph 기반 RAG 채팅 에이전트. 충분성 평가기로 retrieve를 반복하고(`top_k` 5→10→20), NestJS API와 Next.js UI로 구성되어 있습니다.
      <br><br>
      <img src="https://img.shields.io/badge/NestJS-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="NestJS" /> <img src="https://img.shields.io/badge/Next.js-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Next.js" /> <img src="https://img.shields.io/badge/LangGraph-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="LangGraph" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <b>RPA 셀프힐링 PoC</b><br>
      <sub>비공개 저장소</sub>
      <br><br>
      브라우저 RPA가 설계 시점의 요소를 찾지 못하면, 규칙과 Laya 결정 모델로 대체 요소를 고르고 실행 엔진이 검증한 뒤에만 한 번 재시도하는 셀프힐링 PoC입니다.
      <br><br>
      <img src="https://img.shields.io/badge/TypeScript-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="TypeScript" /> <img src="https://img.shields.io/badge/Playwright-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Playwright" /> <img src="https://img.shields.io/badge/Laya-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Laya" />
    </td>
    <td valign="top" width="50%">
      <b>수표 직인 대조 PoC</b><br>
      <sub>비공개 저장소</sub>
      <br><br>
      수표 이미지에서 직인을 검출한 뒤, 등록 인감과 매칭하는 비전 파이프라인입니다.
      <br><br>
      <img src="https://img.shields.io/badge/Grounding_DINO-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Grounding DINO" /> <img src="https://img.shields.io/badge/EfficientLoFTR-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="EfficientLoFTR" /> <img src="https://img.shields.io/badge/Real--ESRGAN-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Real-ESRGAN" /> <img src="https://img.shields.io/badge/OpenCV-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="OpenCV" /> <img src="https://img.shields.io/badge/Streamlit-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Streamlit" />
    </td>
  </tr>
</table>

## 웹 사이드 프로젝트

<table width="100%">
  <tr>
    <td valign="top" width="50%">
      <b><a href="https://maparty.kr/">메랜파티</a></b>
      <br><br>
      게임 파티 모집 플랫폼
      <br><br>
      <img src="https://img.shields.io/badge/Next.js-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Next.js" /> <img src="https://img.shields.io/badge/Nest.js-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Nest.js" />
    </td>
    <td valign="top" width="50%">
      <b><a href="https://tetr-sigma.vercel.app/">테트리스</a></b>
      <br><br>
      테트리스
      <br><br>
      <img src="https://img.shields.io/badge/React-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="React" /> <img src="https://img.shields.io/badge/Nest-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Nest" /> <img src="https://img.shields.io/badge/Socket.io-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Socket.io" />
    </td>
  </tr>
  <tr>
    <td valign="top" width="50%">
      <b><a href="https://holy-symbol-timer.vercel.app/">홀심타이머</a></b>
      <br><br>
      타이머
      <br><br>
      <img src="https://img.shields.io/badge/Next.js-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Next.js" /> <img src="https://img.shields.io/badge/Electron-E6EDF7?style=flat-square&labelColor=0B1220&color=123047" alt="Electron" />
    </td>
    <td width="50%"></td>
  </tr>
</table>

---

<div align="center">

이메일: mdc@kakao.com · 포트폴리오: <a href="https://lunatic.monster">lunatic.monster</a> · LinkedIn: <a href="https://www.linkedin.com/in/santa93">in/santa93</a>

</div>
