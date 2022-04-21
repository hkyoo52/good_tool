* 서버에서 사용할 때 이용
* 서버를 내가 끄고 자도 서버가 알아서 돌아감
* 내가 wifi 없는 곳을 가도 서버는 알아서 돌아감




#### 설치 방법
```python
sudo apt-get install tmux
```

#### tmux session 생성
```python
tmux new -s $session_name
```

#### 기존 session 들어가기
```python
tmux attach -t $session_name
```

#### 현재 존재하는 session 보기
```python
tmux ls
```





참고자료
https://tootouch.notion.site/tmux-2bec4d2c870e4451a9b6babae3dda15d
