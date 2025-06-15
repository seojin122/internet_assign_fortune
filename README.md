# 🎵 오늘의 감성 노래 추천기

사용자의 기분과 시간대를 입력하면,  
AI가 감성적인 노래 3곡을 추천해주는 웹 애플리케이션입니다.

Google Gemini API를 활용하여  
기분과 시간에 어울리는 노래와 간단한 설명을 제공합니다.

---

## 💻 기술 스택

- HTML / CSS / JavaScript
- 백엔드 API: Google Gemini API (Vercel 배포)
- 프론트엔드 배포: GitHub Pages

---

## ✨ 주요 기능

- 사용자의 기분(mood)과 시간대(timeOfDay)를 입력받음
- AI가 노래 3곡을 추천하고, 각 곡에 대한 감성적인 설명 제공
- 결과는 실시간으로 웹 페이지에 표시됨

---

## 🖱️ 사용 방법

1. 웹페이지 접속:  
   👉 [https://yourid.github.io/duksung-music-frontend/](https://yourid.github.io/duksung-music-frontend/)

2. 기분을 입력하고 시간대를 선택

3. "노래 추천 받기" 버튼 클릭

4. 결과가 아래에 바로 표시됨

---

## 🔗 API 연동 정보

- API 주소: `https://internet-assign2.vercel.app/api`
- 요청 방식: `POST`
- 요청 형식:
  ```json
  {
    "mood": "우울해요",
    "timeOfDay": "밤이에요"
  }
