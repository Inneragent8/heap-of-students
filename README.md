 Student
 -----------------
 firstName: string
 
 lastName: string
 
 address: Address
 
 dateOfBirth: Date
 
 gradDate: Date 
 
 creditHours: int

 contains
 
 Address
 --------------
 street: string 
 
 city: string
 
 state: string

 zip: string

 contains
 
 Date
 --------------
 day: int
 
 month: int
 
 year: int

----------------------

 algarithem
 
 Address class:
 
Address(): It initializes an Address object with default values.

Address(street, city, state, zip): This constructor initializes an Address object with the given values for street, city, state, and zip code.

print() const: This member function outputs the address information (street, city, state, and zip) to the console.

Date class:
   
Date(): This is a default constructor. It initializes a Date object with default values.

Date(): This constructor initializes a Date object by parsing a string ("01/01/2000") into month, day, and year.

print() const: This function outputs the date in a readable format to the console.

Student class:
   
Student(): This is the default constructor. It initializes a Student object with default values for name, address, birth date, graduation date, and credit hours.

Student(firstName, lastName, address, birthDate, gradDate, creditHours): This constructor initializes a Student object with the provided values for name, address, birth date, graduation date, and credit hours.

print() const: This member function prints out the student's details, such as first name, last name, address, birth date, graduation date, and credit hours to the console.

main function:
   
main(): This is where the program starts. It creates instances of Address, Date, and Student with sample data and then calls the print() method of the Student class to display the student’s information.
