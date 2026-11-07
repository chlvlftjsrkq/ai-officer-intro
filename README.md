# AI-officer 소개 페이지

**기본 운영은 전화기 → 호환 수화기 녹음용 분기 어댑터 → PC Line-in 연결입니다.** 음성을 자막으로 바꾸고, 이어지는 AI 분석·전화 메모·후속 업무로 연결합니다.

## 기본 소개

**[Line-in 기본 소개 열기](https://chlvlftjsrkq.github.io/ai-officer-intro/)**

- 전화기와 직원 PC의 연결 · 입력 장치 선택 · 음량 확인
- 통화 시작 또는 소리 기준 자동 감지
- 자막 타이핑 → AI 분석 단계 → 메모 작성
- 장면별 진행 막대·다시 보기·재생 및 정지

## 추가 소개 · 기존 녹취서버 연동

직접 Line-in 연결이 어렵고 해당 교환기의 녹취서버가 이미 운영 중이며 음성·번호 로그 연동을 확인한 환경에서 사용하는 선택 구성입니다.

**[녹취서버 선택 구성 소개](https://chlvlftjsrkq.github.io/ai-officer-intro/ai-officer-server-intro.html)** · [연결·설치 문서](https://gitlab.aigov.go.kr/pilddong/AI-officer/-/blob/main/docs/OPTIONAL_RECORDING_SERVER.md)

[프로젝트 원본·기본 설치 안내](https://gitlab.aigov.go.kr/pilddong/AI-officer)

공개 소개 전용 저장소입니다. 실제 통화·기관 API 인증정보·민원인 기록을 포함하지 않습니다. 소개 화면은 시연 예시이며 실제 서비스는 기관 내부망의 PC 앱과 GOV API를 이용합니다.

## 갱신

원본 프로젝트에서 `tools/build_intro.py`를 실행합니다. 생성된 기본 소개를 `index.html`과 `ai-officer-intro.html`로, 선택 구성 소개를 `ai-officer-server-intro.html`로 복사합니다. `.nojekyll`을 유지하고 `main` 루트 폴더를 GitHub Pages로 게시합니다. 각 소개는 단일 HTML이며 오프라인에서 서로 이동하려면 두 소개를 같은 폴더에 둡니다.

구성 참고: [기후노트 소개](https://gonynim22.github.io/climate-note/climate-note-intro/climate-note-intro.html). 문구·장면·아이콘·코드는 AI-officer에 맞게 새로 구성했습니다.
