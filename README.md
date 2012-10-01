




LearnToCount
============

Learn children to count and (their fathers) to program.  DART.


IDEA_1   LEARN CHILDREN TO COUNT

Put in usual Blog simple counting examples,  2+7   4+5  and ask children to 
write sum of counting expression.  Valuate, if sum is right.  
Later there would be other countings; dividing, minuses and division.  All VERY simple. 
Later this could be complicated...


But because i want to promote DART here, so we put there next phase:  

IDEA_2   ..  and learn their parents to program.

Under the examples we put the actual program code, wich does these GET - SET / ASK numbers
(numbers must be between 0-9, and not amount more than ten.. 
And also code that does the actual calculations.  
      This is to let children ( and their parents)  to see, how this is done.  
      

This code should be elegant, because it is for to
-  Promote DART
-  In educational BLOG things should be done VERY elegantly.  No mistakes, no lousy code...
This is why I myself can not do this code now.  


PROBLEM:  Is this code to be dane using JavaScript?  Maybe...
BUT There might be only translation to DART visible here



So here this idea is...

I should put more code sometimes...

:(


  int Summa   = 0;  
  int Luku1   = 0;
  int Luku2   = 0;



main(){
  print('Simple DART-program to Learn Children to Count and their fathers to program');
  print('');
  print('Learn to count, for to be Counted On!');
  print('Learn to program, for not to be programmed!'); 
  print('');
  getnumberstocount();
  docount();
  print('You are counted on, You are not to be programmed');
}

void getnumberstocount(){
  Luku1 = 3;
  Luku2 = 4;
}

void docount() {
  Summa = Luku1 + Luku2;
  print(Summa); 
}
