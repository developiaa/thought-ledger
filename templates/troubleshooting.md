# [TS] 이슈 제목 (예: 응답 지연 및 Connection Pool 고갈)
> **발생 일시:** 2026-04-27 14:00
> **영역:** #Backend #MySQL #Performance

### 🚨 현상 (Symptom)
*사용자가 느낀 불편함이나 모니터링 툴(Grafana 등)에서 발견된 수치*
- 
-

### 🔍 분석 및 가설 (Analysis & Hypothesis)
*로그 분석, 덤프 확인 등을 통해 세운 가설들*
- **현상 파악:** (에러 로그 또는 스레드 덤프 내용 요약)
- **가설 1:** - **가설 2:** ### 🧪 검증 과정 (Verification)
  *각 가설을 어떻게 확인했는지 기록*
- [x] 가설 1 검증: (결과: 관련 없음)
- [ ] 가설 2 검증: (결과: 원인 확인)

### ✅ 해결 (Resolution)
*최종 조치 사항과 코드 변경점*
- **조치:** - **코드/설정:**
```yaml
# 수정된 설정 예시
spring:
  datasource:
    hikari:
      maximum-pool-size: 20
