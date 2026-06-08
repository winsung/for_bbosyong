# 📱 모바일에서 뽀숑이 기록·문의하기

집 밖에서도 휴대폰으로 뽀숑이를 기록하고 물어보는 방법입니다.

## 1. 가족용 안내 페이지 (보기 전용) — 아내·아이들용
누구나 링크만 열면 뽀숑이 현재 상태를 볼 수 있어요.

🔗 **https://winsung.github.io/for_bbosyong/**

- 몸무게, 다음 접종 D-day, 사료, 주의사항, 훈련 단계를 한 화면에서 확인
- 휴대폰 홈 화면에 추가해두면 앱처럼 바로 열 수 있어요
  - iPhone(Safari): 공유 → "홈 화면에 추가"
  - Android(Chrome): ⋮ → "홈 화면에 추가"

> ※ 이 페이지가 보이려면 GitHub 저장소에서 Pages를 한 번 켜야 합니다 (아래 "최초 설정" 참고).

## 2. 기록하고 문의하기 (입력) — 관리자(아빠)용
휴대폰 브라우저에서 **claude.ai/code** 에 로그인 → `winsung/for_bbosyong` 저장소를
연결하면, 채팅으로 기록·문의할 수 있습니다.

예시로 이렇게 말하면 됩니다:
- "오늘 뽀숑이 산책 잘했고 변 상태 좋았어" → 그날 일지에 자동 기록
- "몸무게 1.9kg으로 바뀌었어" → 몸무게 추이 + 안내 페이지(data.json) 갱신
- "이번 주 배변훈련 어떻게 할까?" → 현재 월령 기준 추천
- 변경 후 자동으로 `main`에 push → 가족 페이지도 최신으로 반영

## 최초 설정 (한 번만)
### GitHub Pages 켜기 (가족 페이지 배포)
1. https://github.com/winsung/for_bbosyong/settings/pages 접속
2. **Build and deployment → Source**: "Deploy from a branch"
3. **Branch**: `main` 선택, 폴더는 **/docs** 선택 → **Save**
4. 1~2분 뒤 위 링크에서 페이지 확인

---
업데이트하면 항상 `git push` 되어 페이지와 모바일에서 최신 내용이 보입니다.
