# iM_Digtal_Banker

# Pandas 기초 문법

이 저장소는 **Python의 Pandas 라이브러리**를 활용한 데이터 분석 기초 문법을 정리한 자료입니다. Pandas를 처음 접하는 분들이 쉽게 이해할 수 있도록 주요 기능과 예제를 포함하고 있습니다.

## 📌 주요 내용

- **Pandas 개요**: Pandas의 기본 개념과 활용 목적
- **데이터 구조**
  - Series
  - DataFrame
- **데이터 불러오기 및 저장하기**
  - CSV, Excel, JSON 파일 다루기
- **데이터 조회 및 선택**
  - 인덱싱과 슬라이싱
  - 조건부 필터링
- **데이터 전처리**
  - 결측치 처리
  - 중복 데이터 제거
  - 데이터 변환 및 정렬
- **그룹화 및 집계**
  - groupby(), pivot_table()
- **데이터 시각화**
  - Matplotlib, Seaborn을 활용한 시각화

## 🛠 설치 방법

Pandas가 설치되어 있지 않다면, 아래 명령어를 실행하여 설치할 수 있습니다.

```bash
pip install pandas
```

추가로, Jupyter Notebook 환경에서 실행하고 싶다면 다음 패키지도 설치해주세요.

```bash
pip install jupyter
```

## 📂 파일 구조

```
📁 pandas_basics
├── 📄 README.md  # 프로젝트 소개 및 설명
├── 📄 pandas_basics.ipynb  # Pandas 기초 문법 정리
├── 📁 data  # 샘플 데이터 (CSV, Excel 등)
└── 📁 images  # 예제 출력 이미지
```

## 📖 사용법

Jupyter Notebook에서 실행하는 방법:

```bash
jupyter notebook pandas_basics.ipynb
```

또는 Python 스크립트에서 실행할 수도 있습니다.

```python
import pandas as pd

# CSV 파일 불러오기
df = pd.read_csv('data/sample.csv')
print(df.head())
```

## 🤝 기여하기

오타 수정, 예제 코드 추가 등 기여를 환영합니다! Pull Request 또는 Issue를 남겨주세요. 😊

## 📜 라이선스

MIT License 하에 배포되며 자유롭게 수정 및 배포가 가능합니다.
