# zlczh
自动生成无机材料的化学式

(ChenZhihao,待完善)


# 从python库下载pip安装

!pip install zlczh

# 例如(example)：

!pip install zlczh

from zlczh import autoin as pc

a = ['K','Rb']#'Sc','MA','FA','CA','GU','PEA'

b = ['Pb','Sn']#,'Bi'

c = ['Cl','Br']#,'I'

pc.predictioinclass(a,b,c,0.1,"outt.csv")
