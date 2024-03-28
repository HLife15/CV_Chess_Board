제가 직접 촬영한 체스보드 동영상을 이용해 카메라 캘리브레이션을 수행하고 렌즈 왜곡 보정을 수행했습니다.

- 카메라 캘리브레이션 수행 (사용 코드 : camera_calibration.py)
![calibration](https://github.com/HLife15/CV_Chess_Board/assets/162321808/eb168109-52e1-4a1a-a154-45de9de6aa54)

[카메라 캘리브레이션 결과]
* The number of selected images = 11
* RMS error = 1.4191920262564757    
* Camera matrix (K) = <br>
[[1.26064501e+03 0.00000000e+00 7.44017741e+02]<br>
 [0.00000000e+00 1.70245148e+03 4.85183754e+02]<br>
 [0.00000000e+00 0.00000000e+00 1.00000000e+00]]<br>
* Distortion coefficient (k1, k2, p1, p2, k3, ...) = [ 0.12038199, -0.19289355, -0.02137884,  0.0073491,   0.1622757 ]

<br><br><br>

- 렌즈 왜곡 보정 수행 (사용 코드 : distortion_correction.py)
<br>
[렌즈 왜곡 보정된 화면]
![distortion](https://github.com/HLife15/CV_Chess_Board/assets/162321808/0fad8891-0d1c-4713-9c02-2b8b89d217c4)
<br><br>
[TAB키를 눌러 렌즈 왜곡 보정 해제한 화면]
![original](https://github.com/HLife15/CV_Chess_Board/assets/162321808/b8a6d0e4-2f4c-4561-bd44-be8136bf776e)
