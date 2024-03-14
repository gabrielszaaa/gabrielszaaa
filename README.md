#include<stdio.h>
#include<stdlib.h>
#include<locale.h>
#include<ctype.h>
#include<string.h>

void questao1(),questao2(),questao5(),questao8()


int main(){
	setlocale(LC_ALL,"portuguese")
	int option;
	
	do{
		printf("\t\t\t#########################\n");
		printf("\t\t\t## EXERCÍCIOS- ANEXO 08##\n");
		printf("\t\t\t#########################\n");
		
		printf("1- questao 1");
		printf("2- questao 2\n");
		printf("3- questao 5\n");
		printf("4- questao 8\n");
		printf("0-sair\n");
		scanf("d%",&option)
		
		
		system("cls");
		
		switch(option)
		   
		   case '1':
		   	    questao1();
		   	   
				  
				break
		   	   
		   	   
		   case '2':
		   	    questao2();
				  
				break
				
				
		   case '3':
		   	    questao5();
				  
				break
				
				
		   case '4':
		   	    questao8();
				  
				break
				
				
				
           case '0':
           	    abort();
		   	    break
		   defalt:
		      printf("opcao invalida!")					
		   				
		
	} while(option!=0) 
	
}
