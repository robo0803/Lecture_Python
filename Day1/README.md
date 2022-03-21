Python 1일차


# 1. 환경


폰노이만 아키텍처
 - https://t1.daumcdn.net/cfile/tistory/2428C73B568D36FC3A
 - 

## 활용분야

CRM
 - https://cdnsite.agilecrm.com/img/info-graphic.svg

SCM
 - https://st4.depositphotos.com/13159112/21885/v/1600/depositphotos_218853972-stock-illustration-scm-supply-chain-management-concep.jpg


ERP
 - https://leadersmt.net/wp-content/uploads/2021/09/erp-system.png


Big Data
 - https://www.selecthub.com/wp-content/uploads/2020/03/BA-Life-Cycle-1024x1024.png
 - https://www.saytekinc.com/img/big-data.png


---

KOCW / edwith
 - https://www.edwith.org/


# 2. conda 연습


1. PythonLecture 가상환경 제거!!!
2. PythonLecture 가상환경 생성
  - Python=3.9
3. Jupyter-lab 설치

4. Jupyter-lab 실행 : 디렉토리 필요(루트)
  - HOME/Works

참고 conda 명령

```
(base)> conda remove –n 이름 --all
(base)> conda env list
(base)> conda create –n PythonLecture python=3.9
(base)>
(base)> conda install jupyterlab
(base)> dir Works
(base)> jupyter-lab --no-browser Works
```
