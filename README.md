# Multi

## 실행 결과

1.
![cap1](./img/cap1.PNG)

첫 화면입니다.


2.
![cap2](./img/cap2.PNG)

Find Maximum 을 실행합니다.

Find Maximum 을 실행하게 되면

내부에 선언되어 있는 Array 배열에서

가장 큰 값을 찾아내어 출력합니다.

3.
![cap3](./img/cap3.PNG)

1,2,3,4,5 중 가장 큰 값인 5를 찾아낸 모습입니다.





--------------------------------------------------------------------------------------------
1.
![code1](./img/code1.PNG)

MultiView.h에 정수 배열 5개의 정수와 

HWND를 가지는 구조체를 정의 합니다.


![code2](./img/code2.PNG)

메뉴를 선택하면 쓰레드가 시작이 되고

구조체 속 정수 배열에 1,2,3,4,5를 넣고

HWND에는 현재의 윈도우 m_hWnd 저장시킵니다.

또한 ThreadProcedure 함수를 호출 합니다. 데이터는 data에 전달됩니다.



![code3](./img/code3.PNG)

최댓값을 찾고 WM_MAX를 발생시킵니다.


![code4](./img/code4.PNG)

WM_MAX가 발생하면 OnMaxFound 함수를 발생시킵니다.

![code5](./img/code5.PNG)

data값의 최댓값을 출력합니다.

