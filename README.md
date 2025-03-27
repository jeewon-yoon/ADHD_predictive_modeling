# ADHD의 부주의/충동성 예측 모델  
**프로젝트 상세 소개:** [포트폴리오 링크](https://drive.google.com/file/d/1WE2KaVW89SnjrjfuAqQkS_wPueiEPqsC/view?usp=drive_link)   
<br>

# 프로젝트 개요
ADHD를 포함한 정신과 질환들은 동일한 진단을 받은 환자군 내에서도 증상이 개별적으로 다르게 나타나 정확한 치료를 위해서는 추가적으로 뇌영상 데이터 분석을 통한 정밀한 평가가 요구됨. 기존 ADHD 관련 뇌 연구들은 질환의 전반적인 특성과 관련된 뇌 영역을 분석하는 데 중점을 두었기 때문에, 환자 개개인의 증상 차이를 발견하고 세분화된 증상을 분석하는 데 한계가 있었고 기존 연구결과만으로 환자에 대한 정확한 파악이 어려움. 분석 방향 설계) ADHD를 하나의 질환(범주)로 보기보다는 개인별 특정 증상에 집중하고 개인차를 반영한 예측모델을 구축. ADHD의 주요 증상(부주의, 충동성)에 대해 각각 유의미한 예측모델을 구축. 범주적 접근이 아닌 세부 증상을 살펴보는 것의 가능성을 입증. 
<br><br>

# 연구배경  
정신과 질환의 난제는 환자가 진단받은 질환 외에도 다양한 임상적 특징이 동반되거나 인지적 결손의 심각성이 개인마다 크게 다르기 때문에 정확한 진단이 어려움. 국립 정신 건강 연구소(NIMH)는 RDoC이라는 프로젝트를 통해 이러한 문제를 해결하기 위한 방향으로 "질환명을 기준으로 범주화하는 접근법이 아니라, 환자 개개인을 고유한 존재로 바라보는 초개인화적 접근의 필요성"을 강조.
ADHD 환자의 뇌 영역을 정상 대조군과 비교하여 이상을 보이는 부분에 대해 지속적인 연구가 진행되었으나 ADHD는 다양한 인지 기능 장애와 관련 신경 상관관계가 존재하기 때문에, 연구 결과가 일관되지 않아 신뢰성이 부족하다는 한계를 보입니다. 이러한 문제를 해결하기 위해 데이터 분석 분야에서는 관련 뇌 영역을 통합하고, 행동 및 증상과의 관계를 조사하는 계산 모델(computational models)을 개발하여 분석의 견고성을 높였습니다. 다만, 개별 피험자의 ADHD 주요 증상을 예측하며 개인차를 고려한 모델은 아직 부족한 실정입니다.
<br><br>

# 분석 방향  
더 정교한 데이터 분석법들(기계 학습, 모델링)을 많이 사용하여 단순히 뇌영역과 인지적 결손의 관계를 정의하는 것과는 다른 의미있는 결과를 도출하는 것이 가능하다. 
관련 뇌 영역을 통합하고, 행동 및 증상과의 관계를 조사하는 계산 모델(computational models)을 개발
<br><br>

# 데이터셋  
소아정신과를 방문한 ADHD로 진단받지 않은 아동들과 ADHD를 진단받은 아동들 300명 이상의 임상검사 점수 & 뇌영상 이미지(fMRI)
<br><br>

# 데이터 전처리  
* 뇌영상 이미지 전처리 Workflow
<img width="708" alt="image" src="https://github.com/user-attachments/assets/08cdedca-695c-4cd8-9392-2f91e0c4d586" />

* 뇌영상 데이터 시각화 결과물 
<img width="221" alt="image" src="https://github.com/user-attachments/assets/c0b20266-e875-419d-9806-03913238e356" />
<br>  
<br>

- 임상검사(K-ARS: ADHD 평가 척도)
<img width="407" img height="500" alt="image" src="https://github.com/user-attachments/assets/d3e142d8-bd2c-4770-b073-201eec831311" />

<br><br>

# 분석 방법  
MATLAB을 사용하여 크게 1.변수선택(feature selection), 2.모델구축(model construction), 3.모델검증(model validation)의 단계를 통해 예측 모델을 구축함.
<br><br>

# 연구결과  
부주의, 충동성 각각에 대하여 유의미한 선형회귀 예측 모델을 구축할 수 있었고 이를 통해 환자 개개인에 대한 맞춤형 접근의 가능성을 확인. 추후 지속적인 연구를 통해 더 정확한 진단과 그에 따른 치료나 처방을 개선할 수 있음.  
