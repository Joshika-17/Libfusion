# Libfusion
//HEADER FILES
#include<stdio.h>
#include<stdlib.h>
#include<unistd.h>
//FUNTIONS
void book();
void stumem();
void weekmem();
void monmem();
void vipmem();
int daysBetween();
void Payment_Error();
void Payment_Success();
//MACROS
#define A 1122
#define B 1123
#define C 1124
#define D 1125
//STRUCTURES
struct date1{
     int day;
     int mon;
     int year;
};
typedef struct donator{
     char name[100];
     long long int phno;
     char add[500];
     char bookname[50];
     int serno;
     struct date1 d ;
}S;
struct date {
    int day, month, year;
};
//MAIN FUNCTIONS
int main()
{
    int status=system("color 3");
    FILE *fig;
    FILE *stu;
    FILE *week;
    FILE *month;
    FILE *year;
    fig= fopen("libfusionfigure.txt","a");
    int a,n,b,c,d,opt,pass,f,g,h,i,opt1,opt2,n1,s1,w1,m1,v1,ss1,p1;
    char p='|',q='/',r='\\',s='-';
    printf("\t\t\t\t            %c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",q,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,r);
    fputs("\t\t\t\t            /----------------------------\\\n",fig);
    printf("\t\t\t\t           %c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",q,q,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,r,r);
    fputs("\t\t\t\t           //----------------------------\\\\\n",fig);
    printf("\t\t\t\t          %c%c                              %c%c\n",q,q,r,r);
    fputs("\t\t\t\t          //                              \\\\\n",fig);
    printf("\t\t\t\t         %c%c                                %c%c\n",q,q,r,r);
    fputs("\t\t\t\t         //                                \\\\\n",fig);
    printf("\t\t\t\t        %c%c           ***BBJMS***            %c%c\n",q,q,r,r);
    fputs("\t\t\t\t        //           ***BBJMS***            \\\\\n",fig);
    printf("\t\t\t\t       %c%c         *****LIBRARY*****          %c%c\n",p,q,r,p);
    fputs("\t\t\t\t       |/         *****LIBRARY*****          \\|\n",fig);
    printf("\t\t\t\t       %c                                      %c\n",p,p);
    fputs("\t\t\t\t       |                                      |\n",fig);
    printf("\t\t\t\t       %c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s);
    fputs("\t\t\t\t       ----------------------------------------\n",fig);
    printf("\t\t\t\t        %c                                    %c\n",p,p);
    fputs("\t\t\t\t        |                                    |\n",fig);
    printf("\t\t\t\t        %c %c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c %c\n",p,p,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,p,p);
    fputs("\t\t\t\t        | |--------------------------------| |\n",fig);
    printf("\t\t\t\t    %c%c%c%c%c%c%c                                %c%c%c%c%c%c%c\n",p,s,s,s,s,s,p,p,s,s,s,s,s,p);
    fputs("\t\t\t\t    |-----|                                |-----|\n",fig);
    printf("\t\t\t\t    %c %c%c%c %c          *LIB FUSION*          %c %c%c%c %c\n",p,q,s,r,p,p,q,s,r,p);
    fputs("\t\t\t\t    | /-\\ |          *LIB FUSION*          | /-\\ |\n",fig);
    printf("\t\t\t\t    %c %c %c %c                                %c %c %c %c\n",p,p,p,p,p,p,p,p);
    fputs("\t\t\t\t    | | | |                                | | | |\n",fig);
    printf("\t\t\t\t    %c %c %c %c         %c%c%c%c%c%c%c%c%c%c%c%c%c          %c %c %c %c\n",p,p,p,p,s,s,s,s,s,s,s,s,s,s,s,s,s,p,p,p,p);
    fputs("\t\t\t\t    | | | |         -------------          | | | |\n",fig);
    printf("\t\t\t\t    %c %c %c %c         %c     %c     %c          %c %c %c %c\n",p,p,p,p,p,p,p,p,p,p,p);
    fputs("\t\t\t\t    | | | |         |     |     |          | | | |\n",fig);
    printf("\t\t\t\t    %c %c %c %c         %c     %c     %c          %c %c %c %c\n",p,p,p,p,p,p,p,p,p,p,p);
    fputs("\t\t\t\t    | | | |         |     |     |          | | | |\n",fig);
    printf("\t\t\t\t    %c %c %c %c         %c     %c     %c          %c %c %c %c\n",p,p,p,p,p,p,p,p,p,p,p);
    fputs("\t\t\t\t    | | | |         |     |     |          | | | |\n",fig);
    printf("\t\t\t\t    %c %c %c %c         %c     %c     %c          %c %c %c %c\n",p,p,p,p,p,p,p,p,p,p,p);
    fputs("\t\t\t\t    | | | |         |     |     |          | | | |\n",fig);
    printf("\t\t\t\t    %c %c%c%c %c         %c     %c     %c          %c %c%c%c %c\n",p,r,s,q,p,p,p,p,p,r,s,q,p);
    fputs("\t\t\t\t    | \\-/ |         |     |     |          | \\-/ |\n",fig);
    printf("\t\t\t\t  %c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s);
    fputs("\t\t\t\t  --------------------------------------------------\n",fig);
    printf("\t\t\t\t  %c                                                %c\n",p,p);
    fputs("\t\t\t\t  |                                                |\n",fig);
    printf("\t\t\t\t  %c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n\n\n",s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s);
    fputs("\t\t\t\t  --------------------------------------------------\n",fig);
    printf("\t\t\t\t\t%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s);
    fputs("\t\t\t\t\t----------------------------------\n",fig);
    printf("\t\t\t\t\t%c  WELCOME TO THE LIFE OF BOOKS  %c\n",p,p);
    fputs("\t\t\t\t\t|  WELCOME TO THE LIFE OF BOOKS  |\n",fig);
    printf("\t\t\t\t\t%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s,s);
    fputs("\t\t\t\t\t----------------------------------\n",fig);
    fclose(fig);
    printf("enter any key to continue :\n\n");
    getch(n);
    libfusion:
        printf("\n\n\t\t -----------------------------------------------\n");
        printf("\t\t| \t\t         \t\t\t|\n\t\t|\t\t  LIBFUSION\t\t\t");
        printf("|\n\t\t|\t\t\t\t\t\t|\n\t\t-------------------------------------------------\n");
        printf("\t\t|\t\t\t\t\t\t|\n\t\t| \t 1.Are you a membership holder:\t\t|\n\t\t|\t\t\t\t\t\t|\n");
        printf("\t\t|\t 2.New to the library:\t\t\t|\n\t\t|\t\t\t\t\t\t|\n\t\t");
        printf(" ----------------------------------------------- \n\n");
        printf("\t\t\tEnter your option:");
        scanf("%d",&a);
    if(a==1)
      {
       printf("\n\tEnter your membership pass number: ");
       scanf("%d",&pass);
       printf("\n");
      if(pass==A)
      {
          char p[30]={'P','a','s','s',' ','n','u','m','b','e','r',' ','m','a','t','c','h','e','d','.','.','.'};//22
          for(int i=1;i<=1;i++)
          {
              printf("\r                      \r");
              for(int j=0;j<=22;j++)
              {
                  printf("%c",p[j]);
                  usleep(40000);
              }
          }printf("\n\n");
              printf("\t\t\t\tYou are a Student membership pass holder :)\n\n");
              student:
              printf("\n\n\t\t--------------------------------------------------\n\t\t|\t   CHOOSE THE OPTION                     |\n\t\t|------------------------------------------------|\n");
              printf("\t\t|\t1.Donate a book                          |\n\t\t|\t\t\t\t\t\t |\n");
              printf("\t\t|\t2.To take the book home                  |\n\t\t|\t\t\t\t\t\t |\n\t\t|\t3.To read a book in the library          |\n\t\t|\t\t\t\t\t\t |\n");
              printf("\t\t|\t4.Submission of book                     |\n\t\t--------------------------------------------------");
              printf("\n\nEnter the option: ");
              scanf("%d",&f);
          switch(f)
          {
          case 1:
             printf("\t\t\tYou came for donating a book :)))\n");
             BBJMS:
             printf("\n\n\t\t\tEnter your details in the log book:\n\n");
             S z;
             printf("\n\tEnter your name : ");
             fflush(stdin);
             gets(z.name);
             printf("\n\tEnter your phone number : ");
             scanf("%lld",&z.phno);
             fflush(stdin);
             printf("\n\tEnter your address : ");
             fflush(stdin);
             gets(z.add);
             fflush(stdin);
             printf("\n\tEnter donating book name : ");
             fflush(stdin);
             gets(z.bookname);
             fflush(stdin);
             printf("\n\tEnter book serial number : ");
             scanf("%d",&z.serno);
             fflush(stdin);
             printf("\n\tEnter the date(Eg: 17 04 2024) : ");
             scanf("%d %d %lld",&z.d.day,&z.d.mon,&z.d.year);
             fflush(stdin);
             printf("\n\n\t\tThese are the details of a person who donate a book :\n\n\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%lld\n\n",z.name,z.phno,z.add,z.bookname,z.serno,z.d.day,z.d.mon,z.d.year);
             printf("\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tCheck your details once...\n\n");
             printf("\t\tIf it is correct press 1 or if it is wrong press 2: ");
             fflush(stdin);
             scanf("%d",&opt2);
             stu=fopen("Donar details.csv","a");
             fprintf(stu,"%s,%lld,%s,%s,%d,%d-%d-%lld\n",z.name,z.phno,z.add,z.bookname,z.serno,z.d.day,z.d.mon,z.d.year);
             fclose(stu);
             if(opt2==1)
             {
                printf("\n\n\t\t\t\t***THANKS FOR DONATING A BOOK TO OUR LIBRARY***\n\n");
             }
             if(opt2==2)
             {
             goto BBJMS;
             }
             printf("\n\t\tIf you want to check our library books Press 1 or to exit Press 2: ");
             scanf("%d",&n1);
             if(n1==1){
             goto student;
            }
            break;
          case 2:
              printf("\t\t\tYou came for taking a book to home :)))\n");
              book();
              LIB:
              printf("\n\n\t\t\tEnter your details in the log book:");
              S z1;
              printf("\n\n\tEnter your name : ");
              fflush(stdin);
              gets(z1.name);
              fflush(stdin);
              printf("\n\tEnter your phone number : ");
              scanf("%lld",&z1.phno);
              fflush(stdin);
              printf("\n\tEnter your address : ");
              fflush(stdin);
              gets(z1.add);
              printf("\n\tEnter the book name : ");
              fflush(stdin);
              gets(z1.bookname);
              printf("\n\tEnter book serial number : ");
              scanf("%d",&z1.serno);
              fflush(stdin);
              printf("\n\tEnter the date(Eg: 17 04 2024) : ");
              scanf("%d %d %d",&z1.d.day,&z1.d.mon,&z1.d.year);
              fflush(stdin);
              printf("\n\n\t\tThese are the details of a person who take the book to home :\n\n\t\t-------------------------------------------------------\n\n");
              printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z1.name,z1.phno,z1.add,z1.bookname,z1.serno,z1.d.day,z1.d.mon,z1.d.year);
              printf("\t\t-------------------------------------------------------\n\n");
              printf("\t\t\tCheck your details once..");
              printf("\n\n\t\tIf you want to change your details press 1 or press 2 to exit: ");
              fflush(stdin);
              scanf("%d",&opt1);
              stu=fopen("Book takers details.csv","a");
              fprintf(stu,"%s,%lld,%s,%s,%d,%d-%d-%lld\n",z1.name,z1.phno,z1.add,z1.bookname,z1.serno,z1.d.day,z1.d.mon,z1.d.year);
              fclose(stu);
              while(opt1==1)
              {
              goto LIB;
              }
              break;
          case 3:
             printf("\t\t\tYou came for reading a book in the library :)))\n");
              book();
             FUSION:
             printf("\n\n\t\t\tEnter your details in the log book:\n");
             S z2;
             printf("\n\tEnter your name : ");
             fflush(stdin);
             gets(z2.name);
             fflush(stdin);
             printf("\n\tEnter your phone number : ");
             scanf("%lld",&z2.phno);
             fflush(stdin);
             printf("\n\tEnter your address : ");
             fflush(stdin);
             gets(z2.add);
             fflush(stdin);
             printf("\n\tEnter the book name : ");
             fflush(stdin);
             gets(z2.bookname);
             fflush(stdin);
             printf("\n\tEnter book serial number : ");
             scanf("%d",&z2.serno);
             fflush(stdin);
             printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
             scanf("%d %d %d",&z2.d.day,&z2.d.mon,&z2.d.year);
             fflush(stdin);
             printf("\n\n\t\tThese are the details of a person who read the book in library :\n\n\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z2.name,z2.phno,z2.add,z2.bookname,z2.serno,z2.d.day,z2.d.mon,z2.d.year);
             printf("\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tCheck your details once..");
             printf("\n\n\t\t\tIf you want to change your details press 1 or press 2 to exit: ");
             fflush(stdin);
             scanf("%d",&opt1);
             stu=fopen("Book reader details.csv","a");
             fprintf(stu,"%s,%lld,%s,%s,%d,%d-%d-%lld\n",z2.name,z2.phno,z2.add,z2.bookname,z2.serno,z2.d.day,z2.d.mon,z2.d.year);
             fclose(stu);
             while(opt1==1)
             {
             goto FUSION;
             }
             break;
          case 4:
            printf("\t\t\tYou came for submission of book :)))\n\n");
            struct date d1, d2;
            int fn;
            printf("\n\n\tEnter first date of book taken (Eg:dd mm yyyy): ");
            scanf("%d %d %d", &d1.day, &d1.month, &d1.year);
            printf("\n\n\tEnter  the book returning date (Eg:dd mm yyyy): ");
            scanf("%d %d %d", &d2.day, &d2.month, &d2.year);
            printf("\n\n\tNumber of days between two dates :   %d\n", daysBetween(d1, d2));
            if(daysBetween(d1, d2)<=20)
             {
                printf("\n\t\tYou have returned the book in 20 days only  \n\n\t\t\tSo there is no fine ...\n\n\t\t\t***THANK YOU***\n");
             }
            else
             {
               printf("\n\n\tDays exceeded are             => %d\n",daysBetween(d1, d2) - 20);
               printf("\n\n\tFine for exceeding limit is   => %d days * 10 rs\n",daysBetween(d1, d2) - 20);
               printf("\n\n\tYour fine has to pay is       => %d rs\n",(daysBetween(d1, d2) - 20) * 10);
               amount:
               printf("\n\n\t\tEnter the amount:  ");
               scanf("%lld",&s1);
               printf("\n\n");
               if(s1==(daysBetween(d1, d2) - 20)*10)
               {
                 Payment_Success();
                 printf("\n\n\t\t\t\t\t*****THANK YOU*****");
               }
               else
              {
                 Payment_Error();
                 goto amount;
              }
               break;
          }
        }
       }
          else if(pass==B)
           {
             char p[30]={'P','a','s','s',' ','n','u','m','b','e','r',' ','m','a','t','c','h','e','d','.','.','.'};//22
             for(int i=1;i<=1;i++)
             {
                printf("\r                      \r");
                for(int j=0;j<=22;j++)
               {
                   printf("%c",p[j]);
                   usleep(40000);
               }
            }
              printf("\n\n");
              printf("\t\t\t\tYou are a Weekly membership pass holder :)\n\n");
              weekly:
              printf("\n\n\t\t--------------------------------------------------\n\t\t|\t   CHOOSE THE OPTION                     |\n\t\t|------------------------------------------------|\n");
              printf("\t\t|\t1.Donate a book                          |\n\t\t|\t\t\t\t\t\t |\n");
              printf("\t\t|\t2.To take the book home                  |\n\t\t|\t\t\t\t\t\t |\n\t\t|\t3.To read a book in the library          |\n\t\t|\t\t\t\t\t\t |\n");
              printf("\t\t|\t4.Submission of book                     |\n\t\t--------------------------------------------------");
              printf("\n\nEnter the option: ");
              scanf("%d",&g);
          switch(g)
          {
          case 1:
             printf("\t\t\tYou came for donating a book :)))\n");
             printf("\n\n\t\t\tEnter your details in the log book \n");
             S z3;
             printf("\n\tEnter your name : ");
             fflush(stdin);
             gets(z3.name);
             fflush(stdin);
             printf("\n\tEnter your phone number : ");
             scanf("%lld",&z3.phno);
             fflush(stdin);
             printf("\n\tEnter your address : ");
             fflush(stdin);
             gets(z3.add);
             fflush(stdin);
             printf("\n\tEnter donating book name : ");
             fflush(stdin);
             gets(z3.bookname);
             fflush(stdin);
             printf("\n\tEnter book serial number : ");
             scanf("%d",&z3.serno);
             fflush(stdin);
             printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
             scanf("%d %d %d",&z3.d.day,&z3.d.mon,&z3.d.year);
             fflush(stdin);
             printf("\n\n\t\tThese are the details of a person who donate the book :\n\n\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z3.name,z3.phno,z3.add,z3.bookname,z3.serno,z3.d.day,z3.d.mon,z3.d.year);
             printf("\t\t-------------------------------------------------------\n\n");
             printf("\tCheck your details once..");
             printf("\n\n\t\tIf it is correct press 1 or if it is wrong press 2: ");
             fflush(stdin);
             scanf("%d",&opt2);
             week=fopen("donar details.csv","a");
             fprintf(week,"%s,%lld,%s,%s,%d,%d-%d-%lld\n",z3.name,z3.phno,z3.add,z3.bookname,z3.serno,z3.d.day,z3.d.mon,z3.d.year);
             fclose(week);
             if(opt2==1)
             {
                printf("\n\n\t\t\t\t***THANKS FOR DONATING A BOOK TO OUR LIBRARY***\n\n");
             }
             if(opt2==2)
             {
                goto BBJMS;
             }
            printf("\n\tIf you want to check our library books Press 1 or to exit Press 2: ");
            scanf("%d",&n1);
            if(n1==1){
            goto weekly;
            }
            break;
          case 2:
             printf("\t\t\tYou came for taking a book to home :)))\n");
             book();
             printf("\n\n\t\t\tEnter your details in the log book:\n");
             S z4;
             printf("\n\tEnter your name : ");
             fflush(stdin);
             gets(z4.name);
             fflush(stdin);
             printf("\n\tEnter your phone number : ");
             scanf("%lld",&z4.phno);
             fflush(stdin);
             printf("\n\tEnter your address : ");
             fflush(stdin);
             gets(z4.add);
             fflush(stdin);
             printf("\n\tEnter the book name : ");
             fflush(stdin);
             gets(z4.bookname);
             fflush(stdin);
             printf("\n\tEnter book serial number : ");
             scanf("%d",&z4.serno);
             fflush(stdin);
             printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
             scanf("%d %d %d",&z4.d.day,&z4.d.mon,&z4.d.year);
             fflush(stdin);
             printf("\n\n\t\tThese are the details of a person who take the book to home :\n\n\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z4.name,z4.phno,z4.add,z4.bookname,z4.serno,z4.d.day,z4.d.mon,z4.d.year);
             printf("\t\t-------------------------------------------------------\n\n");
             printf("\t\tCheck your details once..");
             printf("\n\n\t\tIf you want to change your details press 1 or press 2 to exit: ");
             fflush(stdin);
             scanf("%d",&opt1);
             week=fopen("Book taker details.csv","a");
             fprintf(week,"%s,%lld,%s,%s,%d,%d-%d-%lld\n",z4.name,z4.phno,z4.add,z4.bookname,z4.serno,z4.d.day,z4.d.mon,z4.d.year);
             fclose(week);
             while(opt1==1)
             {
                 goto LIB;
             }
             break;
          case 3:
             printf("\t\t\tYou came for reading a book in the library :)))\n");
             book();
             printf("\n\n\t\tEnter your details in the log book \n");
             S z5;
             printf("\n\tEnter your name : ");
             fflush(stdin);
             gets(z5.name);
             fflush(stdin);
             printf("\n\tEnter your phone number : ");
             scanf("%lld",&z5.phno);
             fflush(stdin);
             printf("\n\tEnter your address : ");
             fflush(stdin);
             gets(z5.add);
             fflush(stdin);
             printf("\n\tEnter the book name : ");
             fflush(stdin);
             gets(z5.bookname);
             printf("\n\tEnter book serial number : ");
             scanf("%d",&z5.serno);
             fflush(stdin);
             printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
             scanf("%d %d %d",&z5.d.day,&z5.d.mon,&z5.d.year);
             fflush(stdin);
             printf("\n\n\t\tThese are the details of a person who read the book in library :\n\n\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z5.name,z5.phno,z5.add,z5.bookname,z5.serno,z5.d.day,z5.d.mon,z5.d.year);
             printf("\t\t-------------------------------------------------------\n\n");
             printf("\t\tCheck your details once..");
             printf("\n\n\t\tIf you want to change your details press 1 or press 2 to exit: ");
             fflush(stdin);
             scanf("%d",&opt1);
             week=fopen("Reader details.csv","a");
             fprintf(week,"%s,%lld,%s,%s,%d,%d-%d-%lld\n",z5.name,z5.phno,z5.add,z5.bookname,z5.serno,z5.d.day,z5.d.mon,z5.d.year);
             fclose(week);
             while(opt1==1)
             {
               goto FUSION;
             }
             break;
         case 4:
               printf("\t\t\tYou came for submission of book :)))\n\n");
               struct date d1, d2;
               int fn;
               printf("\n\n\tEnter first date of book taken (Eg:dd mm yyyy): ");
               scanf("%d %d %d", &d1.day, &d1.month, &d1.year);
               printf("\n\n\tEnter  the book returning date (Eg:dd mm yyyy): ");
               scanf("%d %d %d", &d2.day, &d2.month, &d2.year);
               printf("\n\n\tNumber of days between two dates is:   %d\n", daysBetween(d1, d2));
            if(daysBetween(d1, d2)<=7)
            {
                   printf("\n\t\tYou have returned the book in 7days only  \n\n\t\t\tSo there is no fine ...\n\n\t\t\t***THANK YOU***\n");
            }
           else
           {
             printf("\n\n\tDays exceeded are           => %d",daysBetween(d1, d2) - 7);
             printf("\n\n\tFine for exceeding limit is => %d days * 20 rs\n",daysBetween(d1, d2) - 7);
             printf("\n\tYour fine has to pay is       => %d rs",(daysBetween(d1, d2) - 7) * 20);
             amount1:
             printf("\n\n\n\tEnter the amount:  ");
             scanf("%lld",&w1);
             printf("\n\n");
          if(s1==(daysBetween(d1, d2) - 7)*20)
            {
                 Payment_Success();
                 printf("\n\n\t\t\t\t\t*****THANK YOU*****");
            }
         else
            {
                Payment_Error();
                goto amount1;
            }
              break;
          }
        }
     }
          else if(pass==C)
          {
               char p[30]={'P','a','s','s',' ','n','u','m','b','e','r',' ','m','a','t','c','h','e','d','.','.','.'};//22
               for(int i=1;i<=1;i++)
            {
                printf("\r                      \r");
                for(int j=0;j<=22;j++)
               {
                    printf("%c",p[j]);
                    usleep(40000);
                }
             }
               printf("\n\n");
               printf("\t\t\t\tYou are a Monthly membership pass holder :)\n\n");
               monthly:
               printf("\n\n\t\t--------------------------------------------------\n\t\t|\t   CHOOSE THE OPTION                     |\n\t\t|------------------------------------------------|\n");
               printf("\t\t|\t1.Donate a book                          |\n\t\t|\t\t\t\t\t\t |\n");
               printf("\t\t|\t2.To take the book home                  |\n\t\t|\t\t\t\t\t\t |\n\t\t|\t3.To read a book in the library          |\n\t\t|\t\t\t\t\t\t |\n");
               printf("\t\t|\t4.Submission of book                     |\n\t\t--------------------------------------------------");
               printf("\n\nEnter the option: ");
               scanf("%d",&h);
          switch(h)
          {
          case 1:
             printf("\t\t\tYou came for donating a book :)))\n");
             printf("\n\n\t\t\tEnter your details in the log book \n");
             S z6;
             printf("\n\tEnter your name : ");
             fflush(stdin);
             gets(z6.name);
             fflush(stdin);
             printf("\n\tEnter your phone number : ");
             scanf("%lld",&z6.phno);
             fflush(stdin);
             printf("\n\tEnter your address : ");
             fflush(stdin);
             gets(z6.add);
             fflush(stdin);
             printf("\n\tEnter donating book name : ");
             fflush(stdin);
             gets(z6.bookname);
             printf("\n\tEnter book serial number : ");
             scanf("%d",&z6.serno);
             fflush(stdin);
             printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
             scanf("%d %d %d",&z6.d.day,&z6.d.mon,&z6.d.year);
             fflush(stdin);
             printf("\n\n\t\tThese are the details of a person who donate book :\n\n\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z6.name,z6.phno,z6.add,z6.bookname,z6.serno,z6.d.day,z6.d.mon,z6.d.year);
             printf("\t\t-------------------------------------------------------\n\n");
             printf("\n\n\t\tCheck your details once..");
             printf("\t\tIf it is correct press 1 or if it is wrong press 2: ");
             fflush(stdin);
             scanf("%d",&opt2);
             month=fopen("donar details.csv","a");
             fprintf(month,"%s,%lld,%s,%s,%d,%d-%d-%lld\n\n",z6.name,z6.phno,z6.add,z6.bookname,z6.serno,z6.d.day,z6.d.mon,z6.d.year);
             fclose(month);
             if(opt2==1)
              {
                 printf("\n\n\t\t\t\t***THANKS FOR DONATING A BOOK TO OUR LIBRARY***\n\n");
              }
             if(opt2==2)
             {
              goto BBJMS;
             }
              printf("\n\t\tIf you want to check our library books Press 1 or to exit Press 2: ");
              scanf("%d",&n1);
              if(n1==1)
                {
                 goto monthly;
               }
            break;
          case 2:
              printf("\t\t\tYou came for taking a book to home :)))\n");
              book();
              printf("\n\n\t\t\tEnter your details in the log book:\n");
              S z7;
              printf("\n\tEnter your name : ");
              fflush(stdin);
              gets(z7.name);
              fflush(stdin);
              printf("\n\tEnter your phone number : ");
              scanf("%lld",&z7.phno);
              fflush(stdin);
              printf("\n\tEnter your address : ");
              fflush(stdin);
              gets(z7.add);
              fflush(stdin);
              printf("\n\tEnter the book name : ");
              fflush(stdin);
              gets(z7.bookname);
              printf("\n\tEnter book serial number : ");
              scanf("%d",&z7.serno);
              fflush(stdin);
              printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
              scanf("%d %d %d",&z7.d.day,&z7.d.mon,&z7.d.year);
              fflush(stdin);
              printf("\n\n\t\tThese are the details of a person who take the book to home :\n\n\t\t-------------------------------------------------------\n\n");
              printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z7.name,z7.phno,z7.add,z7.bookname,z7.serno,z7.d.day,z7.d.mon,z7.d.year);
              printf("\t\t-------------------------------------------------------\n\n");
              printf("\t\tCheck your details once..");
              printf("\n\n\t\tIf you want to change your details press 1 or press 2 to exit");
              fflush(stdin);
              scanf("%d",&opt1);
              month=fopen("Book taker details.csv","a");
              fprintf(month,"%s,%lld,%s,%s,%d,%d-%d-%lld\n\n",z7.name,z7.phno,z7.add,z7.bookname,z7.serno,z7.d.day,z7.d.mon,z7.d.year);
              fclose(month);
              while(opt1==1)
              {
               goto LIB;
              }
            break;
          case 3:
              printf("\t\t\tYou came for reading a book in the library :)))\n");
              book();
              printf("\n\n\t\t\tEnter your details in the log book:\n");
              S z8;
              printf("\n\tEnter your name : ");
              fflush(stdin);
              gets(z8.name);
              fflush(stdin);
              printf("\n\tEnter your phone number : ");
              scanf("%lld",&z8.phno);
              fflush(stdin);
              printf("\n\tEnter your address : ");
              fflush(stdin);
              gets(z8.add);
              fflush(stdin);
              printf("\n\tEnter the book name : ");
              fflush(stdin);
              gets(z8.bookname);
              printf("\n\tEnter book serial number : ");
              scanf("%d",&z8.serno);
              fflush(stdin);
              printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
              scanf("%d %d %d",&z8.d.day,&z8.d.mon,&z8.d.year);
              fflush(stdin);
              printf("\n\n\t\tThese are the details of a person who read the book in library :\n\n\t\t-------------------------------------------------------\n\n");
              printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z8.name,z8.phno,z8.add,z8.bookname,z8.serno,z8.d.day,z8.d.mon,z8.d.year);
              printf("\t\t-------------------------------------------------------\n\n");
              printf("\t\tCheck your details once..");
              printf("\n\n\t\tIf you want to change your details press 1 or press 2 to exit: ");
              fflush(stdin);
              scanf("%d",&opt1);
              month=fopen("Reader details.csv","a");
              fprintf(month,"%s,%lld,%s,%s,%d,%d-%d-%lld\n\n",z8.name,z8.phno,z8.add,z8.bookname,z8.serno,z8.d.day,z8.d.mon,z8.d.year);
              fclose(month);
              while(opt1==1)
              {
                goto FUSION;
              }
                break;
         case 4:
             printf("\t\t\tYou came for submission of book\n\n");
             struct date d1, d2;
             int fn;
             printf("\n\n\tEnter first date of book taken (Eg: dd mm yyyy): ");
             scanf("%d %d %d", &d1.day, &d1.month, &d1.year);
             printf("\n\n\tEnter  the book returning date (Eg: dd mm yyyy): ");
             scanf("%d %d %d", &d2.day, &d2.month, &d2.year);
             printf("\n\n\tNumber of days between two dates is:   %d\n", daysBetween(d1, d2));
             if(daysBetween(d1, d2)<=30)
              {
                printf("\n\t\t\tYou have returned the book in 30 days only  \n\n\t\tSo there is no fine ...\n\n\t\t\t***THANK YOU***\n");
              }
            else
            {
                printf("\n\n\tDays exceeded are           => %d",daysBetween(d1, d2) - 30);
                printf("\n\n\tFine for exceeding limit is => %d days * 15 rs\n",daysBetween(d1, d2) - 30);
                printf("\n\tYour fine has to pay is       => %d rs",(daysBetween(d1, d2) - 30) * 15);
                amount2:
                printf("\n\n\n\tEnter the amount:  ");
                scanf("%lld",&m1);
                printf("\n\n");
                if(s1==(daysBetween(d1, d2) - 30)*15)
               {
                  Payment_Success();
                  printf("\n\n\t\t\t\t\t*****THANK YOU*****");
               }
              else
              {
                Payment_Error();
                goto amount2;
              }
              break;
     }
  }
 }
          else if(pass==D)
          {
             char p[30]={'P','a','s','s',' ','n','u','m','b','e','r',' ','m','a','t','c','h','e','d','.','.','.'};//22
             for(int i=1;i<=1;i++)
           {
                 printf("\r                      \r");
                 for(int j=0;j<=22;j++)
               {
                     printf("%c",p[j]);
                     usleep(40000);
               }
           }
              printf("\n\n");
              printf("\t\t\t\tYou are a VIP membership pass holder :)\n\n");
              vipp:
              printf("\n\n\t\t--------------------------------------------------\n\t\t|\t   CHOOSE THE OPTION                     |\n\t\t|------------------------------------------------|\n");
              printf("\t\t|\t1.Donate a book                          |\n\t\t|\t\t\t\t\t\t |\n");
              printf("\t\t|\t2.To take the book home                  |\n\t\t|\t\t\t\t\t\t |\n\t\t|\t3.To read a book in the library          |\n\t\t|\t\t\t\t\t\t |\n");
              printf("\t\t|\t4.Submission of book                     |\n\t\t--------------------------------------------------");
              printf("\n\nEnter the option: ");
              scanf("%d",&i);
          switch(i)
          {
          case 1:
             printf("\t\t\tYou came for donating a book :)))\n");
             printf("\n\n\t\t\tEnter your details in the log book:\n");
             S z9;
             printf("\n\tEnter your name : ");
             fflush(stdin);
             gets(z9.name);
             fflush(stdin);
             printf("\n\tEnter your phone number : ");
             scanf("%lld",&z9.phno);
             fflush(stdin);
             printf("\n\tEnter your address : ");
             fflush(stdin);
             gets(z9.add);
             fflush(stdin);
             printf("\n\tEnter donating book name : ");
             fflush(stdin);
             gets(z9.bookname);
             printf("\n\tEnter book serial number : ");
             scanf("%d",&z9.serno);
             fflush(stdin);
             printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
             scanf("%d %d %d",&z9.d.day,&z9.d.mon,&z9.d.year);
             fflush(stdin);
             printf("\n\n\t\tThese are the details of a person who donate the book :\n\n\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",z9.name,z9.phno,z9.add,z9.bookname,z9.serno,z9.d.day,z9.d.mon,z9.d.year);
             printf("\t\t-------------------------------------------------------\n\n");
             printf("\t\tCheck your details once..");
             printf("\t\tIf it is correct press 1 or if it is wrong press 2: ");
             fflush(stdin);
             scanf("%d",&opt2);
             year=fopen("donar details.csv","a");
             fprintf(year,"%s,%lld,%s,%s,%d,%d-%d-%lld\n\n",z9.name,z9.phno,z9.add,z9.bookname,z9.serno,z9.d.day,z9.d.mon,z9.d.year);
             fclose(year);
             if(opt2==1)
              {
                  printf("\n\n\t\t\t\t***THANKS FOR DONATING A BOOK TO OUR LIBRARY***\n\n");
              }
             if(opt2==2)
             {
               goto BBJMS;
             }
              printf("\n\tIf you want to check our library books Press 1 or to exit Press 2: ");
              scanf("%d",&n1);
              if(n1==1)
                {
                  goto vipp;
                }
              break;
          case 2:
              printf("\t\t\tYou came for taking a book to home :)))\n");
              book();
              printf("\n\n\t\t\tEnter your details in the log book:\n");
              S y;
              printf("\n\tEnter your name : ");
              fflush(stdin);
              gets(y.name);
              fflush(stdin);
              printf("\n\tEnter your phone number : ");
              scanf("%lld",&y.phno);
              fflush(stdin);
              printf("\n\tEnter your address : ");
              fflush(stdin);
              gets(y.add);
              fflush(stdin);
              printf("\n\tEnter the book name : ");
              fflush(stdin);
              gets(y.bookname);
              printf("\n\tEnter book serial number : ");
              scanf("%d",&y.serno);
              fflush(stdin);
              printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
              scanf("%d %d %d",&y.d.day,&y.d.mon,&y.d.year);
              fflush(stdin);
              printf("\n\n\t\tThese are the details of a person who take the book to home :\n\n\t\t-------------------------------------------------------\n\n");
              printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",y.name,y.phno,y.add,y.bookname,y.serno,y.d.day,y.d.mon,y.d.year);
              printf("\t\t-------------------------------------------------------\n\n");
              printf("\t\tCheck your details once..");
              printf("\n\n\tIf you want to change your details press 1 or press 2 to exit");
              fflush(stdin);
              scanf("%d",&opt1);
              year=fopen("Book taker details.csv","a");
              fprintf(year,"%s,%lld,%s,%s,%d,%d-%d-%lld\n\n",y.name,y.phno,y.add,y.bookname,y.serno,y.d.day,y.d.mon,y.d.year);
              fclose(year);
              while(opt1==1)
             {
               goto LIB;
             }
              break;
          case 3:
             printf("\t\t\tYou came for reading a book in the library :)))\n");
             book();
             printf("\n\n\t\t\tEnter your details in the log book:\n");
             S y1;
             printf("\n\tEnter your name : ");
             fflush(stdin);
             gets(y1.name);
             fflush(stdin);
             printf("\n\tEnter your phone number : ");
             scanf("%lld",&y1.phno);
             fflush(stdin);
             printf("\n\tEnter your address : ");
             fflush(stdin);
             gets(y1.add);
             fflush(stdin);
             printf("\n\tEnter the book name : ");
             fflush(stdin);
             gets(y1.bookname);
             printf("\n\tEnter book serial number : ");
             scanf("%d",&y1.serno);
             fflush(stdin);
             printf("\n\tEnter the date(Eg: 17 04 2024)  : ");
             scanf("%d %d %d",&y1.d.day,&y1.d.mon,&y1.d.year);
             fflush(stdin);
             printf("\n\n\t\tThese are the details of a person who read the book in library :\n\n\t\t-------------------------------------------------------\n\n");
             printf("\t\t\tName                     : %s\n\n\t\t\tPhone Number             : %lld\n\n\t\t\tAddress                  : %s\n\n\t\t\tBook Name                : %s\n\n\t\t\tBook Serial Number       : %d\n\n\t\t\tDate                     : %d-%d-%d\n\n",y1.name,y1.phno,y1.add,y1.bookname,y1.serno,y1.d.day,y1.d.mon,y1.d.year);
             printf("\t\t-------------------------------------------------------\n\n");
             printf("\t\tCheck your details once..");
             printf("\n\n\t\tIf you want to change your details press 1 or press 2 to exit: ");
             fflush(stdin);
             scanf("%d",&opt1);
             year=fopen("Reader details.csv","a");
             fprintf(year,"%s,%lld,%s,%s,%d,%d-%d-%lld\n\n",y1.name,y1.phno,y1.add,y1.bookname,y1.serno,y1.d.day,y1.d.mon,y1.d.year);
             fclose(year);
             while(opt1==1)
             {
               goto FUSION;
             }
              break;
        case 4:
            printf("\t\t\tYou came for submission of book:)))\n\n");
            struct date d1, d2;
            int fn;
            printf("\n\n\tEnter first date of book taken (Eg:dd mm yyyy): ");
            scanf("%d %d %d", &d1.day, &d1.month, &d1.year);
            printf("\n\n\tEnter  the book returning date (Eg:dd mm yyyy): ");
            scanf("%d %d %d", &d2.day, &d2.month, &d2.year);
            printf("\n\n\tNumber of days between two dates is:   %d\n", daysBetween(d1, d2));
            if(daysBetween(d1, d2)<=60)
          {
              printf("\n\t\t\tYou have returned the book in 20 days only...  \n\n\t\t\tSo there is no fine ...\n\n\t\t\t***THANK YOU***\n");
          }
       else
       {
            printf("\n\n\tDays exceeded are         => %d",daysBetween(d1, d2) - 60);
            printf("\n\n\tFine for exceeding limit is => %d days * 5 rs\n",daysBetween(d1, d2) - 60);
            printf("\n\tYour fine has to pay is       => %d rs",(daysBetween(d1, d2) - 60) * 5);
            amount3:
            printf("\n\n\n\tEnter the amount:  ");
            scanf("%lld",&v1);
            printf("\n\n");
            if(s1==(daysBetween(d1, d2) - 60)*5)
            {
              Payment_Success();
              printf("\n\n\t\t\t\t\t*****THANK YOU*****");
            }
            else
            {
              Payment_Error();
              goto amount3;
            }
            break;
       }
    }
 }

}
    else
    {
        printf("\n\t\t\tYou are new to the library  :))))\n\n\t\t\tSo you need to known some rules!\n");
        printf("\nPress 1 to see rules:");
        scanf("%d",&b);
        printf("\n\n\tA. You Should be silent as long as you are in the library.\n\n");
        printf("\tB. There is a limited of days to take the book home\n\n\t   You should return the book before 20 days without any membership if you returned after 20 days the fine will be 30 Rs.\n\n");
        printf("\tC. If you take any book without permission is like a thefting, will cause 1000 Rs fine.\n\n");
        printf("\tD. If you miss the taken book, it will be fined as 500 Rs.\n\n");
        printf("\tE. If the book is taken by you and got damaged means, the fine will be 300 Rs.\n\n");
        printf("\tAnd then we have some memberships also\n\n");
        printf("\tPress 2 to see memberships:");
        scanf("%d",&c);
        printf("\n\n\t\t----------------------------------------------------\n\t\t|\t        CHOOSE THE MEMBERSHIP\t\t   |\n\t\t|--------------------------------------------------|\n");
        printf("\t\t|\t\t1.Student Membership\t           |\n\t\t|\t\t\t\t\t\t   |\n\t\t|\t\t2.Weekly Membership\t           |\n\t\t|\t\t\t\t\t\t   |\n");
        printf("\t\t|\t\t3.Monthly Membership\t           |\n\t\t|\t\t\t\t\t\t   |\n\t\t|\t\t4.VIP Membership\t\t   |\n\t\t----------------------------------------------------");
        printf("\n\n\t\tIf you want to take any membership press 3 or else you want to continue without membership press 4:");
        scanf("%d",&d);
        if(d==3)
        {
        printf("\n\n\t\tEnter your membership:");
        scanf("%d",&opt);
        }
        else{
            printf("\n\n\t\t\tNo need any membership...\n\n\t\t\t***THANK YOU***");
            printf("\n\n\t\tIf you want to see ours books press any key to continue\n\n");
            getch(p1);
            book();
        }

        switch(opt)
        {
        case 1:
            printf("\n\n\t\t\tYou have selected the Student membership pass:)))\n\n");
            printf("\t->For this student pass you have to pay 400 Rs.\n\n\t->And also you should have your student id card\n\n");
            printf("\t->We will provide student pass number.\n\n");
            printf("\t\t\tFor taking student pass you have some benefits....\n\n");
            printf("\t\t->You will not be fined until 20 days\n\n\t\t->You can took any book to your home\n\n");
            printf("\t->A fine of 10 Rs will be charged If you bring the after 20 days");
            printf("\n\n\t\tIf you want to take this membership\n\n");
            stumem();
            goto libfusion;
            break;
        case 2:
            printf("\n\n\t\t\tYou have selected the Weekly membership pass:)))\n\n");
            printf("\t->For this Weekly pass you have to pay 50 Rs.\n\n");
            printf("\t->We will provide weekly membership pass number.\n\n");
            printf("\t\t\tFor taking Weekly pass you have some benefits....\n\n");
            printf("\t\t->For this pass you have access time from 10AM to 8PM for the whole week.\n\n");
            printf("\t\t->You will be not fined until 7 days.\n\n\t->A fine of 20 Rs will be charged If you bring after 7 days.");
            printf("\n\n\t\tIf you want to take this membership\n\n");
            weekmem();
            goto libfusion;
            break;
        case 3:
            printf("\n\n\t\t\tYou have selected the Monthly membership pass:)))\n\n");
            printf("\t->For this Monthly pass you have to pay 200 Rs.\n\n");
            printf("\t->We will provide Monthly membership pass number.\n\n");
            printf("\t\t\tFor taking Monthly pass you have some benefits....\n\n");
            printf("\t\t->For this pass you have access time from 10AM to 8PM for the whole Month.\n\n\t\t->With this monthly membership you can also come and study on Sundays.");
            printf("\n\n\t\t->You will be not fined until 30 days\n\n\t->A fine of 15 Rs will be charged If you bring after 30 days");
            printf("\n\n\t\tIf you want to take this membership\n\n");
            monmem();
            goto libfusion;
            break;
        case 4:
             printf("\n\n\t\t\tYou have selected the VIP membership pass:)))\n\n");
            printf("\t->For this VIP pass you have to pay 1500 Rs\n\n");
            printf("\t->We will provide VIP membership pass number.\n\n");
            printf("\t\t\tFor taking VIP pass you have some benefits\n\n");
            printf("\t\t->You can use this VIP pass for a whole year.\n\n\t\t->For this pass you have access time from 10AM to 8PM for the whole year.\n\n ");
            printf("\t\t->You will be not fined until 60 days\n\n\t->A fine of 5 Rs will be charged If you bring after 60 days");
            printf("\n\n\t\tIf you want to take this membership\n\n");
            vipmem();
            goto libfusion;
            break;
        case 5:
            printf("\t\t\tYou came for submission of book:)))\n\n");
            struct date d1, d2;
            int fn;
            printf("\n\n\tEnter first date of book taken (Eg: dd mm yyyy): ");
            scanf("%d %d %d", &d1.day, &d1.month, &d1.year);
            printf("\n\n\tEnter  the book returning date (Eg: dd mm yyyy): ");
            scanf("%d %d %d", &d2.day, &d2.month, &d2.year);
            printf("\n\n\tNumber of days between two dates is        :   %d\n", daysBetween(d1, d2));
            if(daysBetween(d1, d2)<=20)
           {
             printf("\n\t\t\tYou returned the book in 20 days only  \n\n\t\t\tSo there is no fine ...\n\n\t\t\t\t***THANK YOU***\n\n");
           }
           else
           {
            printf("\n\n\tDays exceeded are           => %d",daysBetween(d1, d2) - 20);
            printf("\n\n\tFine for exceeding limit is => %d days * 30 rs\n",daysBetween(d1, d2) - 20);
            printf("\n\tYour fine has to pay is       => %d rs",(daysBetween(d1, d2) - 20) * 30);
            printf("\n\n\n\tEnter the amount:  ");
            scanf("%lld",&ss1);
            printf("\n\n");
            Payment_Success();
            printf("\n\n\t\t\t*****THANK YOU*****");
            break;
           }
       }
    }
          int rating;
          printf("\n\n\t\t   ------Please give your valuable rating on our BBJMS library------");
          rating:
          printf("\n\n\t\t\tGive your rating from 1-5 out of 5 stars : ");
          scanf("%d",&rating);
     switch(rating)
    {
    case 1:
        printf("\n\t\t\tYou rated us : *");
        break;
    case 2:
        printf("\n\t\t\tYou rated us : **");
        break;
    case 3:
        printf("\n\t\t\tYou rated us : ***");
        break;
    case 4:
        printf("\n\t\t\tYou rated us : ****");
        break;
    case 5:
        printf("\n\t\t\tYou rated us  : *****");
        break;
    default :
            printf("\n\t\t\tEnter between 1 to 5 only.......");
            goto rating;
            break;
    }
    printf("\n\n\n\t\t\t\t\tThanks for your rating..... \n\n\t\t\t\t****  It is most precious to us ****\n\n");
    printf("\t\t\t\t\tVISIT AGAIN..........:)))\n\n");
}
//FUNCTIONS USED
void book()
{
   int book,j,k,l,m,t,u,v,w,x,j1,k1,l1;
   printf("\n\n\t1.Electronics and Communication Engineering\n\n\t2.Computer Science Engineering\n\n\t3.Civil Engineering\n\n\t4.Comics Books\n\n\t5.Horror&Mystery Books\n\n\t6.Science Fiction\n\n\t7.Biography Books\n\n\t8. Psychology Books\n\n\t9.Crime Books\n\n\t10.Poetry Books\n\n\t11.Languages Book\n\n");
   printf("\t\tEnter the your Selected module:");
   scanf("%d",&j);
   switch(j)
   {
   case 1:
    printf("\n\n\t\t\tYou selected Electronics.....\n\n");
    printf("\t1001.Electronic Devices&CKT Theory\n\n\t1002.Micro Electronic Circuits\n\n\t1003.Digital Logic& Computer Design\n\n\t1004.Communication Systems\n\n\t1005.Control System Engineering\n\n");
    printf("\t1006.Digital Signal Processing\n\n\t1007.Telecommunication Systems\n\n\t1008.Digital Electronics and Microprocessors\n\n\t1009.Embedded Systems\n\n\t1010.Analog& Digital Electronics\n\n");
    serial1:
    printf("\t\tEnter your selected book serial number:");
    scanf("%d",&k);
    printf("\n\n\tYou have choosen:");
    switch(k)
    {
    case 1001:
        printf("Electronic Devices&CKT Theory\n");
        break;
    case 1002:
        printf("Micro Electronic Circuits\n");
         break;
    case 1003:
        printf("Digital Logic& Computer Design\n");
         break;
    case 1004:
        printf("Communication Systems\n");
         break;
    case 1005:
        printf("Control System Engineering\n");
         break;
    case 1006:
        printf("Digital Signal Processing\n");
         break;
    case 1007:
        printf("Telecommunication Systems\n");
        break;
    case 1008:
        printf("Digital Electronics and Microprocessors\n");
         break;
    case 1009:
        printf("Embedded Systems\n");
         break;
    case 1010:
        printf("Analog& Digital Electronics\n");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number...\n\n");
        while(k!=(k>1010))
        {
          printf("\t\tPlease enter a valid serial number....\n\n");
          goto serial1;
        }
        break;
    }
    break;
    case 2:
        printf("\n\n\t\t\tYou selected Computer science.....\n\n");
        printf("\t2001.Introduction to algorithms\n\n\t2002.Operating System Concepts\n\n\t2003.Database Systems\n\n\t2004.Computer Networks\n\n\t2005.Software Engineering\n\n");
        printf("\t2006.Datastructure & Algorithms in c++\n\n\t2007.Computer Architecture\n\n\t2008.Artifical Intelligence\n\n\t2009.Machine Learning\n\n\t2010.Cryptography & Network Security\n\n");
        serial2:
        printf("\t\tEnter your selected book serial number:");
        scanf("%d",&l);
        printf("\n\n\tYou have choosen:");
    switch(l)
    {
    case 2001:
        printf("Introduction to algorithms\n");
        break;
    case 2002:
        printf("Operating System Concepts\n");
         break;
    case 2003:
        printf("Database Systems\n");
         break;
    case 2004:
        printf("Computer Networks\n");
         break;
    case 2005:
        printf("Software Engineering\n");
         break;
    case 2006:
        printf("Datastructure & Algorithms in c++\n");
         break;
    case 2007:
        printf("Computer Architecture\n");
        break;
    case 2008:
        printf("Artifical Intelligence\n");
         break;
    case 2009:
        printf("Machine Learning\n");
         break;
    case 2010:
        printf("Cryptography & Network Security\n");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number...\n\n");
        while(k!=(k>2010))
        {
          printf("\t\tPlease enter a valid serial number....\n\n");
          goto serial2;
        }
        break;
    }
    break;
    case 3:
       printf("\n\n\t\t\tYou selected Civil.....\n\n");
       printf("\t3001.Structural Analysis\n\n\t3002.Steel Structures\n\n\t3003.Reinforced Concrete Design\n\n\t3004.Fluid Mechanics\n\n\t3005.Irrigation Engineering\n\n");
       printf("\t3006.Surveying & Levelling\n\n\t3007.Geo technical Engineering\n\n\t3008.Environmental Engineering\n\n\t3009.Building Materials\n\n\t3010.Structural Steel Design\n\n");
       serial3:
       printf("\t\tEnter your selected book serial number:");
       scanf("%d",&m);
       printf("\n\n\tYou have choosen:");
    switch(m)
    {
    case 3001:
        printf("Structural Analysis\n");
        break;
    case 3002:
        printf("Steel Structures\n");
         break;
    case 3003:
        printf("Reinforced Concrete Design\n");
         break;
    case 3004:
        printf("Fluid Mechanics\n");
         break;
    case 3005:
        printf("Irrigation Engineering\n");
         break;
    case 3006:
        printf("Surveying & Leveling\n");
         break;
    case 3007:
        printf("Geo technical Engineering\n");
        break;
    case 3008:
        printf("Environmental Engineering\n");
         break;
    case 3009:
        printf("Building Materials\n");
         break;
    case 3010:
        printf("Structural Steel Design\n");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>3010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial3;
        }
        break;
    }
    break;
    case 4:
         printf("\n\n\t\t\tYour Selected Comics.....\n\n");
         printf("\t4001.Batman(Dc Comic)\n\n\t4002.Super-Man(Dc Comic)\n\n\t4003.The Avengers(Marvel Comic)\n\n\t4004.Captain Marel(Marvel Comic)\n\n\t4005.Hellyboy\n\n");
         printf("\t4006.Sin City(Dark Horse Comic)\n\n\t4007.Pogo\n\n\t4008.Peanuts\n\n\t4009.Little Nemo\n\n\t4010.Garfield\n\n");
         serial4:
         printf("\t\tEnter your selected book serial number:");
         scanf("%d",&l1);
         printf("\n\n\tYou have choosen:");
    switch(l1)
    {
    case 4001:
        printf("Batman(Dc Comic)\n");
        break;
    case 4002:
        printf("Super-Man(Dc Comic)\n");
         break;
    case 4003:
        printf("The Avengers(Marvel Comic)\n");
         break;
    case 4004:
        printf("Captain Marel(Marvel Comic)\n");
         break;
    case 4005:
        printf("Hellyboy\n");
         break;
    case 4006:
        printf("Sin City(Dark Horse Comic)\n");
         break;
    case 4007:
        printf("Pogo\n");
        break;
    case 4008:
        printf("Peanuts\n");
         break;
    case 4009:
        printf("Little\n");
         break;
    case 4010:
        printf("Garfield\n");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>4010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial4;
        }
        break;
    }
    break;
     case 5:
         printf("\n\n\t\t\tYou selected Horror&Mystery.....\n\n");
         printf("\t5001.Dracula(Clauic Horror)\n\n\t5002.The Exorcist(Modern Horror)\n\n\t5003.The Conjuring(Paranormal Horror)\n\n\t5004.The fall of the House of usher\n\n\t5005.The shining(Modern Horror)\n\n");
         printf("\t5006.The Haunting of Hill House(Paranormal Horror)\n\n\t5007.The Vampire Lestat(Super Natural)\n\n\t5008.Gone Girl\n\n\t5009.The Lincoln Rhyme\n\n\t5010.The Girl with the Dragon tattoo\n\n");
         serial5:
         printf("\t\tEnter your selected book serial number:");
         scanf("%d",&t);
         printf("\n\n\tYou have choosen:");
    switch(t)
    {
    case 5001:
        printf("Dracula(Clauic Horror)\n");
        break;
    case 5002:
        printf("The Exorcist(Modern Horror)\n");
         break;
    case 5003:
        printf("The Conjuring(Paranormal Horror)\n");
         break;
    case 5004:
        printf("The fall of the House of usher\n");
         break;
    case 5005:
        printf("The shining(Modern Horror)\n");
         break;
    case 5006:
        printf("The Haunting of Hill House(Paranormal Horror)\n");
         break;
    case 5007:
        printf("The Vampire Lestat(Super Natural)\n");
        break;
    case 5008:
        printf("Gone Girl\n");
         break;
    case 5009:
        printf("The Lincoln Rhyme\n");
         break;
    case 5010:
        printf("The Girl with the Dragon tattoo\n");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>5010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial5;
        }
        break;
    }
    break;
    case 6:
        printf("\n\n\t\t\tYou selected Science fiction.....\n\n");
        printf("\t6001.The Load of the Rings\n\n\t6002.The Power\n\n\t6003.Dune\n\n\t6004.The HandMaid's Tale\n\n\t6005.The Martain\n\n");
        printf("\t6006.The Name of the wind\n\n\t6007.The Three-Body Problem\n\n\t6008.The war of the Worlds\n\n\t6009.Brave New Worlds\n\n\t6010.Neuromancer\n\n");
        serial6:
        printf("\t\tEnter your selected book serial number:");
        scanf("%d",&u);
        printf("\n\n\tYou have choosen:");
    switch(u)
    {
    case 6001:
        printf("The Load of the Rings\n");
        break;
    case 6002:
        printf("The Power\n");
         break;
    case 6003:
        printf("Dune\n");
         break;
    case 6004:
        printf("The HandMaid's Tale\n\n");
         break;
    case 6005:
        printf("The Martain\n\n");
         break;
    case 6006:
        printf("The Name of the wind\n\n");
         break;
    case 6007:
        printf("The Three-Body Problem\n\n");
        break;
    case 6008:
        printf("The war of the Worlds\n\n");
         break;
    case 6009:
        printf("Brave New Worlds\n\n");
         break;
    case 6010:
        printf("Neuromancer\n\n");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>6010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial6;
        }
        break;
    }
    break;
    case 7:
        printf("\n\n\t\t\tYou selected Biography.....\n\n");
        printf("\t7001.Abraham Lincoln\n\n\t7002.The Wright Brothers\n\n\t7003.Charless Darwin\n\n\t7004.Marie Curie\n\n\t7005.Cleopatra\n\n");
        printf("\t7006.The Brontes\n\n\t7007.The Life of Shakespeare\n\n\t7008.The Life of virginia woolf\n\n\t7009.Steve Jobs\n\n\t7010.Long Walk to Freedom\n\n");
        serial7:
        printf("\t\tEnter your selected book serial number:");
        scanf("%d",&v);
        printf("\n\n\tYou have choosen:");
    switch(v)
    {
    case 7001:
        printf("Abraham Lincoln\n\n");
        break;
    case 7002:
        printf("The Wright Brothers\n\n");
         break;
    case 7003:
        printf("Charless Darwin\n\n");
         break;
    case 7004:
        printf("Marie Curie\n\n");
         break;
    case 7005:
        printf("Cleopatra\n\n");
         break;
    case 7006:
        printf("The Brontes\n\n");
         break;
    case 7007:
        printf("The Life of Shakespeare\n\n");
        break;
    case 7008:
        printf("The Life of virginia woolf\n\n");
         break;
    case 7009:
        printf("Steve Jobs\n\n");
         break;
    case 7010:
        printf("Long Walk to Freedom\n\n");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>7010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial7;
        }
        break;
    }
    break;
    case 8:
        printf("\n\n\t\t\tYou selected Psychology.....\n\n");
        printf("\t8001.The Ego and the Id\n\n\t8002.Man's search for meaning\n\n\t8003.The Power of Habit\n\n\t8004.The Whole-Brain Child\n\n\t8005.The Gift of Fear\n\n");
        printf("\t8006.The Social Animal\n\n\t8007.The Lucifer effect \n\n\t8008.An Unquiet mind\n\n\t8009.The Developing Mind\n\n\t8010.Influence:The Psychology of Persuasion\n\n");
        serial8:
        printf("\t\tEnter your selected book serial number:");
        scanf("%d",&w);
        printf("\n\n\tYou have choosen:");
    switch(w)
    {
    case 8001:
        printf("The Ego and the Id\n\n");
        break;
    case 8002:
        printf("Man's search for meaning\n\n");
         break;
    case 8003:
        printf("The Power of Habit\n\n");
         break;
    case 8004:
        printf("The Whole-Brain Child\n\n");
         break;
    case 8005:
        printf("The Gift of Fear\n\n");
         break;
    case 8006:
        printf("The Social Animal\n\n");
         break;
    case 8007:
        printf("The Lucifer effect\n\n");
        break;
    case 8008:
        printf("An Unquiet mind\n\n");
         break;
    case 8009:
        printf("The Developing Mind\n\n");
         break;
    case 8010:
        printf("Influence:The Psychology of Persuasion\n\n");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>8010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial8;
        }
        break;
    }
    break;
     case 9:
        printf("\n\n\t\t\tYou selected Crime......\n\n");
        printf("\t9001.In Cold Blood\n\n\t9002.The Bone Women\n\n\t9003.The Poisoner Handbook\n\n\t9004.All that remains\n\n\t9005.The last victim\n\n");
        printf("\t9006.The cases that Hunt us\n\n\t9007.Deadman to tell Tales \n\n\t9008.The Girl with Dragon Tattoo\n\n\t9009.Sharp Objects\n\n\t9010.Helter Skelter\n\n");
        serial9:
        printf("\t\tEnter your selected book serial number:");
        scanf("%d",&x);
        printf("\n\n\tYou have choosen:");
    switch(x)
    {
    case 9001:
        printf("\n\nIn Cold Blood");
        break;
    case 9002:
        printf("\n\nThe Bone Women");
         break;
    case 9003:
        printf("\n\nThe Poisoner Handbook");
         break;
    case 9004:
        printf("\n\nAll that remains");
         break;
    case 9005:
        printf("\n\nThe last victim");
         break;
    case 9006:
        printf("\n\nThe cases that Hunt us");
         break;
    case 9007:
        printf("\n\nDeadman to tell Tales");
        break;
    case 9008:
        printf("\n\nThe Girl with Dragon Tattoo");
         break;
    case 9009:
        printf("\n\nSharp Objects");
         break;
    case 9010:
        printf("\n\nHelter Skelter");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>9010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial9;
        }
        break;
    }
    break;
    case 10:
        printf("\n\n\t\t\tYour Selected Poetry.....\n\n");
        printf("\t10001.The Divine Comedy\n\n\t10002.The Waste Land\n\n\t10003.The Penguin book\n\n\t10004.The Canterbury Tales\n\n\t10005.The Iliad and the odyssey\n\n");
        printf("\t10006.The Harvard Anthology\n\n\t10007.Leaves of Grass\n\n\t10008.The Bell Jar\n\n\t10009.The Cantos\n\n\t10010.Citizen:An American Lyric\n\n");
        serial10:
        printf("\t\tEnter your selected book serial number:");
        scanf("%d",&j1);
        printf("\n\n\tYou have choosen:");
    switch(j1)
    {
    case 10001:
        printf("\n\nThe Divine Comedy");
        break;
    case 10002:
        printf("\n\nThe Waste Land");
         break;
    case 10003:
        printf("\n\nThe Penguin book");
         break;
    case 10004:
        printf("\n\nThe Canterbury Tales");
         break;
    case 10005:
        printf("\n\nThe Iliad and the odyssey");
         break;
    case 10006:
        printf("\n\nThe Harvard Anthology");
         break;
    case 10007:
        printf("\n\nLeaves of Grass");
        break;
    case 10008:
        printf("\n\nThe Bell Jar");
         break;
    case 10009:
        printf("\n\nThe Cantos");
         break;
    case 10010:
        printf("\n\nCitizen:An American Lyric");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>10010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial10;
        }
        break;
    }
    break;
    case 11:
        printf("\n\n\t\t\tYou selected Languages Books.....\n\n");
        printf("\t11001.The Oxford English Dictionary\n\n\t11002.Merriam-Webster's Dictionary\n\n\t11003.Spanish for Dummies\n\n\t11004.French for Dummies\n\n\t11005.German for Dummies\n\n");
        printf("\t11006.Chinese for Dummies\n\n\t11007.Arabic for Dummies\n\n\t11008.French in 10 Minutes a Day\n\n\t11009.Barron's German Grammar\n\n\t11010.Korean for Beginners\n\n");
        serial11:
        printf("\t\tEnter your selected book serial number:");
        scanf("%d",&k1);
        printf("\n\n\tYou have choosen:");
     switch(k1)
    {
    case 11001:
        printf("\n\nThe Oxford English Dictionary");
        break;
    case 11002:
        printf("\n\nMerriam-Webster's Dictionary");
         break;
    case 11003:
        printf("\n\nSpanish for Dummies");
         break;
    case 11004:
        printf("\n\nFrench for Dummies");
         break;
    case 11005:
        printf("\n\nGerman for Dummies");
         break;
    case 11006:
        printf("\n\nChinese for Dummies");
         break;
    case 11007:
        printf("\n\nArabic for Dummies");
        break;
    case 11008:
        printf("\n\nFrench in 10 Minutes a Day");
         break;
    case 11009:
        printf("\n\nBarron's German Grammar");
         break;
    case 11010:
        printf("\n\nKorean for Beginners");
         break;
    default:
        printf("\t\tYou entered a invalid Serial Number\n\n");
        while(k!=(k>11010))
        {
          printf("\t\tPlease enter a valid serial number\n\n");
          goto serial11;
        }
        break;
    }
    break;

    }
}
void stumem()
{
    int stu=400,pay;
    payment:
    printf("\n\tFor this you have to pay 400 Rs\n\n");
    printf("\tEnter the amount your paying:");
    scanf("%d",&pay);
    printf("\n");
    if(pay==stu)
    {
        Payment_Success();
        printf("\n\n\t\t\tNow you are a student membership pass holder.....\n\n");
        printf("\t\t\tThis is your student pass number is ---1122---\n\n");
        printf("\t\t\t\t***THANK YOU***\n\n");
    }

    else
    {
        Payment_Error();
            goto payment;

     }

}
void weekmem()
{
    int wee=50,pay;
    payment:
    printf("\n\tFor this you have to pay 50 Rs\n\n");
    printf("\tEnter the amount your paying:");
    scanf("%d",&pay);
    if(pay==wee)
    {
        Payment_Success();
        printf("\n\n\t\t\tNow you are a weekly membership pass holder.....\n\n");
        printf("\t\t\tThis is your weekly pass number is ---1123---\n\n");
        printf("\t\t\t\t***THANK YOU***\n\n");
    }
    else
    {
        Payment_Error();
            goto payment;

    }

}
void monmem()
{
    int mon=200,pay;
    payment:
    printf("\n\tFor this you have to pay 200 Rs\n\n");
    printf("\tEnter the amount your paying:");
    scanf("%d",&pay);
    if(pay==mon)
    {
        Payment_Success();
        printf("\n\n\t\t\tNow you are a monthly membership pass holder.....\n\n");
        printf("\t\t\tThis is your monthly pass number is ---1124---\n\n");
        printf("\t\t\t\t***THANK YOU***\n\n");
    }
    else
    {
        Payment_Error();
            goto payment;

    }

}
void vipmem()
{
    int vip=1500,pay;
    payment:
    printf("\n\tFor this you have to pay 1500 Rs\n\n");
    printf("\tEnter the amount your paying:");
    scanf("%d",&pay);
    if(pay==vip)
    {
        Payment_Success();
        printf("\n\n\t\t\tNow you are a VIP membership pass holder.....\n\n");
        printf("\t\t\tThis is your VIP pass number is ---1125---\n\n");
        printf("\t\t\t\t***THANK YOU***\n\n");
    }
    else
    {
        Payment_Error();
            goto payment;

    }
}
int daysBetween(struct date d1, struct date d2)
{
    int t1 = d1.year*365 + d1.day;
    for (int i = 0; i < d1.month - 1; i++)
        if (i == 1) {
            if (d1.year % 4 == 0 && d1.year % 100 != 0 || d1.year % 400 == 0)
                t1 += 29;
            else
                t1 += 28;
        }
        else if (i == 3 || i == 5 || i == 8 || i == 10)
            t1 += 30;
        else
            t1 += 31;

    int t2 = d2.year*365 + d2.day;
    for (int i = 0; i < d2.month - 1; i++)
        if (i == 1) {
            if (d2.year % 4 == 0 && d2.year % 100 != 0 || d2.year % 400 == 0)
                t2 += 29;
            else
                t2 += 28;
        }
        else if (i == 3 || i == 5 || i == 8 || i == 10)
            t2 += 30;
        else
            t2 += 31;

    return t2 - t1;
}
void Payment_Success(char x[],char y[])
{
     char a[15]={'L','o','a','d','i','n','g','.','.','.'};//10
        for(int i=1;i<2;i++)
           {
            printf("\n\n");
            printf("\t\t\r__________\r");//22
            for(int j=0;j<=10;j++)
               {
                printf("%c ",a[j]);
                usleep(300000);
                }
              char b[30]={'Y','o','u','r',' ','P','a','y','m','e','n','t',' ','S','u','c','e','s','s','f','u','l',':',')'};//24
                for(int i=1;i<=1;i++)
                    {
                     printf("\r                       \r");
                for(int j=0;j<24;j++)
                    {
                     printf("%c",b[j]);
                     usleep(100000);
                    }
                    }
            }
}
void Payment_Error(char e[],char f[])
{
    char c[15]={'L','o','a','d','i','n','g','.','.','.'};//10
        for(int i=1;i<2;i++)
           {
               printf("\n\n");
            printf("\t\t\r__________\r");//22
            for(int j=0;j<=10;j++)
               {
                printf("%c ",c[j]);
                usleep(300000);
                }
                char d[30]={'P','a','y','m','e','n','t',' ','e','r','r','o','r'};//13
                for(int i=1;i<=1;i++)
                    {
                    printf("\r                    \r");
                for(int j=0;j<13;j++)
                    {
                     printf("%c",d[j]);
                     usleep(200000);
                    }
                    }
                    printf("\n");
            }
}



