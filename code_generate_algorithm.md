# 代码生成算法

若三地址语句是 `x:= y op z`

若三地址语句是 `x:= op y`

若三地址语句是 `x:= y` 

- 若y的值在R中,更新R的寄存器描述器和x的地址描述器

- 若y在存储器My中,

- 若X无下次引用,生成指令 `MOV my,mx` ,更新x的地址



 



#### 为条件语句生成目标代码