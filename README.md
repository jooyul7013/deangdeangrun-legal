# deangdeangrun-legal

드로잉런(deangdeangrun) Android 앱의 공개 법무 문서 호스팅 레포.

본 레포의 마크다운은 GitHub Pages 로 자동 빌드되어 다음 URL 에서 접근 가능합니다.

- 개인정보처리방침: <https://jooyul7013.github.io/deangdeangrun-legal/privacy/>

## 정책 본문 SSoT 와 동기화 절차

정책 본문의 단일 진실 공급원(SSoT) 은 메인 앱 레포 `deangdeangrun/docs/launch/privacy-policy.ko.md` 입니다. 본 레포의 `privacy/index.md` 는 수동으로 동기화된 복사본입니다.

### 정책 개정 절차

1. 메인 레포 `launch/<topic>` 브랜치에서 `docs/launch/privacy-policy.ko.md` 수정
2. 정책서 §시행일자·최종 개정일·직전 개정일자 갱신
3. PR 머지
4. 본 레포 로컬 클론에서 `privacy/index.md` 의 frontmatter 아래 본문을 메인 레포의 새 내용으로 교체
5. 본 레포 커밋·푸시 → GitHub Pages 자동 재빌드 (1~2 분 소요)
6. URL 새로고침으로 변경 반영 확인

## 라이센스

본 레포의 법무 문서는 드로잉런 앱의 운영 정보를 담고 있으며, 무단 재사용을 금지합니다.
