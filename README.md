# 우리 아이 발달정도 테스트 (비공식)

WHO가 공개한 GSED(Global Scales for Early Development) v1.0 간소화 버전(Short Form, 보호자 응답용)과
D-score 계산 방식을 참고해 만든 **비공식** 한국어 설문입니다. 월령에 맞는 문항부터 답하면
또래 100명 중 우리 아이가 어디쯤인지 보여 줍니다. 응답은 저장되지 않고 어디로도 전송되지 않습니다
(모든 계산이 브라우저 안에서 이뤄집니다).

- 사이트: https://ybybgo.github.io/baby-development-check/
- 진단이나 선별 도구가 아닙니다. 발달이 걱정되면 영유아 건강검진과 전문의 상담을 이용하세요.

## 출처와 라이선스

- 문항과 예시 그림: © World Health Organization 2023, *Global Scales for Early Development v1.0 Short Form*.
  [CC BY-NC-SA 3.0 IGO](https://creativecommons.org/licenses/by-nc-sa/3.0/igo/) 라이선스에 따라 출처를 밝히고,
  한국어 번역·가공본임을 알리며, 같은 조건으로 공유합니다. **비영리 목적으로만** 사용할 수 있습니다.
- 이 번역본은 WHO가 만든 것이 아닙니다. WHO는 번역의 내용이나 정확성에 책임이 없으며 영어 원본이 정본입니다.
  WHO의 이름이나 로고가 이 페이지를 보증한다는 뜻이 아닙니다.
- 점수 계산(문항 난이도, 기준 곡선, 알고리즘): R 패키지 [dscore](https://github.com/D-score/dscore) 2.0.0 / 2.1.0 (Apache License 2.0, Stef van Buuren 외).
  일러스트와 코드는 이 저장소 작성자가 만들었습니다.
- 원문:
  [GSED v1.0 Short Form](https://iris.who.int/server/api/core/bitstreams/39849da3-bfeb-4d66-bb8f-26c18d3bcdfe/content),
  [GSED v1.0 Scoring guide](https://iris.who.int/server/api/core/bitstreams/fbf4ad43-b299-4b41-806e-fe48b731501f/content)

---

An unofficial Korean adaptation of the WHO GSED v1.0 Short Form with D-score calculation ported from the `dscore` R package.
Not created or endorsed by WHO. Original material © WHO 2023, CC BY-NC-SA 3.0 IGO (non-commercial). Adaptation: Korean translation and software port.
