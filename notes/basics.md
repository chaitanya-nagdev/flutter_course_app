# Widget

- Flutter apps are built using **widgets inside widgets**.
- A widget can take:
  - **1 child** using the `child` property.
  - **Multiple children** using the `children` property.
  - **Custom or specific properties** that accept widgets (like `title`, `body`, `actions`).
  - **Builder functions** to dynamically generate child widgets.
- So to pass widget inside widget we use argument

- Difference between an argument & widget is , Widget start with capital letter while argument start with small letter so
  Ex For Text widget see argument like 'style' they will be small but to set argument we pass TextStyle which is widget

- Widget behaviors can be changed by using arguments Ex
  - Text Widget -> takes style argument -> style takes 'TextStyle' -> Now TextStyle takes colors argument to set colors
    so see this pattern we pass widget behavior as arguments & we pass widget to widgets

# Types

- Data Types

```dart

String name = "testing";
int num = 1;
double dnum = 1.34;
List mylist = ['testing',1,34]; // heterogeneous (dynamic) if type not enforced
List<int> intList = [1,4,5];
Map myMap = {'name': 'user-1','age':5,10:'ten'}; // heterogeneous if type not enforced
Map<String,String> strMap = {'name':'user-1','age':'5 years','10':'ten'};
String? firstName = 'TestingU1';// It can store null as well , so using ? operator we can make any type null, all types in dart are not nullable
Set s1 = {1,5,234,'test','dfdfi',true};
Set<String> s2 = {'only','string','allowed'};
dynamic nameAge = 'stores the name';
name-age = 4;

```
