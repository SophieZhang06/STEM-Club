#include<stdio.h>


int main()

{

int a,b,c;

double sum;

printf("\n**********");

printf("\nSophie Zhang's STEM Club Proposal\n");

printf("\n**********");

printf("\nContents: \n 1.PHYSICS \n 2.CHEMISTRY \n 3.EARTH SCIENCE \n");

scanf("%d",&a);

switch (a)

{

case 1:

printf("\n**********");

printf("\nPHYSICS\n 1.SALTWATER EGG FLOAT\n 2.STATIC ELECTRICITY FAN \n 3.FLOATING FISH \n 4.RAINBOW DENSITY EXPERIMENT \n 5.LIGHT REFRACTION IN WATER \n");

scanf("%d",&b);

switch (b)

{

case 1:

printf("\n**********");

printf("\n1: SALTWATER EGG FLOAT (PHYSICS)\nMaterials:\n Eggs\n Salt\n Water Cups and spoons\n");
printf("\nLesson plan:\n Introduce experiment (5 minutes)\n Discuss science and demonstrate (10 minutes)\n Students do experiment (20 minutes)\n Place an egg in plain water and it sinks\n Add spoonful of salt into water and stir\n Watch as egg rises and float\n Clean up (10 minutes)\n");

printf("\nQuestions to ask students:\n What do you think happens next?\n Why does the balloon inflate?\n");

printf("\nScience:\n Salt water is denser than fresh water.\n The egg floats when the liquid density is greater than the egg's density\n");break;

case 2:sum=5*c;break;

case 3:sum=4*c;break;

}

break;

case 2:

printf(" ");

scanf("%d",&b);

printf("：\n");

scanf("%d",&c);

switch (b)

{

case 1:sum=4.5*c;break;

case 2:sum=6*c;break;

case 3:sum=4*c;break;

}

break;

case 3:

printf("\n ");

scanf("%d",&b);

printf("\n");

scanf("%d",&c);

switch (b)

{

case 1:sum=2.5*c;break;

case 2:sum=3*c;break;

case 3:sum=2.5*c;break;

}

break;
}
}
