Teona Petrova 223142

Control Flow Graph
![Untitled Diagram drawio](https://github.com/teonapetrovaa/SI_2024_lab2_223142/assets/163328264/62fc4ffc-c68d-4e30-945a-c8d53b4d7911)

Цикломатската комплексност: 
Цикломатската комплексност на кодот е 10, ја добив преку формулата P+1, каде P е бројот на предикатни јазли. Во овој случај бројот на предикатни јазли е 9,па цикломатската комплексност изнесува 10.

Тест случаи според критериумот Every Branch:

Item("", "9876", 200, 0.0)], payment = 100
Item("Пенкало", null, 150, 10.0)], payment = 80
Item("Ранец", "0123", 400, 15.0)], payment = 300
Item("Шише", "9012", 100, 5.0)], payment = 350
Item("Книга", "5678", 300, 10.0), payment = 250

Тест случаи според Multiple Condition
T && T && T
item.getPrice() >= 300, item.getDiscount() > 0, item.getBarcode().charAt(0) == '0'
T && T && F
item.getPrice() >= 300, item.getDiscount() > 0, item.getBarcode().charAt(0) != '0'
T && F && T
item.getPrice() >= 300, item.getDiscount() <= 0, item.getBarcode().charAt(0) == '0'
T && F && F
item.getPrice() >= 300, item.getDiscount() <= 0, item.getBarcode().charAt(0) != '0'
F && T && T
item.getPrice() < 300, item.getDiscount() > 0, item.getBarcode().charAt(0) == '0'
F && T && F
item.getPrice() < 300, item.getDiscount() > 0, item.getBarcode().charAt(0) != '0'
F && F && T
item.getPrice() < 300, item.getDiscount() <= 0, item.getBarcode().charAt(0) == '0'
F && F && F
item.getPrice() < 300, item.getDiscount() <= 0, item.getBarcode().charAt(0) != '0'
