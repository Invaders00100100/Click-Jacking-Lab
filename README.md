1) Navigate to the directory containing the Script

2) Double click the attacker.html file 

3) Click The Button to trigger the attack

The Walkthrough is available on Youtube:

https://www.youtube.com/watch?v=pPmWjfAJ1Nc

Support My Work With A Cup Of Coffee

![CashTag$](https://github.com/user-attachments/assets/9d25ed0d-aa28-4e09-915a-ebc102b31b7a)

ATTACK EXPLAINED:
	
The attacker.html page has no fuctionality at all in it of itself. Its litterally 

just decoration. The Button is nothing but a mask.  

The under lying target.html page is where the real button is. The button that 

actually has functionality and does something the attacker wants. Thats whats 

being clicked.

If you where to click the button on the attacker webpage without the under lying

 target webpage being under it aka embedded in the iframe of the attacker.html 
 
 page it would literally do nothing. 

You can view this in the html code using your dev tools

The Overlying webpage aka the "iframe container" serves as a mask  and 

refferences the underlying webpage with the tags below essentially rendering it
