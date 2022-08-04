# Just-DDance
모션 인식을 통한 안무 연습과 음악 추천

팀장: 김채현
팀원: 김동영, 박대희, 서진원, 주소리

### 1. 주제
1. 모션 인식을 통한 안무 연습 및 피드백 제공 서비스
2. 모션 감지와 실제 안무 간 유사도를 이용한 음악 찾기 및 추천

### 2. 선정의 배경 및 이유

COVID-19의 영향으로 실내 활동의 중요성이 대두된 상황에서, 실내에서 즐길 수 있는 여가 활동의 다양성 확보를 위한 일환 중 하나로 운동을 도와주는 서비스에서 아이디어를 얻어 시작하게 되었습니다.

장기자랑 등을 위해 춤을 연습하는 경우, 일반적으로 안무 영상을 보며 따라하는 방식으로 연습을 하게 됩니다. 그러나 단순히 영상을 보며 따라하는 방법은 결국 안무를 모두 스스로 암기할 수밖에 없습니다. 또한 이후, 본인의 춤추는 영상을 보면서 역시 스스로 틀린 부분을 찾고 고치는 방식으로 이뤄지게 됩니다.

그래서 본 프로젝트는 원본 안무 영상과 본인의 안무 영상을 비교하며 틀린 부분을 직접 찾아야 하는 번거로움을 줄여주고, 특정 동작에서 어떤 부분을 어떻게 고치면 좋을지 피드백을 해주는 서비스를 기획했습니다. 

### 3. 목적

바쁜 일상 속 쉽고 간편하게 집에서 춤을 배우거나 춤으로 운동하고 싶은 사람들에게 즉각적 자세 교정 피드백을 통해 도움을 주는 서비스 구현

사용자의 무작위 몸짓을 기반으로 유사성을 이용하여 그때 마다의 무드에 맞는 노래(안무) 추천

### 4. 데이터셋

- 유튜브 안무 영상 크롤링
- 감정 분석을 위한 감정 데이터 셋

### 5. 예상 결과물(가설 설정)

진행되는 프로젝트는 본인의 춤추는 영상을 나중에 보면서 어는 부분에서 틀렸는지 찾고 피드백을 통해 고치는 방법으로 고치는 방식으로 이뤄집니다. 더 나아가 무작위 몸짓에 가장 어울리는 노래도 찾아줍니다.

### 6. 예상 활용 라이브러리, 알고리즘 등의 기술적 요소

- Mediapipe
- openCV
- Selenium
- Tensorflow
- PyTorch