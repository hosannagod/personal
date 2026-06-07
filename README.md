# LUMI:TINT Seoul AI 광고 영상 프로젝트

## 1. 브랜드 아이덴티티

- 브랜드명: LUMI:TINT Seoul
- 제품명: LUMI:TINT Velvet Neon Fixing Tint
- 타겟: 10~20대, K-POP 스타일과 트렌디한 스트릿 무드를 선호하는 소비자
- 톤앤매너: 차분한 K-POP 아이돌 포트레이트, 서울 네온 밤거리, 펑키 그래피티, 시네마틱 K-beauty 광고
- USP: 자연스러운 노메이크업 무드에서도 입술 컬러만 선명하게 살아나는 벨벳 틴트 이미지
- 핵심 메시지: “서울의 밤, 입술 끝에서 켜지다.”
- CTA: “Turn on your Seoul lips.”

## 2. 스토리보드 요약

| 씬 | 길이 | 목표 메시지 | 주요 화면 | 카피 |
|---|---:|---|---|---|
| Scene 01. Intro | 6초 | 서울 네온 밤거리와 브랜드 세계관 각인 | 젖은 도로, 네온 반사, 인물 실루엣 | 서울의 밤은, 조용히 빛난다. |
| Scene 02. Idol Close-up | 7초 | 차분하고 세련된 K-POP 아이돌 무드 표현 | 인물 클로즈업, 노메이크업 스타일, 네온 보케 | 과하지 않게, 더 선명하게. |
| Scene 03. Product Reveal | 7초 | 틴트 제품 첫 등장 | 글로시 테이블 위 틴트 제품 | 빛을 머금은 컬러, LUMI:TINT. |
| Scene 04. Lip Moment | 8초 | 입술 컬러 포인트 강조 | 로즈 베리 컬러 립 클로즈업 | 서울의 밤, 입술 끝에서 켜지다. |
| Scene 05. Hero Shot | 8초 | 인물, 서울, 제품의 결합 | 모델과 틴트 제품, 네온 서울 배경 | Calm face. Neon lips. |
| Scene 06. End Card | 6초 | 브랜드명과 CTA 각인 | 제품 단독 컷, 네온 그라데이션 | LUMI:TINT. Turn on your Seoul lips. |

## 3. 씬 1 예시 상세

### 씬 1. Intro

- 씬 길이: 6초
- 목표 메시지: 서울 네온 밤거리와 브랜드 세계관을 첫 컷에서 각인한다.
- 화면 구성: 네온사인이 반사되는 서울 밤거리, 젖은 도로, 펑키한 그래피티, 흐릿한 도시 불빛, 인물 실루엣
- 내레이션 또는 카피: “서울의 밤은, 조용히 빛난다.”
- 사용 도구 및 목적:
  - 이미지 생성: 씬별 키 비주얼 생성
  - 비디오 변환: 정지 이미지를 짧은 모션 컷으로 변환
  - 오디오 생성: K-POP 신스팝 기반 배경음악 제작
  - 편집 도구: FFmpeg를 활용해 컷 편집, 자막, 오디오 결합
- 입력 프롬프트 예시: `cinematic neon Seoul night street, wet asphalt reflections, vibrant retro signage, dynamic graffiti wall, soft bokeh city lights, calm K-pop editorial mood, no text, 16:9, photorealistic`
- 출력 결과 요약: 네온 서울 밤거리와 차분한 광고 무드가 결합된 인트로 키 비주얼 확보
- 결과 파일명: `scene01_intro.png`

## 4. 프롬프트 수정 전/후 기록

### Scene 02 프롬프트 개선 로그

- 수정 전 의도: K-POP 아이돌 포트레이트와 서울 펑키 밤거리의 대비를 표현한다.
- 문제: 배경의 네온과 그래피티가 너무 강하면 인물 집중도가 낮아지고, 실제 아이돌을 연상시킬 위험이 있다.
- 수정 후 변경: `fictional K-pop idol`, `natural detailed no-makeup style makeup`, `elegant minimalistic outfit`, `soft bokeh background`, `no real celebrity`, `no text` 조건을 추가했다.
- 결과 변화: 인물의 차분함과 고급스러움이 유지되고, 배경은 펑키하지만 주 피사체를 방해하지 않는 형태로 개선되었다.

## 5. 최종 영상 파일 정보

| 파일명 | 길이 | 해상도 | 화면 비율 | FPS | 코덱 | 용도 |
|---|---:|---:|---:|---:|---|---|
| `LUMITINT_Seoul_Neon_Ad.mp4` | 42초 | 1920x1080 | 16:9 | 30fps | H.264 / AAC | 기본 본편 |
| `LUMITINT_Seoul_Neon_Ad_Lipsync_16x9.mp4` | 48초 | 1920x1080 | 16:9 | 30fps | H.264 / AAC | 립싱크 포함 가로형 본편 |
| `LUMITINT_Seoul_Neon_Ad_Lipsync_9x16.mp4` | 48초 | 1080x1920 | 9:16 | 30fps | H.264 / AAC | 쇼츠/릴스용 |
| `LUMITINT_Seoul_Neon_Ad_Lipsync_1x1.mp4` | 48초 | 1080x1080 | 1:1 | 30fps | H.264 / AAC | SNS 피드용 |
| `bonus_lipsync_scene.mp4` | 6초 | 1280x720 | 16:9 | 24fps | H.264 / AAC | 립싱크 단독 증빙 클립 |

## 6. 보너스 반영 내용

- 보너스 1 립싱크 적용: 모델이 “서울의 밤, 입술 끝에서 켜져요. 루미틴트.”라고 말하는 장면을 추가했다.
- 보너스 2 동일 스토리보드 재제작: 기존 Scene 05 Hero Shot을 모델 발화가 포함된 영상 생성 컷으로 재제작했다.
- 보너스 3 플랫폼별 화면 비율 제작: 16:9, 9:16, 1:1 버전을 각각 제작했다.

## 7. 제출 파일

- `storyboard.pdf`: 브랜드 아이덴티티와 전체 스토리보드 문서
- `storyboard.md`: Markdown 원본 문서
- `LUMITINT_Seoul_Neon_Ad.mp4`: 기본 42초 본편
- `bonus/`: 립싱크 및 플랫폼별 비율 보너스 영상
- `assets/`: 씬별 이미지와 배경음악 소스
