# SolidWorks Python 인터페이스 프로젝트

이 그룹 과제는 Python 인터페이스를 통해 SolidWorks를 제어하고 CAD 작업을 자동화하는 프로젝트입니다.

## 프로젝트 개요
- **목표**: Python 스크립트를 작성해 SolidWorks에서 부품을 생성하고 작업을 자동화하기.
- **참여**: B 이상을 목표로 하는 고학년 학생들에게 필수 (그룹 프로젝트).
- **성적 기준**:
  - **최대 B**: SolidWorks에 대한 기본 인터페이스 구축 (Windows 전용).
  - **B+**: 인터페이스에 대한 `pytest` 테스트 추가.
  - **최대 A**: 3D 부품 생성 기능 추가 (예: 스케치 압출).
  - **A+**: 3D 부품 생성에 대한 `pytest` 테스트 추가.
- **발표**: 5~10분 분량의 데모 및 코드 설명.
- **LLM 사용**: 허용되며, 단 모든 코드를 설명할 수 있어야 함.

## 주요 단계
### 1. 기본 인터페이스 (최대 B)
- **목표**: Python으로 SolidWorks 제어.
- **과제**: SolidWorks에 연결, 새 부품 생성, 간단한 스케치 그리기 (예: 사각형).
- **결과물**: SolidWorks에서 도형을 그리는 스크립트.

### 2. 테스트 추가 (B+)
- **목표**: `pytest`로 인터페이스 검증.
- **과제**: 테스트 작성 (예: 스케치 생성 확인).
- **결과물**: 통과하는 테스트 모음.

### 3. 3D 부품 생성 (최대 A)
- **목표**: 스케치를 3D 객체로 확장.
- **과제**: 스케치 작성 후 압출해 3D 부품 생성 (예: 직육면체).
- **결과물**: 3D 부품을 그리는 스크립트.

### 4. 3D 기능 테스트 (A+)
- **목표**: 3D 부품 생성을 `pytest`로 검증.
- **과제**: 부품 속성 테스트 (예: 높이, 부피).
- **결과물**: 통과하는 테스트 모음.

## 요구 사항
- **도구**: Python 3.8 이상, `pywin32`, SolidWorks (Windows), `pytest`.
- **일정**:
    - 시작 03/24월~03/29금
    - 마감 05/19월~05/23금
- **제출**: 코드, 데모, 발표 자료.

## 참고 자료
- [SolidWorks API 도움말](https://help.solidworks.com/)
- [pywin32 문서](https://pypi.org/project/pywin32/)
- [pytest 문서](https://docs.pytest.org/)
