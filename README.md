# Robot_Dont_Makes_Mistakes

![](https://github.com/joonyle99/Robot_Dont_Makes_Mistakes/assets/67359781/8b811a04-b2e4-4464-918e-2562019290de)

* 프로젝트 이름 : `로봇은 실수하지 않아`
* 장르 : `캐주얼` / `스텔스 시뮬레이션` / `전략` / `생존` / `멀티 엔딩` / `싱글` / `탑뷰`
* 개발 환경 : `Visual Studio 2022` / `WinAPI` / `C++`
* 제작 기간 : `2023.05.15` ~ `2023.05.26`
* 담당 파트 :
  1. `유한 상태 머신(FSM) 설계 및 각 상태에 따른 기능 구현`
     - 플레이어 : Idle, Move, Rest, Die
     - 사장님 : Idle, Patrol, Find, Done
  2. `FMOD API를 이용한 SoundManager`
  3. `PathManager와 ResourceManager`
     - Bitmap Texture와 같은 리소스를 손쉽게 가져와서 사용
  4. `각종 Util 클래스 및 콘텐츠 제작`

<details>
<summary>느낀점</summary>
<div markdown="1">

<br>

__개발 관점__  
: Win32API와 C++을 활용한 게임 엔진 개발 경험을 통해 저수준 프로그래밍을 경험할 수 있었습니다. 단순한 비트맵 파일 하나를 로드 하는 과정조차도 수많은 코드가 필요했고, 윈도우 핸들, 디바이스 컨텍스트, 등의 시스템 객체는 하드웨어와 접근하기 위한 추상화 인터페이스로, 시스템 아키텍처에 대한 이해를 도왔습니다. 이러한 저수준 프로그래밍 경험은 앞으로의 Unity와 같은 상용엔진을 더욱 깊이 이해하기 위한 밑바탕이 될 것이라고 생각합니다.

__프로젝트 관점__  
: 저는 해당 프로젝트에서 커뮤니케이션의 중요성을 배웠습니다. 이슈가 발생할 때마다 팀원 모두가 모여 회의를 진행했고, 계속해서 목표를 수정해 나갔으며, 그 내용을 공유했습니다. 그 결과 프로젝트에 대한 명확한 목표 설정과 역할 분담을 통해 팀원 모두가 하나라는 목표를 바라보고 작업할 수 있었습니다.
놀랍게도 기획 및 아트 부서와의 회의에 소요된 시간이 실제 개발 시간보다 더 많았을 정도로 커뮤니케이션에 집중했고, 이를 통해 개발 효율성을 극대화하고 팀 사기를 높일 수 있었습니다. 

</div>
</details>

#### 기술 문서 : [https://github.com/joonyle99/Robot_Dont_Makes_Mistakes/discussions/3 ](https://github.com/joonyle99/Robot_Dont_Makes_Mistakes/discussions/3)  
#### 플레이 영상 : [https://www.youtube.com/watch?v=wxcprpCqLQU](https://www.youtube.com/watch?v=wxcprpCqLQU)

![](https://github.com/joonyle99/Robot_Dont_Makes_Mistakes/assets/67359781/2726e3c9-bed2-4bbe-89c5-b35e49c4d636)
