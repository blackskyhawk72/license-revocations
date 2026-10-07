# license-revocations

JavaSpecAI 등 여러 프로그램이 공유하는 라이선스 폐기 목록. `revoked.json`에
폐기된 키 id(`kid`) 배열만 들어있다 — 고객사명 등 민감 정보는 절대 포함하지
않는다(그래서 이 저장소는 public이어도 안전하다).

license-tools 발급 GUI의 "폐기" 버튼이 이 파일을 갱신한다. 직접 편집은
하지 않는 걸 권장 — 발급 이력(license-tools의 issued_licenses.json)과
싱크가 안 맞을 수 있다.
