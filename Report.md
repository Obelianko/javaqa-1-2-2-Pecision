# Отчёт о тестировании Расчет бонуса 
 
## Краткое описание
 
26.05.2021-26.05.2021 было проведено тестирование корректности расчета бонуса для новых клиентов
 
На тестирование затрачено: 15 мин
 
В результате тестирования выявлены следующие дефекты:
 
* Неточный расчет бонуса 
 
https://github.com/Obelianko/javaqa-1-2-2-Pecision/issues/1#issue-902500731
 
 
## Описание процесса тестирования
 
В процессе тестирования использовались артефакты не использовались:
 
В качестве тестовых данных использовались данные из задания 2 по ссылке:
* https://github.com/netology-code/javaqa-homeworks/tree/master/programming
 
* public class Main {
 
  public static void main(String[] args) {
 
    double regularBonus = 0.3;
 
    double specialBonus = 0.6;
 
    double totalBonus = regularBonus + specialBonus;
 
    System.out.println(totalBonus);
 
  }
 
}
 
Ожидаемый результат : 0.9
 
Тестирование производилось в следующем окружении:
* OC X El Capitan 10.11.6 (15G22010)
* openjdk 11.0.10 2021-01-19
* IntellijIDEA 2021.1.1
 

