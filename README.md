# Web-Synology-NAS
Synology NAS Docker에서 구동되는 repository입니다.

# Synology Docker Code-Server에서 nodeJS, npm module 설치하기
  1. Docker에서 Code-Server를 구동한다.
  2. Code-Server 설정의 터미널로 이동한다.
  3. 생성 버튼을 클릭하고 bash를 open한다.
  <img width="1440" alt="image" src="https://user-images.githubusercontent.com/104338516/169701857-e68dfef8-cf99-4c82-9293-8810eca120b4.png">
  4. sudo apt-get update를 입력한다. (금방 끝난다)
  5. sudo apt-get install nodejs를 입력한다. (금방 끝난다)
  6. sudo apt-get install npm을 입력한다. (오래걸린다. 30분이상)
  7. nodejs -v를 통해 버전을 확인한다.
  8. npm -v를 통해 버전을 확인한다.
  <img width="1440" alt="image" src="https://user-images.githubusercontent.com/104338516/169701939-55c562d4-074e-4921-b4cf-f6378a59f168.png">
  9. code-server의 VSCode에서 npm init 정상 작동 확인
  <img width="1440" alt="image" src="https://user-images.githubusercontent.com/104338516/169702124-59076630-fe14-4b20-b094-dc01964aec9a.png">
