# Pick-A-Credit-Card-Excel-Template
Template to pick a credit card
I am applying for a Credit Card, however, I don't know which one is better. I chose to input credit card information from banks, and let the Excel pick for me, based on my requirements.
In this file, I have used these functional formulas:
> IF(AND(D3>1%,E3="No",I3="Yes",J3>=12,K3>=150,L3<=1000,M3>=3,H3<=24),"Good","Not Accepted")
> INDEX($C$14:$C$18,SMALL(IF(ISNUMBER(MATCH($B$14:$B$18,$G$13,-1)),MATCH(ROW($B$14:$B$18),ROW($B$14:$B$18)),""),ROWS($A$1:A1)))
> MATCH($G$22,$B$23:$B$27,0)
> MATCH(ROW($B$39:$B$43),ROW($B$39:$B$43))

P/S: I hope you will find this template useful! Please leave me a comment if you have any question. 
