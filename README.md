# data_pipeline
class practice

1. 直接在vscode裡執行:
command+shift+p
搜尋 dev Containers: Rebuild and Reopen in Container


2. 在執行 p_02_ptt.ipynb / ptt_flow.py 之前先在終端執行以下取得res_gossiping資料：
wget -O /tmp/course-datamining.zip https://github.com/uuboyscy/course-datamining/archive/refs/heads/master.zip
unzip /tmp/course-datamining.zip -d /tmp/
cp -r /tmp/course-datamining-master/module_06_Pandas_basis/res_gossiping ./

3. resource放進 .gitignore, holding.csv請自行下載, 其他數據如下:

data with_nan.csv:
'''
col1,col2,col3
test1,13,
test2,44,aaa
test3,,
,,
test5,,bbb
,,
'''


data with dtype_sampe.csv:
 '''
 Name,Experience,Age,Department,DepartmentID,CreatedDatetime,CreatedDatetimeTZ,Remote,OnBoard,Intern
John Doe,10,35,Engineering,001,2023-04-05T14:30,2023-04-05T14:30+08:00,true,V,0
Jane Smith,,29,Marketing,002,2023-02-28T08:15,2023-02-28T08:15+08:00,false,X,0
Emily Davis,2,27,Product,003,2023-03-15T12:45,2023-03-15T12:45+08:00,True,V,0
Mark Evans,5,30,Sales,004,2023-01-13T09:00,2023-01-13T09:00+08:00,FALSE,V,1
 '''