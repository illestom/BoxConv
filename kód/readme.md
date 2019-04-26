Az egyes tesztesetekhez tartozó kódok. Általában csak a változást dokumentáltam a base.txt-hez képest.

model leírás
alap model 10 epochal	base.txt	
alap model 20 epochal	base+20ep.txt	
cnn model 30 epochal	cnn+30.txt	
Learning rate változtatása			
fix learning rate	base.txt	
epochonként csökkenő lr	base+lr.txt	
Struktúra			
alap struktúra	base.txt	
alap+3réteg linear	+fc.txt	
3x3-as réteg Box előtt	cnn+.txt	
3x3-as réteg Box után	+cnn.txt	
3x3-as réteg Box előtt és után	+cnn+.txt	
2 réteg Box	2box.txt	
Filterek száma			
40 filter	base.txt	
80 filter	base3x80.txt	
20 filter	base3x20.txt	
