# niceplus_findmyclass
나이스플러스 회원가입 정보 대입 매크로 (내 반 찾기)

## 원리
* 나이스플러스 회원가입에서는 학급 정보/내 정보가 일치해야 다음 단계로 넘어갑니다.
* 이때 학급 정보 중 번호를 대입하고 확인 버튼을 누른 뒤 경고창이 뜨는걸 끄고 다시 입력하는 것을 자동화한 매크로입니다.
* 즉, 만약 내 반이 맞을 경우 다음 단계로 넘어가며 내 반이 아닐 경우 경고창이 뜹니다.

## 사용 방법
1. <a href="https://www.keyboardmaestro.com/main/">Keyboard Maestro</a>를 다운받아 설치합니다. (macOS 전용)
2. 위 파일을 다운받아 Import합니다.
3. 마우스의 좌표는 M2 Macbook Air (13인치)에 맞춰져 있습니다. 오차가 있는 경우 좌표를 수정합니다.
4. <a href="https://edupass.neisplus.kr/SCSP_CLOUD/login.do">나이스플러스 회원가입 페이지</a>에서 기본 정보를 입력해두고, 번호 입력 부분을 비웁니다.
5. Keyboard Maestro에서 매크로를 살행합니다.

## 유의점
* 과도한 실행 시 나이스에서 이를 비정상적인 사용 환경이라 간주하고 일시적인 차단을 당할 수 있습니다.
* 번호 부분을 대입해주기 때문에 반은 수동으로 바꾸어주어야합니다.
* 1번부터 27번까지 자동으로 대입해주며 이 후 번호는 직접 추가하시면 됩니다.
