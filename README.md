## roadview_local(도로이미지 라벨작업)

### 1.주요기능

- 도로이미지 라벨작업
- 인공지능 자율주행을 위한 도로 이미지 라벨 작업을 지원한다.
- Rasnet 이미지 학습을 위하여 사용한다.

### 2. 이미지 라벨링

- 이미지 파일 이름:  aaa_bbb.jpg 형태로 구성한다. 
- 앞자리 aaa 는 이미지(jpg) 파일별 순차적으로 연속된 번호를 사용한다.
- 뒷자리 bbb 는 -45도 ~ +45 도를 포시하는 진행해야 되는 각도를 표시한다.

### 3. 사용방법

1) 로컬 디렉토리에 특정디렉토리를 생성한다.
2) 생성된 디렉토리 안에 자동차가 주행하면서 수집된 이미지를 넣는다.
3) 이미지의 이름은 순차적은 번호를 가지도록 한다. 

!!! 예제
    001_020.jpg, 002_-20.jpg

4) 각 숫자의 단위는 3자리를 가지도록 한다.
5) 다음 웹사이트로 접속 한다.  
    https://rco123.github.io/roadview_local/

6) 이미지가 들어있는 디렉토리를 선택하고 해당 접속 버턴을 수행한다.

7) 도로의 진행방향을 지정하면, 파일의 뒷자리 각도 부분이 지정된 방향에 따라 각도가 변경된다.

*** 사용방법 동영상 참조 ***
  - `howto:`
  https://youtu.be/VFQqeDorDZY

<video width="640" height="360" controls>
  <source src="https://youtu.be/VFQqeDorDZY" type="video/mp4">
  Your browser does not support the video tag.
</video>




