#include<stdio.h>

int main(){
    
    int num, repeat;
    
    char word[100];
    
    printf("ENTER WORD YOU WANT TO REPEAT: ");
    scanf("%s", word);
    
    printf(" Repeating : ");
    scanf("%d", &num);
    
    for( repeat = 1 ; repeat <= num ; repeat++ ){
    printf(" %d. %s\n",repeat, word );
    }   
    
    return 0;
}
