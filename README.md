## scp.client.exe

배경 : 집에서 편하게 scp을 날리기 위해 제작 <br>

필요 세팅 : 대상의 고정 IP 설정

### 사용법

1. 해당 파일 다운로드 압축 해제
2. scp_client/dist/main.exe 실행
3. 윈도우 경고 허용
4. 연결정보 입력 
5. 파일 추가
6. 시작 => 해당 연결 정보로 파일 전송

![1](https://user-images.githubusercontent.com/30226433/145715337-c13c9e37-b22e-49f9-9359-76a3b32117c6.JPG)
![4](https://user-images.githubusercontent.com/30226433/145715423-60bff9a9-d3f5-4ad1-beb6-7bc0d34699d4.JPG)
<br>대상 pc 바탕화면<br>
<img width="220" alt="6" src="https://user-images.githubusercontent.com/30226433/145715740-03f967b1-cb01-4610-855b-de53f386cf45.png">

<hr>

발견된 버그

- 2021/12/12 : exe 파일로 만들 경우 리모트 정보가 파일로 저장은 잘되나 읽어지지가 않음 <br/>
- 2021/12/12 : 연결정보 없이 실행됨
