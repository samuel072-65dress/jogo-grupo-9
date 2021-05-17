# jogo-grupo-9

#include <stdio.h>
#include <stdlib.h>
int sair()
{
 printf("============================\n");
 printf("vc encerrou o jogo.\n");
 printf("============================\n");
}
int fim()
{
   printf("============================\n");
   printf("        FIM DE JOGO.\n");
   printf("============================\n");
}

int main()

{
    int n,n2,n3,n4,n5;

    printf("voce e jack um cientista que inventou uma maquina do tempo,\ne como qualquer outro cientista resolveu usar sua criacao:\n");
    printf("========================================\n");
    do{
    printf("digite 0- se gostaria de sair do jogo\ndigite 1- se gostaria de ir para 473 d.C.\ndigite 2- se gostaria de ir para 2800 a.C.\ndigite 3- se gostaria de ir para 1690 d.C.\n");
    printf("========================================\n");
    scanf("%d",&n);

    switch(n){
    case 0:
        sair();
        return 0;
        break;
    case 1:
    printf("vc escolheu 473 d.C.\n");
    break;
    case 2:
    printf("vc escolheu 2800 a.C. porem deu algum problema na maquina e vc acabou indo para 473 d.C.\n");
    break;
    case 3:
    printf("vc escolheu 1690 d.C. porem deu algum problema na maquina e vc acabou indo para 473 d.C.\n");
    break;
    default:
        printf("escolha 0,1,2 ou 3\n");
    }
    }while ((((n != 0) && (n != 1) && (n != 2) && (n != 3))));
    printf("================================\n");
    printf("================================\n");
    printf("vc chegou em roma no ano 473,\nao descer da maquina vc foi para a cidade mais proxima ,mystras,\ne chegando la vc ...\n");
    printf("================================\n");
do {
    printf("digite:\n0- para sair do jogo\n1-foi para o bar\n2-andou na rua para conhecer os lugares\n");
    printf("================================\n");
    scanf("%d",&n2);
    switch(n2) {
    case 0:
        sair();
        return 0;
        break;
case 1:
    printf("ao chegar no bar um bebado te atacou oque voce vai fazer?\n");
    do {
    printf("digite:\n0- sair do jogo\n1-fugir\n2-atacar de volta\n");
    scanf("%d",&n3);
    switch(n3){
    case 0:
        sair ();
        return 0;
        break;
case 1:
    printf("vc fugiu, mais o bebado te seguiu ate um beco com os amigos\n e la ele te deram uma surra e roubaram sua coisas\nentre elas a chave da maquina do tempo.\n");
    printf("voce pssou anos tentando encontrar o bebado para conseguir recuperar a chave,\nmais quando finalmente vc o encontro ele já tinha jogado fora a chave,\ne vc acabou ficando preso no passado\n ");
    printf("acho que o bar nao foi uma boa opcao!\n");
     fim();
    return 0;
    break;
case 2:
    printf("voces brigaram e no meio da luta\nvc o empurro e ele caiu de cabeça numa mesa,\nlevandou a morte.\ncomo ele era um cidadão romano vc foi condanado a morte.\n");
    printf("lutar nem sempre he a solucao, voce morreu\n");
    fim();
    return 0;
     break;
     default:
        printf("escolha 0,1 ou 2\n");
    }
    }while (((n2 != 0) && (n2 != 1) && (n2 != 2)));


case 2:
   printf("entao voce escolheu conhecer alguns lugares...\n");
    printf("para qual lugar você quer ir?\n");
    default:
        printf("escolha 0,1 ou 2\n");
    }
    }while (((n2 != 0) && (n2 != 1) && (n2 != 2)));

do{
printf("digite:\n0- sair do jogo.\n1- Museu.\n2- Padaria.\n3- Igreja.\n4- Parque.\n5- Vinícola.\n ");
    scanf("%d", &n4);
    switch(n4){
    case 0:
      sair();
        return 0;
        break;
case 1:
	printf ("vc escolheu ir ao museu\n");
	printf ("nesse museu a muitas pinturas e obras interessantes para você conhecer.\n");
	break;
case 2:
	printf ("vc escolheu ir a padaria\n");
	printf ("está com fome, peça algo para comer, aqui tem várias variades de salgados e doces para voce.\n");
	break;
case 3:
	printf ("vc escolheu ir a igreja\n");
	printf ("esta igreja e uma das mais bonitas da região e muitas pessoas veem aqui para rezar.\n");
	break;
case 4:
	printf ("vc escolheu ir ao parque\n");
	printf ("esse parque possui bastante espaço para as pessoas virem aqui e se divertirem ou apenas dar uma caminhada e relaxar.\n");
	break;
case 5:
	printf ("vc escolheu ir a uma vinicola\n");
	printf ("aqui nessa cidade esta vinicola e uma das maiores que existem, muitas pessoas veem aqui para comprarem vinho diretamente daqui.\n");
	break;
	default:
        printf("escolha 0,1,2,3,4,5\n");
    }
 }while (((((n4 != 0) && (n4 != 1) && (n4 != 2) && (n4 != 3) && (n4 != 4) && (n4 != 5)))));
	printf("====================================================\n");
	printf ("Agora que você conheceu alguns lugares dessa cidade,\nvocê quer ir para alguma outra cidade ou terminar por aqui?\n");
	printf("====================================================\n");
do{
        printf ("digite 0- sair do jogo.\ndigite 1- conhecer outra cidade.\ndigite 2- acabar a história.\n");
	scanf ("%d", &n5);
	switch (n5){
    case 0:
      sair();
        return 0;
        break;
case 1:
	printf ("Voce escolheu outra cidade, porem esta parte do jogo so será liberada em uma versao futura\n");
	printf ("Agora que voce ja se aventurou pela cidade e conheceu lugares a história termina aqui.\n");
	printf ("Encontre sua maquina do tempo e volte para a casa.\n");
	fim();
	break;
case 2:
	printf ("Você escolheu terminar a história por aqui.\nentão ache a sua maquina do tempo e volte para a casa.\n");

	fim();
        break;
        default:
        printf("escolha 0,1 ou 2\n");
	}
	}while ((n5 != 1) && (n5 != 2));

	return 0;
}

    
