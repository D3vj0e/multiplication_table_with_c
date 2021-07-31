# Multiplication table with c
## โปรแกรมสูตรคูณ

# Code
```markdown
#include <stdio.h>
#include <stdbool.h>
#include <stdlib.h>
//สูตรคูณ
int main(){
	int num_input;
	while(true){
		printf("\nยินดีต้อนรับสู่โปรแกรมสูตนคูณ by D3vj0e\n");
		printf("ถ้าต้องการออกให้กด Ctrl + c\n");
		printf("ใส่ตัวเลขที่ต้องการ : ");
		scanf("%d",&num_input);
		for(int i = 1; num_input != 0;i++){
			printf("\n%d x %d = %d",num_input,i,num_input*i);
			if(i == 12){
				break;
			}
		} 
	}
	return(0);
}

```
สามารถนำไปศึกษาเต็มที่เลยครับ หรือกดโหลดด้านบนได้เลยครับ(ต้องเอาไป complied ก่อนนะครับ)
