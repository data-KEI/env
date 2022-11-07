- xlrd로 xlsx 파일을 열 수 없을 때는
~~~
XLRDError: Excel xlsx file; not supported
~~~
~~~
> conda install openpyxl

pd.__version__
'1.1.5' <- 1.0.1 이상 사용 중인지 확인!!!

df = pd.read_excel('[파일경로+파일명].xlsx', engine='openpyxl')
~~~
