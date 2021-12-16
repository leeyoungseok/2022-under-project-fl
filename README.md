# 2022-under-project-fl
2022년 학부 졸업프로젝트 주제1
# 제목: 연합학습 모바일 앱

# 주제
연합학습(federated learning)기반 자동차용 Android 또는 iOS 블랙박스 앱 만들기

# 주요내용 
+ 연합학습: 개인정보보호를 위한 분산 연합기술. 클라이언트의 데이터를 단말기에 두고 학습한 통계결과를 서버에서 종합하여 글로벌 모델을 클라이언트에게 배포하는 모델. Google GBoard (키보드앱)을 통해 가능성을 보였고, 현재 개인정보보호 이슈로 핵심 AI 기술로 등장
+ 자동차 데이터 학습: 자동차 데이터는 개인정보에 민감함. 개인의 위치, 운전습관, 블랙박스 카메라의 사진과 동영상 등은 개인정보와 관련되어있기때문에 중앙 서버에서 학습하기에는 부적절한 경우가 많음. 따라서, 자동차에 위치한 단말기에서 실행되는 블랙박스와 같은 앱에서 직접 학습하여 개인정보를 보호하는 기술이 필수임

# 필요기술
+ 연합학습(federated learning) 지식 
+ 연합학습 library 활용: tensorflow federated, pytorch
+ 모바일 앱 개발: Android, iOS
+ 백엔드개발: web server, DB, cloud 활용 서버 개발
+ 블랙박스 앱: 실시간 객체인식 및 분류 모듈 개발


# 예상결과
연합학습기반 자동차 블랙박스 모바일 앱 

# 신청방법 및 선정결과
1. 아래 신청사유 적어서 'Pull Request'를 요청
2. 신청한 조가 2개 이상일 경우 평가 후 결과 발표 ('merge')

# 신청사유(자유양식) 
### 개인정보 언급 금지: 실명, 학번, 전화번호, 이메일주소 등)
### 우리 조가 꼭 해야하는 이유. 성공할 수 밖에 없는 이유. 잘 할 수 있는 이유 등
*
* 
*



# 참고문헌
1. [Google  AI Blog](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html)
2. [Tensorflow Federated](https://www.tensorflow.org/federated/federated_learning)
3. [Federated learning paper by 문현수](https://www.mdpi.com/2079-9292/10/1/27/pdf)
4. [2021년 4학년 연합학습 주제 졸업프로젝트](https://cnuswaiproject.wixsite.com/2021-2/post/%EC%97%B0%ED%95%A9%ED%95%99%EC%8A%B5%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EA%B5%AD%EB%82%B4-%EC%97%AC%ED%96%89%EC%A7%80-%EC%B6%94%EC%B2%9C-%EC%96%B4%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98)