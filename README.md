# quiz#include<iostream.h>
#include<conio.h>
#include<fstream.h>
int main()
{
char ch,ans;
int a,marks=0;
clrscr();
ifstream fillin1("Q.DAT",iosin);
//ofstream fillout;

do
{
 cout<<"\n1.Start";
 cout<<"\n2.Show marks";
 cout<<"\n3.Quit";
 cout<<"\nEnter your choice";
 cin>>a;
 switch(a)
 {
   case 1:cout<<"Start";
     marks=0;
     fillin1.get(ch);
     cout<<"The Rules ofthe game are as follows:";
     cout<<"For correct answer 10 marks and the incorrect answer marks=-5";
     cout<<"\n\nGet ready for the amazing game";
     cout<<"\n\n1)WHO WON THE CONFED CUP 2013?";
     cout<<"\nA)BRAZIL\tB)SPAIN\tC)ITALY\tD)PORTUGUAL";
     cout<<"Enter your answer";
     cin>>ans;
     if(ans==fillin1.ch)
     marks++;
     clrscr();
     cout<<"\n\n2)WHO WAS AWARDED WITH DADASAHEB PHALKE AWARD RECENTLY?";
     cout<<"\nA)SHAMMI KAPOOR\tB) RAJESH KHANNA\tC)DILIP KUMAR\tD)PRAN";
       cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);
     if(ans==fillin1.ch)
     marks++;
     clrscr();
     cout<<"\n3)WHO WAS KNOWN AS THE FATHER OF PENTIUM CHIP?";
     cout<<"\nA)LARRY PAGE\tB)AMAR BOSE\tC)VINOD DHAM\tD)SHIV NADAR";
     cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);
     if(ans==fillin1.ch)
     marks++;
     clrscr();
     cout<<"\n4)WHO IS THE CYCLIST THAT RECIEVED A LIFE BAN RECENTLY?";
     cout<<"\nA)LANCE ARMSTRONG\tB)ALBERTO CONTADOR\tC)FLOYD LANDIS\tD)TYLER HAMILTON";
      cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);
     if(ans==fillin1.ch)
     marks++;
     clrscr();
    cout<<"\n\n5)IN WHICH COUNTRY IS THE FUKUSHIMA NUCLEAR REACTOR LOCATED"?
    cout<<"\nA) CHINA\tB)JAPAN\tC)TAIWAN\tD)FIJI";
    cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);
     if(ans==fillin1.ch)
     marks++;
     clrscr();
	cout<<"\n\n6)WHO IS THE FOUNDER OF JUST DIAL?";
	cout<<"\n\nA)VSS MANI\tB)BOB PARSONS\tC)RICHARD PAUL\tD)PIERRE OMIDYAR";
	cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);
     if(ans==fillin1.ch)
     marks++;
     clrscr();
    cout<<"\n\n7)FOR WHICH FILM DID JENIFIER LAWRENCE GOT AN OSCAR FOR THE BEST ACTRESS?";
    cout<<"\nA)XMEN\tB)PLAYBOOK\tC)SERENA\tD)LIKE CRAZY";
    cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);
     if(ans==fillin1.ch)
     marks++;
     clrscr();
   cout<<"\n\n8)WHAT IS THE FULL FORM OF FAT?";
   cout<<"\nA)FOOTBALL ASSOCIATION TAIWAN\tB)FILE ALLOCATION TABLE \tC)FIJI ASSOCIATION OF TYCOONS\tD)FUKUSHIMA TEAM OF TABALCHIS";
   cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);

     if(ans==fillin1.ch)
     marks++;
     clrscr();
      cout<<"\n\n9)WHICH FILM WAS AWARDED AS THE BEST FILM AT THE 66th BAFTA?";
  cout<<"\nA)ARGO\tB)LINCOLN\tC)DIANA\tD)FIRE IN THE BABYLON";
  cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);
     if(ans==fillin1.ch)
     marks++;
     clrscr();
  cout<<"\n\n10)WHO IS THE ONLY BATSMAN TO HAVE SCORED A QUADRAPULE IN TEST?";
  cout<<"\nA)SACHIN TENDULKAR\tB)SANATH JAYASURIYA\tC)BRIAN LARA\tD)RICKY PONTING";
  cout<<"Enter your answer";
     cin>>ans;
     fillin1.get(ch);
     if(ans==fillin1.ch)
     marks++;
     clrscr();
     break;
case 2 :cout<<"MARKS"<<marks;
	break;
case 3 : exit(0);
}
 }while(a<=3);

}
