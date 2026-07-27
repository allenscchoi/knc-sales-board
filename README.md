# KNC 영업 전광판

SharePoint 데이터를 **열람자 본인 계정으로** 직접 읽어 보여주는 정적 대시보드.

- 로그인: Microsoft Entra ID (KNC 테넌트 전용)
- 데이터: Microsoft Graph → SharePoint 리스트 (위임 권한)
- **이 저장소에는 영업 데이터가 없습니다.** 화면 코드만 있습니다.

권한이 없는 사람은 로그인 화면까지만 보이고, 로그인해도 본인이 SharePoint에서
접근 가능한 범위만 표시됩니다.

## 파일
- `index.html` — 대시보드 (빌드 산출물)
- `msal-browser.min.js` — Microsoft 인증 라이브러리 (v3.30.0)

빌드는 사내 `Casting PO Data_New/Sales Dashboard/live/build_live.py` 에서 수행합니다.
