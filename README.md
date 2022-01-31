# Pomodoro-Timer
# 뽀모도로 타이머
***

#### 0~60분 사이의 타이머를 설정하고 종료되면 알람이 울리는 기본적인 타이머 입니다.
* Blog: <https://hwayomingdlog.tistory.com/218>
* Blog: <https://hwayomingdlog.tistory.com/220>
</br>

## 주 기능
***
### 타이머
* 0~60분 사이의 타이머를 세팅할 수 있습니다.
* 1초마다 남은 시간을 보여주는 TextView와 SeekBar의 progress level이 갱신 됩니다.
* 타이머를 가동시키면 Ticking 효과음이 들리며, 종료되면 알람벨이 울립니다.
</br>

## 활용 기술
* ConstraintLayout - ConstraintLayout의 Chain을 이용하여 View들의 위치를 설정하였습니다.
* CountDownTimer - 타이머 기능을 위해 CountDownTimer 클래스를 사용해서 카운트 다운 시간을 예약하고 onTick() 콜백 메서드를 통해 타이머가 가동되는 1초마다 UI를 갱신시켰습니다. 
* SoundPool - Ticking과 종료 알림음을 SounPool 클래스를 사용해서 적용했습니다. Activity Lifecycle을 고려하여 앱의 화면이 포커싱을 잃거나 다시 재개하는 경우에 맞춰 효과음을 일시정지하고 다시 적용하는 로직을 적용했습니다.
</br>

<img src="/path/to/img.jpg" width="450px" height="300px" title="" alt=""></img><br/>
<img src="/path/to/img.jpg" width="40%" height="30%" title="" alt=""></img>


