github profile markdown generator logo
GitHub Profile README Generator
Star this repo
21038
Fork on GitHub
6524

back to edit

copy-markdown

download markdown

download backup

preview
<h1 align="center">Hi 👋, I'm Navadeep Goud</h1>
<h3 align="center">A passionate Btech student from India</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=navadeepgoud12&label=Profile%20views&color=0e75b6&style=flat" alt="navadeepgoud12" /> </p>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=navadeepgoud12" alt="navadeepgoud12" /></a> </p>

- 🌱 I’m currently learning **HTML,frame works,CSS, Java script**

- 📫 How to reach me **9deepgoud@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/kishtammagari navadeep goud" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="kishtammagari navadeep goud" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=navadeepgoud12&show_icons=true&locale=en&layout=compact" alt="navadeepgoud12" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=navadeepgoud12&show_icons=true&locale=en" alt="navadeepgoud12" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=navadeepgoud12&" alt="navadeepgoud12" /></p>

Support 🙏
Are you using the tool and happy with it to create your GitHub Profile?
Your kind support keeps open-source tools like this free for others.
tweet github profile readme generator
Let the world know how you feel using this tool. Share with others on twitter.
Tip💰
Buy ko-fi for rahuldkjainBuy me a ko-fi
Donate rahuldkjain via paypal
Buy rahuldkjain A CoffeeBuy me a coffee
github profile markdown generator logo
GitHub Profile README Generator
Pages
Addons
Support
About
More
Github
Releases
Issues
Pull Requests
Join Community
Discord of the community
Developed in India 🇮🇳
Buy Me A Coffee

#include<stdio.h>
#include<string.h>
void offer();
void season();
int main()
{
int i;
char a[20];
char b[20];
printf(".....WELL COME TO THE ONLINE SHOPING OFFER.....");
printf("\n Enter the fashion wear");
gets(a);
if(strcmp(a,"men")==0)
{
printf("enter what do you what");
gets(b);
if(strcmp(b,"shirts")==0)
{
offer();
season();
}
else if(strcmp(b,"jeans")==0)
{
offer();
season();
}
else if(strcmp(b,"tshirts")==0)
{
offer();
season();
}
else
{
printf("\n we can't found but the offers are :");
offer();
}
}

else if(strcmp(b,"women")==0)
{gets(b);
 if(strcmp(b,"sarees")==0)
{
printf("aditionally 5% discount");
offer();
season();
}
else if((b,"kurthis")==0)
{
printf("Buy three get 1 free");
offer();
season();
}
else if((b,"westron")==0)
{
printf("buy three jeans get one top free");
offer();
season();
}
else
{
printf("\n we can't found but the offers are :");
offer();
}
}
else if(strcmp(b,"kids")==0)
{
gets(b);
if(strcmp(b,"boys")==0)
{
offer();
season();
}
else if((b,"girls")==0)
{
printf("Buy three get 1 free");
offer();
season();
}
}
else
{
printf("\n we can't found but the offers are :");
offer();
}
}
void offer()
{
int p;
printf("enter the prize to purchase");
scanf("%d",&p);
if(p>=1000 && p<=2000)
{
printf("10% discount on your puchase");
}
else if(p>2000 && p<=3000)
{
printf("20% discount on your puchase");
}
else if(p>3000 && p<=6000)
{
printf("30% discount on your purchase");
}
else if(p>10000)
{
printf("40% discount on your purchase");
}
else
{
printf("no offers on your purchase");
}

}
void season()
{
int m;
printf("enter the month");
scanf("%d",&m);
if(m>=1 && m<=4)
{
printf("*** NEW YEAR AND UGADHI OFFER*");
}
else if(m>=5 && m<8)
{
printf("*** ASHADAM AND SRAVANAM*");
}
else 
{
printf("*** DASARA AND DIWALI");
}

}
