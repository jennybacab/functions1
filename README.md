## functions1

# create a function that receives a string and print the inverted string, remember that to print an element i you can use printf("%c",string[i]); 

#include <stdio.h>

#include<string.h>


void OnlyConsonants (char userInput[30]){

	int i;
  
	int largo = strlen(userInput);
  
	for(i=0; i<=largo; i++){
  
		if (userInput[i]!= 'a' && userInput[i]!= 'e' && userInput[i]!= 'i' && userInput[i]!= 'o' && userInput[i]!= 'u'){
    
			printf("%c",userInput[i]);
      
		} 
    
		}
    
	}
  

int main(void) {

	char userInput[30];
  
	scanf("%s", &userInput);
  
	OnlyConsonants(userInput);
  
	return 0;
  
}
