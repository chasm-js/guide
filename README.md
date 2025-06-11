# Chasm - 캐즘

> **chasm** [ˈkæzəm]  
> *noun* | *명사*  
> 
> (지질) 땅이나 암석, 표면 등에 생긴 깊고 큰 틈  
> *"A chasm opened in the ground after the earthquake."*  
> *(지진 후 땅에 커다란 틈이 생겼다.)*

## 소개

Chasm (캐즘) 은 Crack 사용자 경험을 확장하는 프로젝트입니다.

개발이 중단된 [**FastWrtn**](https://github.com/sickwrtn/FastWrtn) 및 [**FastCrack**](https://github.com/sickwrtn/FastCrack)의 정신을 계승하며, 더 발전된 유저스크립트 포맷과 폭넓은 브라우저 지원을 목표로 하고 있습니다.

Chasm.js 통합 버전이 출시되기 전까지 필요한 기능만 골라 설치할 수 있는 **Chasm Snack** 형태로 제공합니다.

## 설치법 가이드 링크

### PC (Tampermonkey)
* [뤼튼 여성향 갤러리 - 캐즘 설치 어케해??](https://gall.dcinside.com/mini/board/view/?id=wrtnw&no=46410)
   * [아카이브](https://archive.is/z0RfS), [웨이백 머신 아카이브](https://web.archive.org/web/20250502053036/https://gall.dcinside.com/mini/board/view/?id=wrtnw&no=46410)

### iOS (Safari + Stay)
* [뤼튼 여성향 갤러리 - 뒷북이지만 컴맹들을 위한 아이폰 확프 정리](https://gall.dcinside.com/mini/board/view/?id=wrtnw&no=45332)
   * [아카이브](https://archive.is/nDoVb), [웨이백 머신 아카이브](https://web.archive.org/web/20250502054552/https://gall.dcinside.com/mini/board/view/?id=wrtnw&no=45332)

### Android (Firefox + Tampermonkey)
* [뤼튼 여성향 갤러리 - 안드에서 파폭으로 유저스크립트 쓰기 AtoZ 가이드](https://gall.dcinside.com/mini/board/view/?id=wrtnw&no=44839)
   * [아카이브](https://archive.is/ip5RI), [웨이백 머신 아카이브](https://web.archive.org/web/20250502053148/https://gall.dcinside.com/mini/board/view/?id=wrtnw&no=44839)

---

## Chasm Snack (미니 스크립트)

### 캐즘 버너+ (Chasm burner+) v1.3.2 beta

애프터버너 기능의 개선판입니다. 대화 내역을 Gemini 또는 OpenRouter를 사용해 요약하며, 채팅방으로 전송합니다.

사용법: [[뤼튼 여성향 갤러리 - 캐즘 어케써??? ㅠㅠ]](https://gall.dcinside.com/mini/board/view/?id=wrtnw&no=47950) [[아카이브]](https://archive.is/VXqhQ) [[웨이백 머신 아카이브]](https://web.archive.org/web/20250503211128/https://gall.dcinside.com/mini/board/view/?id=wrtnw&no=47950)

> 기존 애프터버너에서의 개선점:
> * 전체 코드 리팩토링, setTimeout 과도 남용 및 부적절한 코드 제거
> * 메세지 수정을 통한 전송을 6000자로 리밋 변경
> * 메세지 전송 전 확인 및 수정기능
> * 여러번 요약 후 원하는 요약본 전송
> * API 발급 페이지 연결 추가
> * 유저노트 요약 전송 추가 (v1.1-beta)
> * 프로필 수정 기능 추가 (v.1.2-beta)
> * ... 추후 커뮤니티 프롬프트 구독, 내 커스텀 프롬프트 저장 등 기능 추가 예정

[![Install Chasm burner+](https://img.shields.io/badge/🚀%20Install-Chasm_Burner-blue?style=for-the-badge)](https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/burner.user.js)

**직접 설치 링크 복사:**

``` 
https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/burner.user.js
```

---

### 캐즘 카피 (Chasm Copy) v1.2.2

생성한 캐릭터를 새 캐릭터로 복제하거나, JSON 데이터 복사/붙여넣기 기능을 추가하는 스크립트입니다.

[![Install Chasm Copy](https://img.shields.io/badge/🚀%20Install-Chasm_Copy-blue?style=for-the-badge)](https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/copy.user.js)

**직접 설치 링크 복사:**

``` 
https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/copy.user.js
```

---

### 빨간약 (Redpill) v1.4

전체 슈퍼챗 사용 내역을 크롤링해, 캐릭터별·월별 분석을 지원하는 유저스크립트입니다.

[![Install Redpill](https://img.shields.io/badge/🚀%20Install-Redpill-blue?style=for-the-badge)](https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/redpill.user.js)

**직접 설치 링크 복사:**

``` 
https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/redpill.user.js
``` 

---

### 캐즘 타이디 (Chasm tidy) v1.2

크랙 메인 페이지에서 팔로잉, 좋아요 목록 제외 전체 캐릭터 섹션을 숨기는 스크립트

[![Install tidy](https://img.shields.io/badge/🚀%20Install-Tidy-blue?style=for-the-badge)](https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/tidy.user.js)

**직접 설치 링크 복사:**

``` 
https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/tidy.user.js
``` 

---

### 캐즘 스타일 (Chasm style) v1.0

* iOS 웹 기반 입력창 터치시 확대되던 오류 수정
* 특정 기기/브라우저(안드로이드+파이어폭스 등)에 코드블록 내용이 serif 체로 나오던 문제 강제 해결

[![Install style](https://img.shields.io/badge/🚀%20Install-Style-blue?style=for-the-badge)](https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/style.user.js)

**직접 설치 링크 복사:**

``` 
https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/style.user.js
``` 
---

## 설치 가이드

크롬 확장 프로그램의 보안 정책으로 인해 `.user.js` 링크 클릭 시 다운로드나 설치가 정상적으로 되지 않을 수 있습니다.  
이 경우 링크를 **직접 복사하여 설치**하거나, **다운로드 후 수동 설치**해야 합니다.

### 유저스크립트 매니저 설치

1. [Tampermonkey (Chrome, Edge)](https://www.tampermonkey.net/)  
2. [Violentmonkey (Chrome, Firefox, Edge)](https://violentmonkey.github.io/)
3. [Stay (iOS)](https://apps.apple.com/kr/app/stay-for-safari/id1591620171)

이후, 위의 스크립트 링크를 이용하여 설치하세요.

---

## FAQ

**Q. 스크립트를 설치할 때 권한 요청(외부 사이트 접근 등)이 나옵니다. 허용해야 하나요?**  
A. **네.** 스크립트가 정상 작동하려면 필요한 권한을 허용해야 합니다.

**Q. 크롬에서는 설치가 잘 안 됩니다. 어떻게 해야 하나요?**  
A. 크롬에서 [개발자 모드](chrome://extensions/)를 켜고 설치를 시도하세요.

**Q. 그래도 문제가 발생하면?**  
A. 파이어폭스(또는 파이어폭스 계열 브라우저) 사용을 권장합니다.  
   파이어폭스에서는 유저스크립트 매니저와의 호환성이 더 좋습니다.

