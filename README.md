# PRograma-basico-em-C
Usando switch case
int main()
{
    printf("decida o que o avião ira realizar\n");
    int comando = 2;
    switch(comando){
        case 1:
        printf("o aviao ira decolar\n");
        break; //eu coloco o break pois se essa condição for 
        //verdadeira ele nao pule para o proximo ele saia da linha de comando
        
        case 2:
        printf("o aviao ira descer");
        break;
        
        case 3:
        printf("o aviao desligara o motor");
        break;
        
        case 4:
        printf("o aviao ligara o motor");
        break;
    }
    
    return 0;
    