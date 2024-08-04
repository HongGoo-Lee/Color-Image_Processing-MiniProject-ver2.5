# 미니 프로젝트 버전 2: OpenCV를 사용하지 않은 Python 기반 영상처리 프로그램

## 소개
이 미니 프로젝트는 OpenCV를 사용하지 않고 Python을 이용하여 다양한 영상 처리 작업을 수행하는 프로그램입니다. 이 프로젝트는 화소 처리, 기하학적 변환, 히스토그램 처리, 화소 영역 처리, HSV 처리를 포함한 여러 기능을 제공합니다.

## 기능 요약

### 화소 처리
1. **원본 이미지 표시**: 원본 이미지를 화면에 표시합니다.
2. **밝기 조절**: 이미지의 밝기를 조절합니다.
3. **반전 이미지**: 이미지를 반전시킵니다.
4. **이진화 (임계값 128)**: 이미지를 임계값 128로 이진화합니다.
5. **논리 연산 (AND, OR)**: 두 이미지 간의 논리 AND 및 OR 연산을 수행합니다.
6. **포스터라이징**: 이미지를 포스터라이징합니다.
7. **감마 보정**: 감마 값을 조절하여 이미지의 명암을 보정합니다.
8. **범위 강조**: 특정 범위를 강조합니다.
9. **파라볼라 변환 **: 이미지에 파라볼라 변환을 적용합니다.

### 기하학적 변환
1. **확대**: 이미지를 확대합니다.
2. **축소**: 이미지를 축소합니다.
3. **이동**: 이미지를 이동시킵니다.
4. **회전**: 이미지를 회전합니다.
5. **좌우 대칭**: 이미지를 좌우 대칭시킵니다.
6. **상하 대칭**: 이미지를 상하 대칭시킵니다.

### 히스토그램 처리
1. **히스토그램 스트레칭**: 히스토그램을 스트레칭하여 이미지의 명암비를 개선합니다.
2. **엔드-인 스트레칭**: 엔드-인 스트레칭을 통해 이미지의 명암비를 조정합니다.
3. **히스토그램 평활화**: 히스토그램 평활화를 통해 이미지의 명암을 고르게 만듭니다.

### 화소 영역 처리
1. **엠보싱**: 이미지에 엠보싱 효과를 적용합니다.
2. **블러링**: 이미지를 블러링합니다.
3. **샤프닝**: 이미지의 선명도를 높입니다.

### HSV 처리
1. **채도 변환**: 이미지의 채도를 변환합니다.
2. **범위 추출**: 특정 HSV 범위 내의 색상을 추출합니다.


## 느낀점 및 향후계획
이번 프로젝트를 통해 GrayScale 이미지 처리 프로그램에서 Color 이미지 처리 프로그램으로 업그레이드하면서 많은 것을 배웠다. 이전에 GrayScale 프로젝트를 이미 진행했기 때문에 이번 작업은 보다 수월하게 느껴졌다. 특히, 큰 어려움 없이 프로젝트를 진행할 수 있어서 만족스러웠다. 이번에는 파이썬을 사용하여 구현했는데, 지난 프로젝트보다 난이도가 상대적으로 쉬웠고, OpenCV 없이도 이미지 처리가 가능한 프로그램을 성공적으로 완성할 수 있어서 매우 뿌듯했다.
다만, 기하학적 처리에서 마우스로 범위를 선택하는 기능을 적용시키지 못한 점은 아쉬움으로 남았다. 앞으로 이 부분을 더 조사하고 공부하여 범위 선택 기능을 추가해 프로그램을 더욱 발전시킬 계획이다. 이를 통해 프로그램의 기능을 한층 더 향상시켜 보다 완벽한 이미지 처리 도구로 성장시킬 예정이다.
