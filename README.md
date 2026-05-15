# Veluga Shipping Map

Google Sheets / Apps Script에서 만든 출고지도 데이터를 고정 도메인에서 보여주는 정적 웹페이지입니다.

## 필요한 URL 파라미터

- appkey: Kakao JavaScript Key
- dataUrl: Apps Script 웹앱 URL. token 파라미터를 포함해야 합니다.

예:
https://YOUR-VERCEL-DOMAIN.vercel.app?appkey=KAKAO_JS_KEY&dataUrl=ENCODED_APPS_SCRIPT_WEB_APP_URL
