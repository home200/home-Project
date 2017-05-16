/*This is a simple swap sort algorithm which uses swap to sort and filter and array*/

#include <iostream>
#include <cstdlib>
#include <ctime>
#define msg cout<<
#define end cout<<endl;

using namespace std;

//Random seeding of number to array container
void Randinit(int arr[], int siz){
				srand(time(NULL));
				for (int r=0; r<siz; ++r)
				   arr[r]=rand()%50+1;			   	
}

//Function to display the element in array
void DisplayA(int arr[], int siz){
				for (int d=0; d<siz; ++d)
				   msg *(arr++)<<" "; //pointer pointing to each position in an array with +1 to move to next position. 
}


//The swap function algorithm
void SwapFunc(int *num1, int *num2){
				int temp;
				temp=*num1;
				*num1=*num2;
				*num2=temp;
}

//Exchange Sort function, main engine to check for sorting order.
void ExchSoRT(int arr[], int siz){
				for (int i=0; i<siz; ++i){
				    for (int k=1; k<siz; ++k){
				         if(arr[k-1]>arr[k]){
				        SwapFunc(&arr[k-1], &arr[k]);
																}
												}
								}
}

//Main body of the program.
int main(){
				const int siz=104;
      int arry[siz];
				Randinit(arry, siz);
				msg "Random-Seed Display";
				end
				DisplayA(arry, siz);
				end
				ExchSoRT(arry, siz);
				msg "Sorted Numbers";
				end
				DisplayA(arry, siz);
}
