# Chasm - 캐즘

**Chasm**은 AI 채팅 서비스 **Crack**을 위한 유저스크립트 확장 프로젝트입니다.

Crack이 여는 새로운 세상의 틈을, Chasm으로 더욱 넓게 확장해보세요.

> **chasm** [ˈkæzəm]  
> *noun* | *명사*  
> 
> 1. (지질) 땅이나 암석, 표면 등에 생긴 깊고 큰 틈  
>    *"A chasm opened in the ground after the earthquake."*  
>    *(지진 후 땅에 커다란 틈이 생겼다.)*

---

## 소개

Chasm은 Crack 사용자 경험을 확장하는 프로젝트입니다.  
개발이 중단된 [**FastWrtn**](https://github.com/sickwrtn/FastWrtn) 및 [**FastCrack**](https://github.com/sickwrtn/FastCrack)의 정신을 계승하며,  
더 발전된 유저스크립트 포맷과 폭넓은 브라우저 지원을 목표로 하고 있습니다.

Chasm.js 통합 버전이 출시되기 전까지는,  
필요한 기능만 골라 설치할 수 있는 **Chasm Snack** 형태로 제공합니다.

---

## Chasm Snack (미니 스크립트)

### 빨간약 (Redpill)

전체 슈퍼챗 사용 내역을 크롤링해, 캐릭터별·월별 분석을 지원하는 유저스크립트입니다.

[![Install Redpill](https://img.shields.io/badge/🚀%20Install-Redpill-blue?style=for-the-badge)](https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/redpill.user.js)

**직접 설치 링크 복사:**

``` 
https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/redpill.user.js
``` 

---

### 캐즘 카피 (Chasm Copy)

생성한 캐릭터를 새 캐릭터로 복제하거나, JSON 데이터 복사/붙여넣기 기능을 추가하는 스크립트입니다.

[![Install Chasm Copy](https://img.shields.io/badge/🚀%20Install-Chasm_Copy-blue?style=for-the-badge)](https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/copy.user.js)

**직접 설치 링크 복사:**

``` 
https://raw.githubusercontent.com/chasm-js/snack/refs/heads/main/copy.user.js
``` 

---

## 설치 가이드

크롬 확장 프로그램의 보안 정책으로 인해 `.user.js` 링크 클릭 시 다운로드나 설치가 정상적으로 되지 않을 수 있습니다.  
이 경우 링크를 **직접 복사하여 설치**하거나, **다운로드 후 수동 설치**해야 합니다.

### 유저스크립트 매니저 설치

1. [Tampermonkey (Chrome, Edge)](https://www.tampermonkey.net/)  
2. [Violentmonkey (Chrome, Firefox, Edge)](https://violentmonkey.github.io/)
3. [Stay (iOS)](https://apps.apple.com/kr/app/stay-for-safari/id1591620171)

둘 중 하나를 설치한 후, 위의 스크립트 링크를 이용하여 설치하세요.

---

## FAQ

**Q. 스크립트를 설치할 때 권한 요청(외부 사이트 접근 등)이 나옵니다. 허용해야 하나요?**  
A. **네.** 스크립트가 정상 작동하려면 필요한 권한을 허용해야 합니다.

**Q. 크롬에서는 설치가 잘 안 됩니다. 어떻게 해야 하나요?**  
A. 크롬에서 [개발자 모드](chrome://extensions/)를 켜고 설치를 시도하세요.

**Q. 그래도 문제가 발생하면?**  
A. 파이어폭스(또는 파이어폭스 계열 브라우저) 사용을 권장합니다.  
   파이어폭스에서는 유저스크립트 매니저와의 호환성이 더 좋습니다.

---
