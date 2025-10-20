## 🚀 Monew PR Template

### 🔗 Related Issue
- closes # (이슈번호,,)
  > 예시: closes #12  
  > ※ `closes` 키워드는 PR merge 시 해당 이슈를 자동으로 닫습니다.

---

### 🧩 Summary
이 PR에서 구현한 기능을 간략히 설명

> 예시:  
> - 사용자 프로필 수정 기능 추가  
> - 게시글 좋아요 기능 구현  
> - 로그인 API JWT 인증 로직 개선  

---

### 💡 Implementation Details
어떤 방식으로 구현했는지, 주요 변경 파일이나 로직을 설명

> 예시:
> - `UserController.java` : 프로필 수정 엔드포인트 추가  
> - `UserService.java` : 유효성 검증 로직 추가  
> - `user-profile-edit.html` : 프론트엔드 수정 반영  

---

### ✅ Checklist
- [ ] 관련된 Issue 번호를 `closes #번호` 형태로 연결했다.
- [ ] 로컬 환경에서 정상적으로 동작을 확인했다.
- [ ] 코드 리뷰 가이드를 준수했다.
- [ ] 테스트 코드 또는 로깅을 추가했다 (필요 시).
- [ ] 문서/주석을 업데이트했다.

---

### 🧪 Test Results (선택)
테스트 방법 또는 결과를 간단히 적어주세요.  
> 예:  
> - `/api/users/edit` 엔드포인트 호출 시 정상 응답(200 OK) 확인  
> - 프로필 이미지 변경 기능 E2E 테스트 통과  

---

### 🗒️ 기타 참고 사항 (Optional)
리뷰어에게 추가로 전달하고 싶은 내용이나 주의 사항이 있다면 적어주세요.
> 예:  
> - API 스펙 변경됨 → 프론트엔드 팀 공유 필요  
> - 배포 전 환경 변수 설정 필요
