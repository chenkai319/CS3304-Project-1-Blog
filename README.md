# CS3304-Project-1-Blog
Hey guys! Roman Numeral is one of the first things in math that is taught to American children after basic math skills – at least it was for me and my time with the education system. The purpose of this blog is to demonstrate how to convert roman numeral to decimal numeral and vice versa. The second part of this blog is to demonstate the stocks-trade through domain-specific language and hope you can be a minillionaire in the future. If you find the second part of this blog very helpful and will assist you becoming rich, Please feel free to donate us (renc2@vt.edu and ruipu98@vt.edu). We are definetely poor programmers. Anyway, I will begain tell you some about our conversion from roman to decimal numeral. 


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
M=1000


I will be using Java programming language to code this problem. A Roman numeral represents an integer using letters. 
Therefore we first determine if the input from user is a valid string.\
(1) letters (Only M D C L X V I can be accepted)\
(2) numbers

In Java, there is a buit-in function called `<String.matches("regex")>` which can check if a certain string have that regex format. 

Later I have two functions called decimalToRoman(String) and romanToDecimal(String) which did the conversion for roman to decimal or decimal to roman. 

For part two of this program, we have special cases and they need different output. 

Part two main function is aureliusRules() which checks the three cases given in the instruction. 

One struggle in this function is to insert a emoji in java string. I had a hard time finding the correct emoji for bear, frog, and horse.

Later I found them by talking to one of the teaching assistant. She was really helpful.
For instance, in order to print a emoji to the console. You will need to call Character.toChars(hex).

     horse = 0x1f434 
     dog   = 0x1f436 
     frog  = 0x1f438 

For Question 2:

The second problem is pretty interesting since it is about building something related to a stock company. I personally love to have some experience about stock in the future. The grammar gave me some headache when I took the first glance at it, it is pretty confusing to understand the meaning of each part. Then I saw the hint to take an extra notice about “<>”, I figured out the meaning of the grammar which is pretty exciting!! I chose Python as the language for this problem since it does not require specific instruction and relatively loose language comparing to other languages. As soon as I stepped into the problem, I realized the key point to start with this problem is to find a good way to parse the input. I started to pay attention to some unique characters in this input, such as “(”, “””. And I wrote one input example on my notebook and uses different highlighters to differentiate the different parts in order to demonstrate my coding logic. This is pretty useful and straightforward to me, I may use this approach as well to help me better and quicker understand a problem.


Link: https://github.com/chenkai319/CS3304-Project-1-Blog/edit/master/README.md
