# 라쿤봇 Python API 메뉴얼

<br>

![RaccoonBot_MainPage](https://github.com/user-attachments/assets/96bde97c-dc2f-4807-ba98-85707854b45f)

<br>

**라쿤봇** 사용자들을 위한 [Python API Wiki](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki)입니다.


이 문서는 로보메이션의 **라쿤봇**을 **Python**으로 프로그래밍하려는 사용자를 위한 **API 메뉴얼**입니다. 

아래 목차에서 **도움말**을 보고싶은 **목차**를 선택하세요.

<br><br>


### [시작하기에 앞서](/시작하기에%20앞서.Md)

### [초보자를 위한 파이썬 설치 가이드](/초보자를%20위한%20파이썬%20설치%20가이드.md)

### [하드웨어 설명](/하드웨어%20설명.md)
<br>


# [생성 및 해제](/생성%20및%20해제.md)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/생성-및-해제#라쿤봇-생성">
            라쿤봇 생성
        </a>
    </summary>

- [Raccoon](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/생성-및-해제#raccoon)
- [Raccoon(index)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/생성-및-해제#raccoonindex)
- [Raccoon(port_name)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/생성-및-해제#raccoonport_name)
- [Raccoon(index, port_name)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/생성-및-해제#raccoonindexport_name)

</details>

<details>
    <summary>
        <a href = "https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/생성-및-해제#라쿤봇-해제">
        라쿤봇 해제
    </summary>

- [dispose()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/생성-및-해제#dispose)
- [reset()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/생성-및-해제#reset)

</details>

<br>


# [관절 제어](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어)

<details>
    <summary><a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#관절-속도-설정">관절 속도 설정</a></summary>
- [velocity(joint, value)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#velocityjoint-value)
- [velocity(joint1, joint2, joint3, joint4)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#velocityjoint1-joint2-joint3-joint4)

</details>

<details>
    <summary><a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#관절-각도-설정">관절 각도 설정</a></summary>

- [degree_to(joint, value, speed)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#degree_tojoint-value-speed)
- [degree_to(joint1, joint2, joint3, joint4, speed)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#degree_tojoint1-joint2-joint3-joint4-speed)
- [degree_by(joint, value, speed)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#degree_byjoint-value-speed)
- [degree_by(joint1, joint2, joint3, joint4, speed)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#degree_byjoint1-joint2-joint3-joint4-speed)
- [set_degree(joint, value, speed)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#set_degreejoint-value-speed)
- [set_degree(joint1, joint2, joint3, joint4, speed)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#set_degreejoint1-joint2-joint3-joint4-speed)

</details>

<details>
    <summary><a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#관절-정지">관절 정지</a></summary>

- [stop()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/관절-제어#stop)

</details>


<br>


# [좌표 및 기구학](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#좌표-제어">
            좌표 제어
        </a>
    </summary>

- [can_move_to(x, y, z)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#can_move_tox-y-z)
- [can_move_by(dx, dy, dz)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#can_move_bydx-dy-dz)
- [move_to(x, y, z, speed)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#move_tox-y-z-speed)
- [move_by(dx, dy, dz, speed)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#move_bydx-dy-dz-speed)

</details>


<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#순기구학">
            순기구학
        </a>
    </summary>

- [deg_to_xyz(deg1, deg2, deg3, deg4, length)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#deg_to_xyzdeg1-deg2-deg3-deg4-length)
- [xyz(length)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#xyzlength)

</details>


<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#역기구학">
            역기구학
        </a>
    </summary>

- [xyz_to_deg(x, y, z)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/좌표-및-기구학#xyz_to_degx-y-z)

</details>

<br>


# [말단 장치](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/말단-장치)


<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/말단-장치#말단-장치-고정">
            말단 장치 고정
        </a>
    </summary>

- [lock_horz()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/말단-장치#lock_horz)
- [lock_vert()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/말단-장치#lock_vert)
- [unlock()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/말단-장치#unlock)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/말단-장치#말단-장치-제어">
            말단 장치 제어
        </a>
    </summary>

- [open_gripper()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/말단-장치#open_gripper)
- [close_gripper()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/말단-장치#close_gripper)

</details>

<br>


# [소리](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#주파수-제어">
            주파수 제어
        </a>
    </summary>

- [tempo(bpm)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#tempobpm)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#note-제어">
            NOTE 제어
        </a>
    </summary>

- [note(pitch)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#notepitch)
- [note(pitch, beats)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#notepitch-beats)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#멜로디-제어">
            멜로디 제어
        </a>
    </summary>

- [sound(sound_id)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#soundsound_id)
- [sound(sound_id, repeat)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#soundsound_id-repeat)
- [sound_until_done(sound_id)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#sound_until_donesound_id)
- [sound_until_done(sound_id, repeat)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#sound_until_donesound_id-repeat)
- [beep()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/소리#beep)

</details>

<br>


# [센서](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/센서)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/센서#관절-엔코더-값">
            관절 엔코더 값
        </a>
    </summary>

- [encoder(joint)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/센서#encoderjoint)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/센서#신호-세기-값">
            신호 세기 값
        </a>
    </summary>

- [signal_strength()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/센서#signal_strength)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/센서#배터리-충전-값">
            배터리, 충전 값
        </a>
    </summary>

- [battery_state()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/센서#battery_state)
- [charge_state()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/센서#charge_state)

</details>

<br>


# [버튼](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#pick-버튼">
            Pick 버튼
        </a>
    </summary>

- [teach_button()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#teach_button)
- [teach_clicked()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#teach_clicked)
- [teach_long_pressed()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#teach_long_pressed)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#play-버튼">
            Play 버튼
        </a>
    </summary>

- [playback_button()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#playback_button)
- [playback_clicked()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#playback_clicked)
- [playback_long_pressed()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#playback_long_pressed)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#erase-버튼">
            Erase 버튼
        </a>
    </summary>

- [delete_button()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#delete_button)
- [delete_clicked()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#delete_clicked)
- [delete_long_pressed()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/버튼#delete_long_pressed)

</details>

<br>


# [전역 함수](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수)

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#해제-다중-작동-포트-출력-콜백-함수">
            해제, 다중 작동, 시리얼 포트 출력, 콜백함수
        </a>
    </summary>

- [dispose()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#dispose)
- [parallel(function1, function2, ...)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#parallelfunction1-function2-)
- [parallel((function1, args1), (function2, args2), ...)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#parallelfunction1-args1-function2-args2-)
- [scan()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#scan)
- [set_executable(execute)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#set_executableexecute)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#대기-함수">
            대기 함수
        </a>
    </summary>

- [wait(milliseconds)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#waitmilliseconds)
- [wait_until(evaluate)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#wait_untilevaluate)
- [wait_until(evaluate, args)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#wait_untilevaluate-args)
- [wait_until_ready()](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#wait_until_ready)

</details>

<details>
    <summary>
        <a href="https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#조건-함수">
            조건 함수
        </a>
    </summary>

- [when_do(when, do)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#when_dowhen-do)
- [when_do(when, do, args)](https://github.com/RobomationLAB/RaccoonBot_API_KR/wiki/전역-함수#when_dowhen-do-args)

</details>

<br><br>

>이 설명서의 정보는 사전 통지 없이 변경될 수 있으며 로보메이션은 해당 정보에 어떠한 책임도 지지 않습니다.<br> 
로보메이션은 이 설명서에 나타날 수 있는 어떠한 오류에도 책임을 지지 않습니다.<br>
이 설명서에 명시적으로 표기된 경우를 제외하고, 이 설명서의 어떠한 내용도 로보메이션이 인명 또는 재산 손실,<br>
손상 또는 특정 목적에의 적합성에 대한 보장이나 보증을 하는 것으로 해석될 수 없습니다.<br>
로보메이션은 어떠한 경우에도 이 설명서와 여기에 설명된 제품을 사용하여 발생하는 우발적 또는 결과적 손해에 대해<br>
책임을 지지 않습니다.
로보메이션의 서면 승인 없이 이 설명서와 설명서의 일부를 재생산하거나 복사할 수 없습니다.<br>

><a href="https://www.robomation.net" target="_blank">www.robomation.net</a><br>
`roboid version-1.7.3`

