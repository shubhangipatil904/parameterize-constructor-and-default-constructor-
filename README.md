# parameterize-constructor-and-default-constructor-
1 parameterize constructor -
using System;

namespace Constructor {

  class Car {   

    string brand;
    int price;

    Car(string theBrand, int thePrice) {

      brand = theBrand;
      price = thePrice;
    }
  
    static void Main(string[] args) {

      // call parameterized constructor
      Car car1 = new Car("Bugatti", 50000);

      Console.WriteLine("Brand: " + car1.brand);
      Console.WriteLine("Price: " + car1.price);
      Console.ReadLine();
     
    }
  }
}
2 default constructor 

using System;

namespace Constructor {

  class Program {  

    int a;

    static void Main(string[] args) {

      // call default constructor
      Program p1 = new Program();

      Console.WriteLine("Default value of a: " + p1.a);
      Console.ReadLine();
     
    }
  }
}
