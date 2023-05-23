# Open Source SW개론 과제 20233168 이상빈
+ **top**

  *table of processes* 의 약자로 **시스템의 프로세스/메모리의 사용 현황을 실시간으로 모니터링** 하여 디바이스의 성능을 체크하는 명령어. 

     + *shift + p* : ***CPU 사용률*** 이 높은 프로세스 순서대로 표시

     + *shift + m* : ***메모리 사용률*** 이 높은 프로세스 순서대로 표시

     + *shift + t* : ***프로세스가 돌아가고 있는 시간***  순서대로 표시

     + *-k* : ***프로세스  kill  - k 입력 후 종료할 PID 입력***  signal을 입력하라고 하면 kill signal인 9를 입력

     + *-a* : ***메모리 사용량*** 에 따라 정렬

     + *-b* : ***Batch 모드***  작동

     + *-c* : ***명령행/프로그램 이름 토글***

     + *1* : ***CPU Core별로 사용량*** 을 보여줌
  
-------
 - **ps**

     **실행중인 프로세스에 대한 정보** 를 표시함
 
    - *-e* : ***모든 프로세스에 대한 내용*** 을 보여줌

    - *-f* : ***프로세스에 대한 자세한 정보*** 를 출력한다(PPID, UID를 확인 가능함)

    - *-u [username]* : ***특정 사용자에 대한 프로세스의 정보*** 를 출력함

    - *a* : ***다른 사용자의 프로세스*** 를 출력함

    - *u* : ***프로세스 소유자의 이름, CPU 사용량, 메모리 사용량*** 등을 출력함

    ![image](https://github.com/kingsiuness12/hellowood12/assets/133829859/1b587406-d85a-4286-a0ab-0d7d88533a94)
    
    
    - *x* : ***사용자가 로그아웃 한 이후에도 실행중인 모든 프로세스*** 를 출력함

       ![image](https://github.com/kingsiuness12/hellowood12/assets/133829859/918d4bdc-eb12-470b-9a52-47d8bf6588ab)




      > ps -ef를 grep과 같이 이용하여  ***ps -ef | grep [프로세스명]***  을 이용하여 실행중인 프러세스를 확인하는 용도로 가장 많이 사용한다고 함

      > PID를 확인 할 수 있기 때문에 ps -ef로 프로세스명을 확인하고 kill명령어를 이용해 해당 프로세스를 종료시킨다고 함




  
------------------
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
```c
#include <stdio.h>

int main(void){
}
```
+ string
- string
* string
 
*나_*나_*나_
<img width="897" alt="sk텔레콤" src="https://github.com/kingsiuness12/hellowood12/assets/133829859/54f10a41-738d-4abd-9f43-549e06e64aee">

