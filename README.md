# Webots 기반 차선 유지 제어 시뮬레이션 프로젝트

---
<br>


## 1. 프로젝트 개요 (Project Overview)
본 프로젝트는 **Webots 시뮬레이터 환경**에서 차량의 비전 센서만을 사용하여 안정적인 차선 유지 제어를 구현하는 것을 목표로 합니다.

---

<br>
<br>

## 2. 팀원 소개 및 역할 (Team Member)
| 이름 | 소속 | 역할 및 담당 기능 |
| :---: | :---: | :--- |
| **김민호** | 숭실대학교 AI소프트웨어학부 | 팀장, 차량 동역학 기반 제어 알고리즘 구현 |
| **박경수** | 숭실대학교 AI소프트웨어학부 | 데이터셋 수집 및 기본 전처리 |
| **김철현** | 숭실대학교 AI소프트웨어학부 | CNN 기반 차선 인식 모델 학습 및 검증 |
| **송규혁** | 숭실대학교 AI소프트웨어학부 | 최종 코드 통합 및 ROS2 연결 |

---

<br>
<br>

## 3. 기술 스택 (Tech Stack)

### Environment & Simulation
<img src="https://img.shields.io/badge/Webots-FF0000?style=for-the-badge&logo=Webots&logoColor=white"/> <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=Ubuntu&logoColor=white"/>

### Programming Languages
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"/> <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=C%2B%2B&logoColor=white"/>

### Libraries & Frameworks
<img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ROS&logoColor=white"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=OpenCV&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"/> <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=NumPy&logoColor=white"/>

--- 

<br>
<br>

## 📂 4. 폴더 구조 (Repository Structure)
```text
├── .gitignore              # Git 업로드 제외 파일 설정 (Python/C++ 캐시 및 빌드 파일 제거)
├── README.md               # 프로젝트 메인 대문 (현재 파일)
│
├── dataset/                # 자율주행 학습 및 테스트용 대용량 데이터셋 (외부 드라이브 연동)
│   └── README.md           # 데이터셋 다운로드 링크 및 위치 안내
│
└── src/                    # 프로젝트 소스 코드 폴더
    ├── core/               # 공통 자율주행 베이스라인 및 메인 알고리즘 코드
    ├── Minho/              # 팀원별 개별 작업 및 실험 폴더
    ├── Kyeongsu/               
    ├── Cheolhyun/          
    └── Doyoung/      
