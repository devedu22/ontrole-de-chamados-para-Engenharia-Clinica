# ontrole-de-chamados-para-Engenharia-Clinica
Projeto com o objetivo de facilicitar a abertura dechamados da Engenharia Clinica do Hospital

#include<stdio.h>
#include<stdlib.h>
#include<conio.h>
#include<locale.h>

main(){
	 setlocale(LC_ALL, "Portuguese");
	char req[99];
	char setor[30];
	char solicitante[30];
	int ramal,i;

	printf("SEJA BEM-VINDO(A) AO CONTROLE DE REQUISIÇÕES - CCO\n");
	printf("******************\n");
	printf("PROJETO IDEALIZADO POR: EDUARDO CAVALCANTE - CCO\n");
	printf("******************\n");
		printf("Objetivo: Otimizar o preenchimento das solicitações (ENGENHARIA CLÍNICA)\n");
		printf("para o Sistema NEOVERO.\n");
	printf("******************\n");
	printf("PARA INICIAR, DIGITE OS DADOS SOLICITADOS ABAIXO:");
	printf("\n******************\n");
	
    setlocale(LC_ALL, "Portuguese");
	

	while(ramal,i<99){
	i=i+1;
	 printf("\n PRESCRIÇÃO DA PROBLEMÁTICA DO EQUIPAMENTO:");
      fflush(stdin);
      gets(req);
    

	 printf("\n - SOLICITANTE:");
	 gets(solicitante);
     fflush(stdin);
    

	 printf("\n - RAMAL PARA CONTATO:");
	 scanf("%d",&ramal);

 	
 	 printf("\nREQUISIÇÃO DO EQUIPAMENTO: %s - ", req);

	 printf("SOLICITANTE: %s - ", solicitante);
	 printf("RAMAL PARA CONTATO:  %d  \n ", ramal);

 }


 getch();
 system("pause");
 
}
