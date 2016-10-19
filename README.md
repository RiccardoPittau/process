# process programmi per tps
#include <iostream>
#include <unistd.h>

int main(void){
	int number;
	std:: cout <<"L'ID del processo e' " << getpid() << std::endl;
	std::cin>>number;
    return 0;
}
