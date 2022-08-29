# dart-inheritance-class-and-object
dart-inheritance class and object

void main() {

 

var obj=C();
  obj.a=8;
  obj.b=8;
  obj.c=5;
  obj.d=5;
  obj.e=5;
  obj.f=7;
  print(obj.a);
   print(obj.b);
   print(obj.c);
   print(obj.d);
   print(obj.e);
   print(obj.f);
}



class A {
  late int a;
  late int b;
  A() {
    print("A class");
  }

 
}

class B extends A {
  late int c;
  late int d;
  B() {
        print("B class");
  }


  
}
class C extends B {
  late int e;
  late int f;
  C() {
        print("C class");
  }

  
}















