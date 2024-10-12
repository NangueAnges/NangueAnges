#include<iostream>

double puissance(double x, int n);

long factoriel(int n);

double cosinus(double x, int n);

int main(int argc, char** argv){
	double x;
	int n;
	
	std::cout<<"entrer l'angle en radian:"<<std::endl;
	std::cin>>x;
	std::cout<<"entrer le nombre de termes pour le developpement limite"<<std::endl;
	std::cin>>n;
	double cos= cosinus(x,n);
	std::cout<<"cos de "<<x<<" :"<<cos<<std::endl;
	return 0;
	
}

double puissance(double x, int n){
	double resultat = 1;
	int i =1;
	for(i=1; i<=n; i++){
		resultat=resultat*x;
	}return resultat;
}

long factoriel(int n){
	long fact=1;
	int i;
	for(i=1; i<=n; i++){
	fact =fact*i;
	}
	return fact;
}

double cosinus(double x, int n){
	double cos=0;
	int i;
	for(i=0; i<=n; i++){
		cos=cos+ puissance(-1,i)* puissance(x,2*i)/factoriel(2*i);
	}
	return cos;
}

