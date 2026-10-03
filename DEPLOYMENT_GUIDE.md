# GitHub Pages 배포 가이드

## 📋 준비사항 확인

- [ ] GitHub 계정 (없으면 [github.com](https://github.com)에서 가입)
- [ ] `index.html` 파일 준비됨
- [ ] 웹 브라우저 (Chrome, Firefox, Safari, Edge 등)

---

## ✅ 단계별 배포 방법

### **1단계: GitHub 저장소 생성 (5분)**

1. [GitHub](https://github.com)에 로그인합니다.

2. 우측 상단 **더하기(+) 버튼** → **New repository** 클릭

   ![Step 1](https://user-images.githubusercontent.com/1/step1.png)

3. 다음과 같이 입력합니다:
   - **Repository name**: `incheon-visual-novel`
   - **Description**: `지속가능한 인천 만들기 - 인천산곡초등학교`
   - **Public** 선택 (중요!)
   - **README file 추가** 체크 (선택사항)

4. **Create repository** 클릭

---

### **2단계: 파일 업로드 (3분)**

1. 생성된 저장소 페이지에서 **Add file** 버튼 클릭

2. **Upload files** 선택

3. 파일 업로드 방식:
   
   **방법 A: 드래그앤드롭**
   - `index.html` 파일을 드래그하여 업로드 영역에 놓기
   
   **방법 B: 클릭 선택**
   - "choose your files" 클릭 → `index.html` 선택

4. **Commit changes** 클릭
   - 커밋 메시지는 기본값으로 두어도 괜찮습니다.

---

### **3단계: GitHub Pages 활성화 (2분)**

1. 저장소 페이지 상단의 **Settings** 탭 클릭

2. 왼쪽 메뉴에서 **Pages** 선택

   ![GitHub Pages Settings](https://user-images.githubusercontent.com/1/pages-settings.png)

3. **Build and deployment** 섹션에서:
   - **Source**: "Deploy from a branch" 선택
   - **Branch**: "main" 선택
   - **Folder**: "/(root)" 선택

4. **Save** 클릭

5. 잠시 후 페이지 상단에 다음 메시지 확인:
   ```
   Your site is live at https://[username].github.io/incheon-visual-novel/
   ```

---

### **4단계: 게임 접속 (1분)**

1. 위 메시지의 링크 클릭 또는 다음 주소로 접속:
   ```
   https://[username].github.io/incheon-visual-novel/
   ```

2. 게임이 정상적으로 로드되는지 확인합니다.

3. 완료! 🎉

---

## 🔗 URL 구조 이해

만약 GitHub 사용자명이 `park-teacher`이고 저장소 이름이 `incheon-visual-novel`이라면:

```
https://park-teacher.github.io/incheon-visual-novel/
```

- `park-teacher`: GitHub 사용자명
- `incheon-visual-novel`: 저장소 이름

---

## 📝 파일 수정 후 배포

게임 내용을 수정하려면:

1. GitHub에서 `index.html` 파일 클릭

2. 연필 아이콘 (Edit this file) 클릭

3. 내용 수정

4. 아래의 "Commit changes" 클릭

5. 잠시 후 변경사항이 웹사이트에 반영됩니다 (최대 1분)

---

## 🎨 선택사항: 더 전문적인 배포

### GitHub Desktop 사용 (권장)

복잡한 수정이 많으면 GitHub Desktop을 사용하면 더 편합니다:

1. [GitHub Desktop](https://desktop.github.com) 다운로드 및 설치

2. 로그인

3. **File** → **Clone repository** 클릭

4. `incheon-visual-novel` 저장소 선택 및 클론

5. 로컬에서 파일 수정

6. GitHub Desktop에서 변경사항 커밋 및 푸시

---

## 🆘 문제 해결

### Q: "Your site is published..." 메시지가 나타나지 않습니다.

**A**: 
- 저장소가 **Public**으로 설정되어 있는지 확인
- 5~10분 기다렸다가 다시 새로고침
- Settings > Pages 다시 확인

### Q: 게임 페이지가 로드되지 않습니다.

**A**:
- 파일이 `index.html`로 정확히 이름 지어졌는지 확인
- 저장소의 메인 디렉토리에 있는지 확인
- 브라우저 개발자 도구 (F12) 확인
- 캐시 삭제 후 다시 로드 (Ctrl+Shift+Delete)

### Q: 게임은 로드되지만 빈 화면입니다.

**A**:
- 브라우저 콘솔에 오류가 있는지 확인 (F12)
- index.html 파일이 완전하게 업로드되었는지 확인
- 다른 브라우저 시도

### Q: 변경사항이 반영되지 않습니다.

**A**:
- 캐시 삭제 (Ctrl+Shift+Delete)
- 전체 새로고침 (Ctrl+F5)
- 5분 정도 기다린 후 다시 시도

---

## 📚 추가 자료

- [GitHub Pages 공식 문서](https://pages.github.com)
- [GitHub 시작 가이드](https://docs.github.com/ko)

---

**배포 완료 후 다음을 시도해보세요:**
- 친구들과 게임 URL 공유
- 학급에서 함께 플레이
- 다양한 브라우저와 기기에서 테스트
- 플레이 피드백 수집
