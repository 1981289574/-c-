#include"stdio.h"
#include"math.h"
main()
{double a,b,c,p,s;
printf("input to a,b,c:");
scanf("%lf%lf%lf,",&a,&b,&c);
  if(a+b>c&&a+c>b&&b+c>a)
     {p=(a+b+c)/2;
      s=sqrt(p*(p-a)*(p-b)*(p-c));
     printf("s=%f\n",s);}
  else printf("三条边组不成三角形。\n");
}
