# 목차

* [소개](intro.md)
* [1주차: AI·머신러닝 기초](week1-ml/)
  * [AI vs ML vs DL](week1-ml/day1.md)
  * [NumPy 기본 연산](week1-ml/day2.md)
  * [Pandas 데이터프레임 입출력·전처리](week1-ml/day3.md)
  * [선형회귀 예제 (scikit-learn)](week1-ml/day4.md)
  * [분류(Classification) 예제](week1-ml/day5.md)
  * [모델 평가 지표(Accuracy, Precision, Recall)](week1-ml/day6.md)
  * [요약 및 복습](week1-ml/day7.md)


* [2주차: LLM·sLLM 이론](week2-llm/)
  * [Day 1: Transformer 구조](week2-llm/day1.md)
  * …
* [3주차: sLLM 로컬 실행 환경](week3-env/)  
* …  



    Transformer 아키텍처
    Self-Attention 원리
    토크나이저(BPE, WordPiece)
    LLM 경량화(Quantization, Distillation)

3주차: sLLM 로컬 실행 환경 구축
    Docker 설치·기본 사용법
    llama.cpp 또는 GPT-NeoX 빌드·로드
    Python 래퍼 연동 (pyllamacpp 등)
    간단한 질의응답 스크립트 작성

4주차: sLLM 실습 심화 및 성능 튜닝
    배치 사이즈·스레드 조정
    8비트/4비트 양자화 적용
    응답 속도·메모리 사용 모니터링
    캐시·메모리 풀링 기법

5주차: Base Template 설계
    디렉터리·모듈 구조 설계
    sLLM 래퍼·핵심 인터페이스 정의
    asyncio 비동기 흐름 설계
    설정 파일·로깅·예외 처리 표준화

6주차: 하드웨어 연동 (Jetson/Pi)
    GPIO 파이썬 라이브러리 설치
    LED·버튼 제어 실습
    I2C 온습도 센서 읽기
    PWM 서보 모터 제어
    이벤트→sLLM 요청 플로우 구현

7주차: 통합 개발·테스트·문서화
    단위 테스트(PyTest)
    통합 테스트(하드웨어 시뮬레이션 포함)
    배포 스크립트(Makefile/Shell)
    systemd 서비스 설정
    README·사용자 가이드 작성
    전체 복습 및 차기 계획 수립