# FSR 상품·상담 노트

개인 참고용 상품 요약 27종과 상담 설계 도구를 하나로 묶은 웹앱입니다. 비공식 자료입니다.
내용은 AES-256으로 암호화되어 있어 비밀번호 없이는 읽을 수 없습니다.

## GitHub에 올리기 (처음 한 번)

1. github.com에 로그인 → 오른쪽 위 **+** → **New repository**
   - Repository name: 예) `fsr-note` (회사명·상품명은 넣지 않는 것을 권장)
   - **Public** 선택 → **Create repository**
2. 새 저장소 화면에서 **uploading an existing file** 클릭
3. 압축을 푼 폴더 안의 파일을 모두 끌어다 놓기
   - `index.html`, `manifest.webmanifest`, `sw.js`, `robots.txt`, `README.md`, `icons` 폴더(아이콘 4개)
   - `.nojekyll`은 숨김 파일이라 안 보여도 괜찮습니다
4. 아래 **Commit changes** 클릭
5. 저장소 **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)** → **Save**
6. 1~2분 뒤 같은 화면 위쪽에 주소가 나옵니다: `https://<아이디>.github.io/fsr-note/`

## 비밀번호 바꾸기 (필요할 때)

1. 앱을 열고 오른쪽 위 **설정(톱니바퀴) → 비밀번호 변경**에 새 비밀번호를 두 번 넣고 **새 index.html 만들기**를 누릅니다.
2. 다운로드 폴더에 저장된 `index.html`을 저장소에 다시 올립니다: **Add file → Upload files** → 파일 끌어다 놓기 → **Commit changes** (같은 이름이면 덮어씁니다)
3. 1~2분 뒤부터 새 비밀번호만 통합니다. 이전 비밀번호와 "이 기기 기억"은 무효가 됩니다.

## 휴대폰에 앱으로 설치

- **iPhone**: Safari로 주소 열기 → 공유 버튼 → **홈 화면에 추가**
- **Android**: Chrome으로 주소 열기 → ⋮ 메뉴 → **앱 설치** (또는 화면 위 "앱 설치" 버튼)
- **PC (Chrome·Edge)**: 주소창 오른쪽 설치 아이콘 또는 화면 위 "앱 설치" 버튼

한 번 연 뒤에는 인터넷이 없어도 열립니다.

## 내용 업데이트

상품이 추가·개정되면 새 `index.html`만 다시 올리면 됩니다(다른 파일은 그대로). 새 파일은 빌드 스크립트(`_FSR추천엔진\hub\build_hub.py`)로 만듭니다.
