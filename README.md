# exp-2
--java my class
class Square{
int area(int side){
return side*side;
}
int perimetre(int side){
return 4*side;
}
public static void main(String[]args){
Square sq = new Square();
int side=5;
int result1=sq.area( side);
int result2=sq.perimetre( side);
System.out.println("side of square:"+side);
System.out.println("area of square:"+result1);
System.out.println("perimetre of square:"+result2);
}
}<img width="211" height="70" alt="square" src="https://github.com/user-attachments/assets/e1fa8418-da6d-4166-ace5-4236ba510850" />
<img width="211" height="70" alt="square" src="https://github.com/user-attachments/assets/e3d7e58c-06d3-40bc-aa31-8a8f477e8315" />
# exp 2.1
--java overload
class overloadexample{
int add(int a,int b)
{
return a+b;
}
double add(double a,double b){
return a+b;
}
int add(int a,int b,int c){
return a+b+c;
}
public static void main(String[]args){
overloadexample obj=new overloadexample();
int result1=obj.add( 10,20);
double result2=obj.add( 10.5, 20.5);
int result3=obj.add(5,10,15);
System.out.println("Result of adding two integers:"+result1);
System.out.println("Result of adding two double values:"+result2);
System.out.println("Result of adding three integers values:"+result3);
}
}
<img width="263" height="55" alt="overload" src="https://github.com/user-attachments/assets/dcbd980f-03f8-4896-aaa6-86857096f033" />

