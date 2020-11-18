

#include <iostream>
#include <string>


using namespace std;


int main()                                                            //main function
{
	int arrays[10] = { 1,5,8,9,11,15,25,35,45,50 };
	int frontIndex, rearIndex;
	int selectingNumber;//9
	cin >> selectingNumber;
	frontIndex = size(arrays) / 2;//8 - 2
	rearIndex = size(arrays) - 1;//10 - 4
	int counter = 0;
	if (arrays[frontIndex] == selectingNumber || arrays[rearIndex] == selectingNumber) {
		cout << "Found it!!";

	}
	else {

		for (int i = 0; i < size(arrays); i++)
		{


			if (selectingNumber < arrays[frontIndex])  
			{
				rearIndex = frontIndex; //8 - 2 
				frontIndex = rearIndex / 2;//5 - 1
			}
			else if (selectingNumber > arrays[frontIndex])
			{
				int value = frontIndex;
				frontIndex += (rearIndex - frontIndex) / 2;
				if (value == frontIndex) {
					break;
				}
			}
			else if (selectingNumber == arrays[frontIndex])
			{
				cout << "\nFound it!";
				counter++;
				break;
			}
			cout << "\n------";
		}
		if (counter == 0) {
			cout << "\nDidn't find it!!";
		}
	}



}



