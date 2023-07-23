# cache-object-script-notebook

## $ObjectScript

#### Commands

##### zn <>	 - לעבור בין מחיצות
##### w = write 		- Like console.writeline
##### ,!			- Enter after line
##### s = set 		- Define variable
##### n = new		- To define local variable
##### r = read		- To implement variable from client => r “Type number”, num
##### d = do		- To execute routine=> d<routineName>^<userName>()<routineName>
##### w "Example"
##### q
##### To execute func=> w $$<funcName>^<userName>()<funcName>(x)
##### n res
##### s res = x
##### q res
##### // ; */ /* 		- Are all for notes.
##### w			- Show all variables. 
##### click + f1		- Show documentation about the func.
##### j = jop		- שגר ושכח מהפונק
##### k = kill 		- To kill variable/s
##### “” = NULL
##### zw <value>	- Print all values of the VALUE 
##### zk <value>	- Kill specific value.
##### $h 		- Get time => days, seconds
##### $zd($h,4)		- Get date.
##### $zt(date,2)		- Get time. 
##### ** / *		- כפל/ חזקה
##### "#"			-חלוקה עם שארית
##### /			-חלוקה כולל העשרוני
##### \			-לא כולל העשרוני
##### ‘=			-שונה מ
##### ()||()  ()!()		- או
##### ()&&()  (),()	- גם
##### _”string”		- To add string to string
##### Errors
##### NO ROUTINE  	 -התכנית לא קיימת
##### NO LINE		-הפונק לא קיימת	  	
##### COMMEND	-פונק לא מחזירה ערך
##### PARAMETER	-יותר פרמטרים ממה שצריך
##### i  = if {}		
##### elseif {}
##### else {}
##### i x=5 continue 	-מדלג על פקודה
##### $c(num)		- Return the character of the num
##### $A(“string”)	- Return the num of the character 
### loops
##### f = for
##### f i=1:1:10{}		- index : growth : stop condition 
##### f i=1,99,””string”, 74
##### f i=1:1{ i=10 q}	- Stop condition inside the loop
##### while(){}
##### do{} while()
##### “string”[“string” 	- Do they contain? (also for numbers)
##### $l = $length 	- How much strings before “X”, between “X” and after “X”
##### *its K sensitive 
##### $l(“theString”,”X”)
##### $e = $extract	- Give me string by index
##### $e(“string”, index) 
##### $e(“string”, $l(“string”) OR  *
##### S $e(str, index)=str
##### S $e(str, index, index)=str
##### $f = find		- Return the next index first string (return the first it find)
##### $f(str,x) 
##### $f(str,x,y) - from y to start looking
##### $p = $piece	- Get the word before the string, the index is when - the first? seconde?
##### $p(str,str,index)
##### s $p(str,”*”,index)
##### $j = $justify 	-לעגל אחר האינדקס
##### $j(num,””,index)
##### $tr = $translate	-   החלפת תו (הפרמטר השני) בתו אחר (הפרמטר השליש)
##### $tr(str,str,str)
##### $replace(str,str,str) - אותו הדבר רק יותר טוב (מחליף שני תווים סמוכים באותו הדבר)
##### NO SHORTCUT
##### $r = $reverse 	- Reverse to string/num
##### $re(str)		
##### $i = $increment 	- Increase var by num (default value of var is 0)
##### $i(var, num)
##### x str 		- Execute the string
##### $zconvert(str,”U”) - הופך לאותיות גדולות
##### $select(condition: value,condition: value,condition: value…, 1:””) 
