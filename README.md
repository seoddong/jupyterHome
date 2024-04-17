# jupyterHome
jupyter notebook 서버를 띄울 경우 소스 동기화를 위한 repo.<br>
root 경로에서 jupyter notebook --allow-root로 서버를 띄우고<br>
root에서 git clone 했다면 jupyterHome = /root/jupyterHome이 된다.

## .gitignore
env 폴더의 .env 파일에는 개인적인 설정이 포함되므로 동기화 제외
