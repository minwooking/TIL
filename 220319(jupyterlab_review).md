<<<<<<< HEAD
# Jupyter lab use
## extension
1. kite
    1-1 사용후기
        ㅇ vscode 를 대체 할 만 한 자동완성 기능을 보여줘서 만족 스러웠음
    1-2 사용방법
        ㅇ pip install 을 통해서 설치하면 되고 lab 3.0 버전과 2.0 버전이 달랐다.
        ㅇ 주의할점 not runing 이라고 나와도 그냥 쓰면 된다. 계속 없애려고 노력했으나 그냥 쓰면 된다는걸 깨달았다.
        ㅇ pro 버전의 장점이 뭔지는 모르겠지만 충붆디 사용가능함
2. subline

- 1-1 사용후기<br>
       ㅇ vscdoe 를 대체하기 위한 ctrl + D 기능을 쓸 수 있어서 굉장히 좋았음

- 1-2 사용방법<br>
        ㅇ pip install 을 통해서 설치하면 된다.

3. git 
    - 1-1 사용후기<br>
            ㅇ 어떠한 이유에선지 몰라도 그대로 설치해도 계속 꼬여서 심하게 고생을했고 지금은 해결했다.
            ㅇ 구글크롬 기준에서 토큰을 저장시켜놓고 쓰니까 굉장히 편했다.
    - 1-2 사용방법<br>
            ㅇ installed server extension and lab extension checking!
            ㅇ 버전이 한번 꼬여버려서 굉장히 고생했던거 같다.
4. excute time 
    - 1-1 사용후기<br>
            ㅇ  vscode 를 대체하기 위하여 excute time 을 설치하려고 labextension탭에서 설치하려했으나 오류가 나왔다. 
            ㅇ 열심히 구글링을 해보니 새로운 설치방법이 있었고 정상적으로 작동하고 있다.
    - 1-2 사용방법<br>
            ㅇ 설치시 CLI 에서 설치를 해야한다.
5. RAM monior 
    - 1-1 사용후기<br>
            ㅇ 얼마나 RAM을 쓰는지 확인 할 수 있어서 나중에 딥러닝 사용 시 큰 도움이 될 꺼같다.
    - 1-2 사용방법<br>
            ㅇ 위와 동으로 CLI 통해서 설치를 했다.

## 참고 사항
1. lsp
    - 1-1 사용후기<br>
            ㅇ 그대로 설치하고 사용하였으나 무엇때문인지 몰라도 오류가 나와서 사용을 안하고 있다
            ㅇ kite로 정착하는 계기가 되었다
2. tabnine 
    - 1-1 사용후기<br>
            ㅇ 사용방법 그대로 설치하고 사용하였으나 사용이 제대로 되지 않았다
            ㅇ 무엇때문인지는 모르겠지만 현재는 lab 최신버전에 지원을 안하는 거같다. 
            ㅇ kite로 정착하게 되었다.
## 그 외 추가사항
1. 구글 드라이브
    ㅇ 구글드라이브를 lab extension 에 직접 설치 해서하는 방법도 있으나 액세스 토큰을 받고 동기화 하는게 귀찮아서 다른 방법을 했다.
    ㅇ 구글드라이브를 리눅스 서버 자체에 마운트 시키고 그 마운트 폴더를 jupyter lab WorkSpace 자체에 넣어버리면 따로 구글 드라이브와 연동하지 않아도 정상작동했다.
2. vscode 자체에 jupyter.server를 연결
    ㅇ vsvode's autocompile and powerful extension is very butiful and so I used vscode
    ㅇ window 라서 pwd,ls 등등 매직 명령어 사용시 한글이 깨져서 나오는게 나한테 너무 큰 단점이 되고 있었다.
    ㅇ 그래서 연산 자체를 ipykernel 을 통해 서버에서 하는 방식으로 바꿔서 해봤다.
    ㅇ 서버에 접속해서 노트북을 접속해서 하다 보니 여러 장점들이 있었다.
        장점
            - linux base Server 라서 pwd 나 ls 등등 매직 명령어 사용시 글자가 깨지지 않아서 명령어 활용이 굉장히 좋았다
            - ! 를 통한 명령어 도 편하게 사용 할 수 있다
            -  서버를 통해 연산하기 때문에 노트북에 큰 과부하가 안걸리는거 같다. cpu 를 확실히 사용안하는건 맞지만 RAM 사용량이 상당하다
            -  커널을 사용하고 있어도 local base를 이용하여 Crawling 이나 러닝 등  돌릴 수 있다는게 장점이다.
        단점
            - 저장 공간이 서버 기준이기 때문에 헷갈릴 수도 있다. 예를들면 pwd 시 윈도우 지만 서버로 나오기 때문에 따로 SFTP 를 연결해서 써야한다.

## jupyter lab
1. review
- 주피터랩을 config.py 파일을 통해서 ip,port,password 등등을 직접 설정해서 사용했는데 정말 편리하고 강력했다.
- 사용하는 램도 적었고 안정성도 높다.
- 확실히 주피터랩 을 이용해서 사용하는게 굉장히 편한거같다.
- 서버에 투자해서 고성능의 랩을 만들고 노트북의 휴대성을 증대 시키면 좋을꺼같다 gram 이나 가벼운 노트북 등등
## SFTP
- 간단한 config 을 통해서 stfp 에 접속하여 파일 관리가 가능하다.
- vscode 를 통해서 사용하고 있는데 정말 굉장히 편하다
- 여러 용도로 활용가능할것으로 보인다.
- 처음에 config 시 주소에  DDNS 를 넣을때 포트와 같이 넣어버리는 실수를 했다.
- ID와 PW를 linux id 와 pw 를 써야 하는거같다.




## 결론
    위에서 말한 extension을 우선적으로 설치하여 사용하면 정말 vscode를 대체 할 수 있을 정도로 사용 가능하다고 느꼈다.
     vs code vs jupyter lab 은 아직 대결 중이지만 둘을 활용하면 혼자서 큰 효율을 낼 수 있을것같다.
=======
# Jupyter lab use
## extension
1. kite
    1-1 사용후기
        ㅇ vscode 를 대체 할 만 한 자동완성 기능을 보여줘서 만족 스러웠음
    1-2 사용방법
        ㅇ pip install 을 통해서 설치하면 되고 lab 3.0 버전과 2.0 버전이 달랐다.
        ㅇ 주의할점 not runing 이라고 나와도 그냥 쓰면 된다. 계속 없애려고 노력했으나 그냥 쓰면 된다는걸 깨달았다.
        ㅇ pro 버전의 장점이 뭔지는 모르겠지만 충붆디 사용가능함
2. subline

- 1-1 사용후기<br>
       ㅇ vscdoe 를 대체하기 위한 ctrl + D 기능을 쓸 수 있어서 굉장히 좋았음

- 1-2 사용방법<br>
        ㅇ pip install 을 통해서 설치하면 된다.

3. git 
    - 1-1 사용후기<br>
            ㅇ 어떠한 이유에선지 몰라도 그대로 설치해도 계속 꼬여서 심하게 고생을했고 지금은 해결했다.
            ㅇ 구글크롬 기준에서 토큰을 저장시켜놓고 쓰니까 굉장히 편했다.
    - 1-2 사용방법<br>
            ㅇ installed server extension and lab extension checking!
            ㅇ 버전이 한번 꼬여버려서 굉장히 고생했던거 같다.
4. excute time 
    - 1-1 사용후기<br>
            ㅇ  vscode 를 대체하기 위하여 excute time 을 설치하려고 labextension탭에서 설치하려했으나 오류가 나왔다. 
            ㅇ 열심히 구글링을 해보니 새로운 설치방법이 있었고 정상적으로 작동하고 있다.
    - 1-2 사용방법<br>
            ㅇ 설치시 CLI 에서 설치를 해야한다.
5. RAM monior 
    - 1-1 사용후기<br>
            ㅇ 얼마나 RAM을 쓰는지 확인 할 수 있어서 나중에 딥러닝 사용 시 큰 도움이 될 꺼같다.
    - 1-2 사용방법<br>
            ㅇ 위와 동으로 CLI 통해서 설치를 했다.

## 참고 사항
1. lsp
    - 1-1 사용후기<br>
            ㅇ 그대로 설치하고 사용하였으나 무엇때문인지 몰라도 오류가 나와서 사용을 안하고 있다
            ㅇ kite로 정착하는 계기가 되었다
2. tabnine 
    - 1-1 사용후기<br>
            ㅇ 사용방법 그대로 설치하고 사용하였으나 사용이 제대로 되지 않았다
            ㅇ 무엇때문인지는 모르겠지만 현재는 lab 최신버전에 지원을 안하는 거같다. 
            ㅇ kite로 정착하게 되었다.
## 그 외 추가사항
1. 구글 드라이브
    ㅇ 구글드라이브를 lab extension 에 직접 설치 해서하는 방법도 있으나 액세스 토큰을 받고 동기화 하는게 귀찮아서 다른 방법을 했다.
    ㅇ 구글드라이브를 리눅스 서버 자체에 마운트 시키고 그 마운트 폴더를 jupyter lab WorkSpace 자체에 넣어버리면 따로 구글 드라이브와 연동하지 않아도 정상작동했다.
2. vscode 자체에 jupyter.server를 연결
    ㅇ vsvode's autocompile and powerful extension is very butiful and so I used vscode
    ㅇ window 라서 pwd,ls 등등 매직 명령어 사용시 한글이 깨져서 나오는게 나한테 너무 큰 단점이 되고 있었다.
    ㅇ 그래서 연산 자체를 ipykernel 을 통해 서버에서 하는 방식으로 바꿔서 해봤다.
    ㅇ 서버에 접속해서 노트북을 접속해서 하다 보니 여러 장점들이 있었다.
        장점
            - linux base Server 라서 pwd 나 ls 등등 매직 명령어 사용시 글자가 깨지지 않아서 명령어 활용이 굉장히 좋았다
            - ! 를 통한 명령어 도 편하게 사용 할 수 있다
            -  서버를 통해 연산하기 때문에 노트북에 큰 과부하가 안걸리는거 같다. cpu 를 확실히 사용안하는건 맞지만 RAM 사용량이 상당하다
            -  커널을 사용하고 있어도 local base를 이용하여 Crawling 이나 러닝 등  돌릴 수 있다는게 장점이다.
        단점
            - 저장 공간이 서버 기준이기 때문에 헷갈릴 수도 있다. 예를들면 pwd 시 윈도우 지만 서버로 나오기 때문에 따로 SFTP 를 연결해서 써야한다.

## jupyter lab
1. review
- 주피터랩을 config.py 파일을 통해서 ip,port,password 등등을 직접 설정해서 사용했는데 정말 편리하고 강력했다.
- 사용하는 램도 적었고 안정성도 높다.
- 확실히 주피터랩 을 이용해서 사용하는게 굉장히 편한거같다.
- 서버에 투자해서 고성능의 랩을 만들고 노트북의 휴대성을 증대 시키면 좋을꺼같다 gram 이나 가벼운 노트북 등등
## SFTP
- 간단한 config 을 통해서 stfp 에 접속하여 파일 관리가 가능하다.
- vscode 를 통해서 사용하고 있는데 정말 굉장히 편하다
- 여러 용도로 활용가능할것으로 보인다.
- 처음에 config 시 주소에  DDNS 를 넣을때 포트와 같이 넣어버리는 실수를 했다.
- ID와 PW를 linux id 와 pw 를 써야 하는거같다.




## 결론
    위에서 말한 extension을 우선적으로 설치하여 사용하면 정말 vscode를 대체 할 수 있을 정도로 사용 가능하다고 느꼈다.
     vs code vs jupyter lab 은 아직 대결 중이지만 둘을 활용하면 혼자서 큰 효율을 낼 수 있을것같다.
>>>>>>> 3406375da18f5b3775d5bcee1a3fb8e8a46bb6ea
