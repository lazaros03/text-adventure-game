# text-adventure-game 
#include <iostream>
using namespace std;
int restart(int firstselection,int secondselection,int thirdselection,int fourthselection,int fifthselection,int sixthselection);
void sixthlevel(int firstselection,int secondselection,int thirdselection,int fourthselection,int fifthselection,int sixthselection)
{
	int y=0;
	cout<<"congratulations, you have reached the final level"<<endl;
	cout <<"after a while the police arrive and arrested the burglars, what are you doing?"<<endl;
	cout <<"press 1 you lose your mind and start burdening everyone with the carbine"<<endl;
	cout <<"press 2 you tell the truth and show them disapproving verses"<<endl;
	cout <<"press 3 you lose your mind and commit suicide"<<endl;
	cin >>sixthselection;
	switch(sixthselection){
		case 1: {
			cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y= restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 2:{
			cout << "you win.if you want to play again press 1 or press 2 to exit"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 3:{
		    cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		default: {
		sixthlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
		break;
	}
	}
}
void fifthlevel(int firstselection,int secondselection,int thirdselection,int fourthselection,int fifthselection,int sixthselection)
 {
 	int y=0;
 	cout<<"fifth level"<<endl;
 	cout <<"while you are in the loft they enter the room,what do you do?"<<endl;
	cout <<"press 1 you come out of the loft and shoot them with the carbine you found"<<endl;
	cout <<"press 2 you wait quietly until the police come"<<endl;
	cout <<"press 3 you come out of the loft and try to stab them"<<endl;
	cin >>fifthselection;
	switch(fifthselection){
		case 1:{
			cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 2:{
			sixthlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 3:{
		cout << "you lost.do you want to restart?"<<endl;
		cout << "press 1 for yes  and 2 for no"<<endl;
		y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		default: {
		fifthlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
		break;
	}
	}
}
void fourthlevel(int firstselection,int secondselection,int thirdselection,int fourthselection,int fifthselection,int sixthselection)
{
	int y=0;
	cout<<"fourth level"<<endl;
	cout <<"after you put the cameras to record video you hear them approaching the room,what do you do?"<<endl;
	cout <<"press 1 you cry for help"<<endl;
	cout <<"press 2 you go up to the hidden loft so that they do not see you"<<endl;
	cout <<"press 3 defend your self"<<endl;
	cin >>fourthselection;
	switch(fourthselection){
		case 1:{
			cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 2:{
			fifthlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 3:{
		    cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		default: {
		fourthlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
		break;
	}
	}
}
void thirdlevel(int firstselection,int secondselection,int thirdselection,int fourthselection,int fifthselection,int sixthselection)
{
	int y=0;
	cout<<"third level"<<endl;
	cout <<"while you're on the phone with the police, you hear them banging  on your door, what do you do?"<<endl;
	cout <<"press 1 you put your cameras on video so you can have proof afterwards"<<endl;
	cout <<"press 2 you're hiding under the bed"<<endl;
	cout<<"press 3 you're hiding in the closet "<<endl;
	cin >>thirdselection;
	switch(thirdselection){
		case 1:{
		fourthlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 2:{
			cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 3:{
		    cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		default: {
		thirdlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
		break;
	}
	}
}
void secondlevel(int firstselection,int secondselection,int thirdselection,int fourthselection,int fifthselection,int sixthselection)
{
	int y=0;
	cout<<"second level"<<endl;
	cout <<"through the cameras you see 3 people breaking into your house, what do you do?"<<endl;
	cout <<"press 1 take a knife from the kitchen"<<endl;
	cout <<"press 2 jump out the window"<<endl;
	cout <<"press 3 call the police"<<endl;
	cin >>secondselection;
	switch(secondselection){
		case 1:{
			cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 2:{
		    cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 3:{
			thirdlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		default: {
		secondlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
		break;
	}
	}
}
void firstlevel(int firstselection,int secondselection,int thirdselection,int fourthselection,int fifthselection,int sixthselection)
{   int y=0;
	cout <<"you wake up in the middle of the night because you hear your dogs barking loudly, what do you do?" <<endl;
	cout << "press 1 watch the cameras on your phone to see what's going on"<<endl;
	cout << "press 2 you shout loudly to quiet the dogs"<<endl;
	cout << "press 3 to turn on the lights in the room"<<endl;
	cin >> firstselection;
	switch(firstselection){
		case 1:{
			secondlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		case 2:{
			cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
				break;
		}
		case 3:{cout << "you lost.do you want to restart?"<<endl;
			cout << "press 1 for yes  and 2 for no"<<endl;
			y=restart(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
			break;
		}
		
		default: {
		firstlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
		break;
	}
	}
}
int main(int argc, char** argv) {
int firstselection=0, secondselection=0, thirdselection=0,fourthselection=0,fifthselection=0,sixthselection=0;
	firstlevel(firstselection,secondselection,thirdselection,fourthselection,fifthselection,sixthselection);
	return 0;
}
int restart(int firstselection, int secondselection, int thirdselection,int fourthselection,int fifthselection,int sixthselection) {
	int k=0;
	int x;
	cin >> x;
	switch (x) {
	case 1: {
		cout << "restart" << endl;
		firstlevel(firstselection, secondselection, thirdselection,fourthselection,fifthselection,sixthselection);
		break;
	}
	default: {
	    cout << "thank you for taking the time to play our game " << endl;
		break;
	}
	}
	return k;
}
