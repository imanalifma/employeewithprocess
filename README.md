#class HelloWorld {
    public static void main(String[] args) {
    Emp obj = new Emp ("John", 20);
   process(obj); 
}
static void process(Emp obj) {
            System.out.println(obj.name);
            System.out.println(obj.age);
        }
}
class Emp {
    
    String name;
    int age;
    
        public Emp (String n, int a) {
             name = n;
             age = a;
           
        
        }
        
    }
