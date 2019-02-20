<Lesson 2.1> - 삭제 명령
----------------------

dw - 단어 삭제 (커서 위치에서 단어 끝까지)  

[메밀꽃 필 무렵 원본]  
![_](https://user-images.githubusercontent.com/17330864/53071283-1aba7480-3525-11e9-8dc3-5b335fdb27c5.png)  
[dw 명령어]  
![_dw](https://user-images.githubusercontent.com/17330864/53071306-2d34ae00-3525-11e9-8bea-d015f056046a.png)


<Lesson 2.2> - 다른 삭제 명령
--------------------------
d$ - 줄 삭제 (커서 위치에서 줄 끝까지)  

[메밀꽃 필 무렵 원본]  
![_](https://user-images.githubusercontent.com/17330864/53071283-1aba7480-3525-11e9-8dc3-5b335fdb27c5.png)  
[d$ 명령어]  
![_d](https://user-images.githubusercontent.com/17330864/53071552-e4c9c000-3525-11e9-8bb9-99aa6a3831fb.png)  

<Lesson 2.3> - 명령 및 적용 대상에 대해
-----------------------------------
삭제 명령의 형식:

    [횟수] [명령] [대상] or [명령] [횟수] [대상]

* [횟수] - 명령을 몇번 처리할 것인가 // [횟수]가 없으면 1번 처리됨
* [명령] - 어떤 명령을 내릴 것인가 // 삭제 - d 
* [대상] - 명령이 동작할 대상 // w - 단어 , $ - 줄의 끝

ex) 2dw , d$ 등등  

[메밀꽃 필 무렵 원본]  
![_](https://user-images.githubusercontent.com/17330864/53071283-1aba7480-3525-11e9-8dc3-5b335fdb27c5.png)  
[2dw 명령어]  
![2dw](https://user-images.githubusercontent.com/17330864/53071649-265a6b00-3526-11e9-8849-93c15a91719a.png)  

<Lesson 2.4> - 줄 전체 삭제 명령
-----------------------------
dd - 줄 전체 삭제 (삭제 된 후 다음 줄로 이동함) 


[메밀꽃 필 무렵 원본]  - 10번 줄 참고 -
![05 - 2](https://user-images.githubusercontent.com/17330864/53071831-b13b6580-3526-11e9-857e-ad886fe82ed9.png)  
[dd 명령어]  
![06 - dd](https://user-images.githubusercontent.com/17330864/53071832-b13b6580-3526-11e9-8362-43a6bd624cf1.png)  


<Lesson 2.5> - 취소 명령
---------------------- 
u - 이전 행동 취소  
U - 한 줄에서 취소한 거 모두 취소  
Ctrl + R - 취소한 거 다시 실행  


[메밀꽃 필 무렵 원본]  
![_](https://user-images.githubusercontent.com/17330864/53071283-1aba7480-3525-11e9-8dc3-5b335fdb27c5.png)  
[수정본] - dw 명령어 2번 씀 -  
![1](https://user-images.githubusercontent.com/17330864/53072125-92899e80-3527-11e9-8cca-b08518ced3ff.png)  
[수정본에서 u 명령어 썼을 때]  
![u](https://user-images.githubusercontent.com/17330864/53072381-49861a00-3528-11e9-80ce-34aff3ace460.png)  
[수정본에서 U 명령어 썼을 때]  
![u](https://user-images.githubusercontent.com/17330864/53072382-4b4fdd80-3528-11e9-9b3c-3d1bc27570b4.png)  

*Ctrl + R의 경우 명령을 한번 내리기 전으로 돌아간다.
