# GitHub & Lambda & Slack연동

## 📋 기능
Lambda : Commit 발생 시 자동으로 `text.txt` 파일을 생성
      Slack (메시지 처리)

## 연동 방법
1. **GitHub에서 WebHook 활성화**
   - Repository Settings → Webhooks
   - Payload URL 설정
2. **AWS Lambda에서 관련 함수 작성**
   - Push event 처리
   - 파일 생성 로직 구현
3. **Slack**
   - WebHook설정 
