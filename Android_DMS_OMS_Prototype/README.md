프로젝트명: Android DMS/OMS Prototype

핵심 기능:
1. CameraX 실시간 카메라
2. ML Kit Face Detection
3. 얼굴 Bounding Box
4. Eye Probability
5. PERCLOS 졸음 감지
6. Head Pose 부주의 감지
7. Yawning Detection
8. Attention Score
9. Driver/Passenger OMS
10. Seat Occupancy UI
11. 경고 UI
12. 진동/경고음
13. YOLOv8n TFLite Phone Usage Detection

- 코드 구조
MainActivity.kt
→ 앱 시작점

CameraScreen.kt
→ CameraX, 프레임 분석, 상태 연결

DmsAnalyzer.kt
→ DMS 상태 판단

PhoneDetector.kt
→ TFLite YOLO 휴대폰 감지

DmsOverlay.kt
→ UI 표시

DmsModels.kt
→ 상태/데이터 모델

WarningManager.kt
→ 진동/경고음
