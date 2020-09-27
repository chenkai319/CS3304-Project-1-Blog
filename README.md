# CS3304-Project-1-Blog
Hey guys! Roman Numeral is one of the first things in math that is taught to American children after basic math skills – at least it was for me and my time with the education system. The purpose of this blog is to demonstrate how to convert roman numeral to decimal numeral and vice versa. The second part of this blog is to demonstate the stocks-trade through domain-specific language and hope you can be a minillionaire in the future. If you find the second part of this blog very helpful and will assist you becoming rich, Please feel free to donate us (renc2@vt.edu and ruipu98@vt.edu). We are definetely poor programmers. Anyway, I will begain tell you some about our conversion from roman to decimal numeral. \


Here is the system:

I =1\
II =2\
III =3\
IIII =4\
V=5\
VI=6\
VII =7\
VIII =8\
IX =9\
X =10\
XX=20\
XXX =30\
XL=40\
L=50\
LX=60\
LXX=70\
LXXX=80\
XC=90\
C=100\
D = 500\
M=1000\


I will be using Java programming language to code this problem. A Roman numeral represents an integer using letters. 
Therefore we first determine if the input from user is a valid string. \
(1) letters (Only M D C L X V I can be accepted)\
(2) numbers\

In Java, there is a buit-in function called `<String.matches("regex")>` which can check if a certain string have that regex format. 
