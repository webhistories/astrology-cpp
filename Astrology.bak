/* Calixto, Dequito, Lorzano, Sojuaco */
#include <iostream>
#include <stdlib.h>
#include <iomanip>
#include <windows.h>
#include <limits>
#include <conio.h>
#include <string>
using namespace std;
void gotoxy (short x, short y)
{
	COORD pos = {x, y};
	SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), pos);
}
int main() {
	int M,D,Y;
	char ans;
	  do{
	  	 back:
		system("cls");
		cout<<"Enter your BIRTHMONTH [1-12], BIRTHDAY [1-31] and BIRTHYEAR separated by a space or a tab:"<<endl;
		cout<<"(BIRTHYEAR must not exceed to 2020 and not under 1900)";
		gotoxy(35,3);
//ERROR TRAPPING FOR INVALID VAR
		while(!(cin>>M>>D>>Y))
		{
//goto for else statement
		get: cin.clear();
			cin.ignore(999, '\n');
			gotoxy(30,5);
			cout<<"Invalid Input!!"; //15
			gotoxy(27,7);
			cout<<"Press any key to input again... ";
			getch();
			goto back; //18
			
	}
	    system("cls");
		gotoxy(1,1); cout<<"BIRTHDAY: "<< D;
		gotoxy(1,2); cout<<"BIRTHMONTH: "<< M;
		gotoxy(1,3); cout<<"BIRTHYEAR: "<< Y <<endl;
		cout<<"\n "<<setw(78)<<setfill('*')<<" "; //30
		
//Western Zodiac

//LEAP YEAR & Error Trapping
		if (M%2==0 && D>=31 && M!=2 || M==2 && D>=30 && Y%4==0)
		{
			gotoxy(26,11); cout<<"Note: Invalid date entered!";
			goto get;
		}
		
		else if (M==2 && D>=29 && Y%4!=0) {
			gotoxy(15,13); cout<<"Note: The year you entered is not a leap year!";
			goto get;
			}
		else if (M%1==0 && D>=32) {
			gotoxy(15,13); cout<<"Note: Invalid date entered!";
			goto get;
		}
		else if ((M>12 || D>31 || Y<1900 || Y>2020 ) || (M<1 || D<1))
			{
			gotoxy(26,13);
			cout<<"NO AVAILABLE HOROSCOPE FOR YOU!\n";
			goto get;
			}
//YEAR OF THE RAT-PIG
		else if ((Y-1900)%12==0 || Y==1900)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is RAT";
		gotoxy (1, 15); cout<<"Lucky Colors: blue, gold, green";
		gotoxy (1, 16); cout<<"Lucky Numbers: 2, 3";
		gotoxy (1,17); cout<<"Lucky Flowers: lily, African violet";
		}
		
		else if ((Y-1900)%12==1 || Y==1901)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is OX";
		gotoxy (1, 15); cout<<"Lucky Colors: white, yellow, green";
		gotoxy (1, 16); cout<<"Lucky Numbers:  1, 4";
		gotoxy (1,17); cout<<"Lucky Flowers: tulip, morning glory, peach blossom";
		}
		
		else if ((Y-1900)%12==2 || Y==1902)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is TIGER";
		gotoxy (1, 15); cout<<"Lucky Colors: blue, grey, orange, white";
		gotoxy (1, 16); cout<<"Lucky Numbers: 1, 3, 4";
		gotoxy (1,17); cout<<"Lucky Flowers: yellow lily, cineraria";
		}
		
		else if ((Y-1900)%12==3 || Y==1903)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is RABBIT";
		gotoxy (1, 15); cout<<"Lucky Colors: blue, gold, green";
		gotoxy (1, 16); cout<<"Lucky Numbers: 2, 3";
		gotoxy (1,17); cout<<"Lucky Flowers: lily, African violet";
		}
		
		else if ((Y-1900)%12==4 || Y==1904)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is DRAGON";
		gotoxy (1, 15); cout<<"Lucky Colors: gold, silver, grayish white";
		gotoxy (1, 16); cout<<"Lucky Numbers: 1, 6, 7";
		gotoxy (1,17); cout<<"Lucky Flowers: bleeding-heart glory bower, dragon flowers";
		}
		else if ((Y-1900)%12==5 || Y==1905)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is SNAKE";
		gotoxy (1, 15); cout<<"Lucky Colors: black, red, and yellow";
		gotoxy (1, 16); cout<<"Lucky Numbers: 2, 8, 9";
		gotoxy (1,17); cout<<"Lucky Flowers: orchid, cactus";
		}
		else if ((Y-1900)%12==6 || Y==1906)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is HORSE";
		gotoxy (1, 15); cout<<"Lucky Colors: yellow and green";
		gotoxy (1, 16); cout<<"Lucky Numbers: 2, 3, 7";
		gotoxy (1,17); cout<<"Lucky Flowers: calalily, jasmine";
		}
		else if ((Y-1900)%12==7 || Y==1907)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is SHEEP";
		gotoxy (1, 15); cout<<"Lucky Colors: brown, red, purple";
		gotoxy (1, 16); cout<<"Lucky Numbers: 8, 7";
		gotoxy (1,17); cout<<"Lucky Flowers: carnation, rose";
		}

		else if ((Y-1900)%12==8 || Y%4==0 && M==2 && D==29 || Y==1908 )
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is MONKEY";
		gotoxy (1, 15); cout<<"Lucky Colors: white, blue, gold";
		gotoxy (1, 16); cout<<"Lucky Numbers: 1, 5";
		gotoxy (1,17); cout<<"Lucky Flowers: chrysanthemum, cray-myrtle";
		}
		else if ((Y-1900)%12==9 || Y==1909 || Y%4==0 && M==2 && D==29)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is ROOSTER";
		gotoxy (1, 15); cout<<"Lucky Colors: gold, brown, yellow";
		gotoxy (1, 16); cout<<"Lucky Numbers: 5, 7, 8";
		gotoxy (1,17); cout<<"Lucky Flowers: gladiola, cockscomb";
		}
		else if ((Y-1900)%12==10 || Y==1910)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is DOG";
		gotoxy (1, 15); cout<<"Lucky Colors: red, green, purple";
		gotoxy (1, 16); cout<<"Lucky Numbers: 3, 4, 9";
		gotoxy (1,17); cout<<"Lucky Flowers: rose, cymbidium orchids";
		}
		else if ((Y-1900)%12==11 || Y==1911)
		{
		gotoxy(27,13); cout<<"Your Zodiac Sign is PIG";
		gotoxy (1, 15); cout<<"Lucky Colors: yellow, gray, brown, gold";
		gotoxy (1, 16); cout<<"Lucky Numbers: 2, 4, 8";
		gotoxy (1,17); cout<<"Lucky Flowers: hydrangea and daisy";
		}

//END


//CHINESE ZODIAC		
		//6
		if((M==12 && D>=22 && D<=31)|| (M==1 && D<=19 && D>=1)){
		gotoxy(27,6); cout<<"Your Zodiac Sign is CAPRICORN"; //29
		gotoxy(28,7);  cout<<"(December 22 - January 19)"; //25
		gotoxy(1,10); cout<<"2016 Western Horoscope For You:"; //23
		gotoxy (1, 11); cout<<"You will have a passing grade in Differential Calculus.";

		  }
		  
		  			

		else if((M==1 && D>=20 && D<=31) || (M==2 && D<=18 && D>=1)){
			gotoxy(27,6); cout<<"Zodiac Sign: AQUARIUS";
			gotoxy(28,7);  cout<<"(January 20 - February 18)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1, 11); cout<<"You will have an unforgettable moment for the day.";
		}
			else if(M==2 && D>=19 && D<=28 && Y%4!=0 || M==3 && D<=20 && D>=1 || M==2 && Y%4==0 && D>=19 && D<=29){
		  past:	gotoxy(27,6); cout<<"Zodiac Sign: PISCES";
		  gotoxy(28,7);  cout<<"(February 19 - March 20)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"Eat a healthy food to make you feel better.";
		}

	
			else if(M==3 && D>=21 && D<=31 || M==4 && D<=19 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: ARIES";
			gotoxy(28,7);  cout<<"(March 21 - April 19)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"Watch a movie with your love ones to make your year";
			gotoxy(1,12); cout<<"happy and worthful.";
		}
			else if(M==4 && D>=20 && D<31|| M==5 && D<=20 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: TAURUS";
			gotoxy(28,7);  cout<<"(April 20 - May 20)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"Do household chores to make your friends proud.";
		}
			else if(M==5 && D>=21 && D<=31|| M==6 && D<=20 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: GEMINI";
			gotoxy(28,7);  cout<<"(May 21 - June 20)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"Share your talent to make you fabulous.";
		}
			else if(M==6 && D>=21 && D<31|| M==7 && D<=22 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: CANCER";
			gotoxy(28,7);  cout<<"(June 21 - July 22)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"Do a chemotherapy sessions to prevent cancer.";
		}
			else if(M==7 && D>=23 && D<=31|| M==8 && D<=22 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: LEO";
			gotoxy(28,7);  cout<<"(July 23 - August 22)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"Love your pets so they will love you back.";
		}
			else if(M==8 && D>=23 && D<=31|| M==9 && D<=22 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: VIRGO";
			gotoxy(28,7);  cout<<"(September 23 - October 22)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"If you want to be loved don't be a plastic.";
		}
			else if(M==9 && D>=23 && D<31 || M==10 && D<=22 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: LIBRA";
			gotoxy(28,7);  cout<<"(September 23 - October 22)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"If you hate someone, tell them but never trip or";
			gotoxy(1,12); cout<<"tease them.";
		}
			else if(M==10 && D>=23 && D<=31 || M==11 && D<=21 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: SCORPIO";
			gotoxy(28,7);  cout<<"(October 10 - November 21)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"Don't use your stupid experiences for your retarded";
			gotoxy(1,12); cout<<"mind, instead find a better and helpful solution.";
		}
			else if(M==11 && D>=22 && D<31 || M==12 && D<=21 && D>=1){
			gotoxy(27,6); cout<<"Zodiac Sign: SAGITTARIUS";
			gotoxy(28,7);  cout<<"(November 22 - December 21)";
			gotoxy(1,10); cout<<"2016 Western Horoscope For You:";
			gotoxy(1,11); cout<<"If you think you're useless, well, that's true.";
		}
		

		
		gotoxy(2,18);
		system("pause");
//goto for invalid input in Y or N		
		balik: 
		gotoxy(23,20);
		system("cls");
		gotoxy(10,12); cout<<"Would you like to enter another birthday [y/n]?";
		gotoxy (28,14);
		cin>>ans;
	 

	


} while(toupper(ans)=='Y');

	 	if(toupper(ans)=='N')
		return 0;


else if (toupper(ans)!='N' && toupper(ans)!='Y')
	{

		gotoxy(10,16);
		cout<<"Invalid Input!";
		gotoxy(10, 18);
		system("pause");
		goto balik;

	}
}



