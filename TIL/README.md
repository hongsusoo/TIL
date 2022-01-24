# 2022

## **mind set**
- 하나씩 천천히 성급하지 않게, 조급함은 도움이 안됨
- 일주일에 한 번은 회고하기
- 빠르게 실패하기(Fast Fail)

## January

### Week 4 (1/24~1/30)

- [ ]  코테 7문제 풀기 ✅◻️◻️◻️◻️◻️◻️
- [ ]  지원서 제출 (보이저엑스◻️, 노타◻️)
- [ ]  면접 (라온피플◻️)
- [ ]  면접스터디 준비(~1/28)
- [ ]  카카오 과제 코드 작성 시작 - 학습◻️, 평가◻️, 결과 도출◻️

- 1/30 (Sun)
    - [ ] 운동

- 1/29 (Sat)
    - [ ] 운동

- 1/28 (Fri)
    - [ ] 운동

- 1/27 (Thu)
    - [ ] 운동

- 1/26 (Wed)
    - [ ] 운동

- 1/25 (Tue)
    - [ ] 운동

- 1/24 (Mon)
    - [x] 운동
    - [x] 알고리즘 문제 - 1439 그리디
    - [x] 라온피플 PT 준비
    - [x] 카카오 과제 Baseline 및 dataset구성

### Week 3 (1/17~1/23)

- [ ]  코테 7문제 풀기 ✅✅◻️◻️◻️◻️◻️
- [ ]  지원서 제출 (네이버 제트✅, 보이저엑스◻️, 스노우✅)
- [ ]  면접 준비(누비랩✅, 라온피플◻️)
- [x]  면접스터디 준비(~1/21)
- [x]  카카오 과제 코드 작성 시작 - Crawling
- [ ]  Dacon - 틀리는 데이터 visualization, 모델 Test

- 1/23 (Sun)
    - [x] 운동
    - 알고리즘 15483 풀이 정리
    - 카카오 과제 Baseline 구축 → colab
    - 라온피플 PT 준비

- 1/22 (Sat)
    - [x] 운동
    - [x]  알고리즘 문제 - 15483
    - [x]  카카오 과제 - data Crawling 진행

- 1/21 (Fri)
    - [x] 운동
    - [ ] 알고리즘 스터디 - 15483
    - [x] 스노우 지원서
    - [ ] 보이저 엑스 지원서

- 1/20 (Thu)
    - [x] 운동
    - [x] 알고리즘 스터디 - 14501
    - [x] 네이버 제트 지원서

- 1/19 (Wed)
    - [x] 운동
    - 인성면접 준비(오전)
    - 카카오 과제 준비 
        - Data 확보 -> Data.go.kr, 제주관광공사, Kaggle 사이트
        - Crawling -> 셀레니움 공부
    - 누비랩 1차 인터뷰
    - 네이버 제트 지원서 작성

- 1/18 (Tue)
    - [x] 운동
    - 네이버 제트 미팅 3시
    - 알고리즘 스터디 시작! 1/20부터
    - Dacon 
        - .py 파일 작성
        - resnet151 flip, rotate augmentation 추가 test
    - 면접스터디
        - 모수와 비모수
    - 기술
        - DLSS : deep learning super sampling
            NVIDIA에서 GPU에 연산장치를 추가하여 게임에서 raytracing을 학습하여 반복적인 작업의 연산을 최소화하는 방법으로 FPS를 높이고 화질을 개선

- 1/17 (Mon)
    - [x] 운동
    - 면접스터디 준비 내용
        고유값(eigen value)와 고유벡터(eigen vector)에 대해 설명해주세요. 그리고 왜 중요할까요?
        샘플링(Sampling)과 리샘플링(Resampling)에 대해 설명해주세요. 리샘플링은 무슨 장점이 있을까요?
        확률 모형과 확률 변수는 무엇일까요.
        누적 분포 함수와 확률 밀도 함수는 무엇일까요? 수식과 함께 표현해주세요.
        조건부 확률은 무엇일까요?
        공분산과 상관계수는 무엇일까요? 수식과 함께 표현해주세요.
        신뢰 구간의 정의는 무엇인가요?
        p-value를 모르는 사람에게 설명한다면 어떻게 설명하실 건가요?
        R square의 의미는 무엇인가요?
        평균(mean)과 중앙값(median)중에 어떤 케이스에서 뭐를 써야할까요?
        중심극한정리는 왜 유용한걸까요?
        엔트로피(entropy)에 대해 설명해주세요. 가능하면 Information Gain도요.
    - 보이저 엑스 준비
        - 압축방식 : BMP(비손실), JPEG(손실), GIF(), PNG(비손실) 
            - BMP(BitMap) : 그림을 저장하는 포멧, 사진 원본, 가끔 RLE(Run-length encoding : 연속해서 나타나는 데이터를 갯수와 반복되는 값만으로 표현한 방식) 압축방식을 사용하기도함
            - JPEG(Joint Photographic Experts Group) : JPG로도 불리며 이전엔 포멧의 이름이 3자리로 사용되었기 때문에 JPG로 이름이 붙여졌지만, JPEG와 동일한 포멧임, ① 사람의 눈이 색차보단 휘도차에 민감하기 때문에 휘도와 색으로 구분지어서 나눔, ②4:2:0으로 subsampling 진행, ③ Sub sampling 이후 각 채널은 8x8블락으로 변환하여 DCT 진행, ④ 고주파영역을 제거(양자화)
                RGB -> YCrCb -> Downsampling(subsampling) -> DCT(이산 코사인변환) -> 양자화 -> zigzag 스캐닝 -> encoding
            - GIF(Graphics Interchange Format) : LZW 알고리즘을 사용하여 압축하는 방식, 가볍게 인터넷 공유용으로 많이 사용됨
            - PNG(Portable Network Graphics) : DEFLATE라는 무손실 압축 알고리즘을 통해 고품질을 유지 데이터가 커짐, GIF 특허문제로 고안됨

    - 네이버 제트 3D Graphics 엔지니어링 업무
        - Pose IK(inverse kinematric) : body part의 경우 parent와 child를 나눠서 진행하게 되는데, child를 움직였을때 parents가 움직이도록 구현하는 방법을 IK라고 하고 반대로 FK(forward kinematric)은 Parents가 움직였을때 Child가 따라 움직이는 방법
        - Pose solve(minimal solver) : Perspective n Point problem을 해결하기 위한 방법, 카메라 관점에 따라 좌표가 변환되는 것을 품
        - Unity(C#) : 가볍게 3D 모델링 구현이 가능함 하지만 빡세게 하면 잘 만들 수 있음, 그리고 C#을 이용해 언어적으로도 쉬워서 접근성이 좋고 자료도 많아서 쉽게 배울수 있음
        - Unreal(C++) : 무거움 빡세게 하면 엄청 실제같은 3D 구현이 가능함

### week 2 (1/10~1/16)

### 1/15

- [x] Alorithm 문제 풀기
- [ ] (Dacon) RNN -> min, max 값으로 대체하여 Test
- [ ] 면접스터디 준비
- [x] 카카오 과제 아이디어 정리

### 1/14

- [x] Alorithm 문제 풀기( + 마키나락스 코테)
- [x] (Dacon) Transformer or 다른 모델 제출
- [x] 면접스터디 진행 방향 정하기
- [ ] 카카오 과제 아이디어 정리

### 1/13

- [ ] Alorithm 문제 풀기 - 3687번
- [x] (Dacon) Transformer 시도 중
- [ ] 면접스터디 준비 -> 스터디 방식 정하기

### 1/12

- [ ] Alorithm 문제 풀기
- [ ] (Dacon) 진행 방향 정리
- [ ] LSTM 공부

### 1/11

- [x] Alorithm 문제 풀기
- [x] Dacon 돌리기
- [ ] LSTM 공부
- [x] 최종프로젝트 추가 내용 Listup

### 1/10

- [x] Alorithm 문제 풀기
- [ ] Dacon 돌리기
- [ ] LSTM 공부