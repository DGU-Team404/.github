<div align="center">

# 🏠 Team 404

**2026 동국대학교 정보통신공학과 졸업프로젝트 (DGU-ICE Capstone Design)**

</div>

---

## 📱 RoomLog

> 자취/원룸 거주자를 위한 **3D 방 기록 & 하자 관리 서비스**

LiDAR 기반 3D 스캔으로 입주 시점의 방을 기록하고, 퇴거 시 동일 공간을 다시 스캔해
**변경된 영역과 하자를 자동으로 비교·관리**할 수 있는 iOS 앱입니다.
하자 발견 시 주변 수리업체를 추천받아 견적 문의까지 한 번에 진행할 수 있습니다.

## 👥 Members

<table>
  <tr>
    <td align="center"><a href="https://github.com/ddodle"><img src="https://github.com/ddodle.png" width="100" /><br/><b>김도연</b></a></td>
    <td align="center"><a href="https://github.com/mnjese"><img src="https://github.com/mnjese.png" width="100" /><br/><b>김민지</b></a></td>
    <td align="center"><a href="https://github.com/ybkim453"><img src="https://github.com/ybkim453.png" width="100" /><br/><b>김용빈</b></a></td>
    <td align="center"><a href="https://github.com/wk1717"><img src="https://github.com/wk1717.png" width="100" /><br/><b>송민교</b></a></td>
  </tr>
  <tr>
    <td align="center"><b>iOS</b></td>
    <td align="center"><b>Backend</b></td>
    <td align="center"><b>AI</b></td>
    <td align="center"><b>iOS</b></td>
  </tr>
  <tr>
    <td align="center">Auth · Home · Scan<br/>MyPage · Core</td>
    <td align="center">API Server<br/>Infra</td>
    <td align="center">3D Reconstruction<br/>Defect Detection</td>
    <td align="center">Viewer · Defect<br/>Comparison · Estimate</td>
  </tr>
</table>

## ✨ Features

<table>
  <tr>
    <td align="center" width="20%"><b>📡 스캔</b></td>
    <td align="center" width="20%"><b>🧊 3D 결과 확인</b></td>
    <td align="center" width="20%"><b>🔍 하자 탐지</b></td>
    <td align="center" width="20%"><b>🪞 내 방 비교</b></td>
    <td align="center" width="20%"><b>💰 업체 추천</b></td>
  </tr>
  <tr>
    <td align="center"><!-- 이미지/영상 추가 위치 --></td>
    <td align="center"><!-- 이미지/영상 추가 위치 --></td>
    <td align="center"><!-- 이미지/영상 추가 위치 --></td>
    <td align="center"><!-- 이미지/영상 추가 위치 --></td>
    <td align="center"><!-- 이미지/영상 추가 위치 --></td>
  </tr>
  <tr>
    <td align="center"><i>LiDAR로 방 내부를<br/>3D로 녹화</i></td>
    <td align="center"><i>PLY 포인트클라우드<br/>렌더링</i></td>
    <td align="center"><i>AI 기반 하자 위치<br/>자동 태깅</i></td>
    <td align="center"><i>입주 전/퇴거 후<br/>스캔 비교</i></td>
    <td align="center"><i>주변 수리업체 추천<br/>견적 문의</i></td>
  </tr>
</table>

## 📦 Repositories

| Repository | Stack | 설명 |
|---|---|---|
| [**roomlog-ios**](https://github.com/DGU-Team404/roomlog-ios) | `Swift` `SwiftUI` `ARKit` | LiDAR 스캔 · 3D 뷰어 · 하자 관리 iOS 앱 |
| [**roomlog-server**](https://github.com/DGU-Team404/roomlog-server) | `Java` `Spring` | API 서버 · 스캔 데이터 처리 · 업체 추천 |
| [**roomlog-ai**](https://github.com/DGU-Team404/roomlog-ai) | `Python` | 포인트클라우드 재구성 · 하자 탐지 모델 |

## 🛠 Tech Stack

<div>

**iOS**
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F4?style=flat&logo=swift&logoColor=white)
![ARKit](https://img.shields.io/badge/ARKit-000000?style=flat&logo=apple&logoColor=white)

**Backend**
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white)

**AI**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

**Collaboration**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)

</div>
