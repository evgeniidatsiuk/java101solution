1. Що виведе на екран наступний фрагмент коду?
```java
class IntsTest {
    int i;
} 

class Main {
    public static void main(String args[]) { 
        IntsTest test = new IntsTest(); 
        System.out.println(test.i);
    } 
}
```
- [X] 0
- [ ] null
- [ ] Помилка компіляції
- [ ] Помилка виконання


2. Що з наведено нижче найкраще описує returnType та returnValue:
```java
returnType methodName()
{
    return returnValue;
}
```
- [ ] returnValue повинно бути того ж типу що і returnType.
- [X] returnValue повинно бути типу returnType або типом, що є нащадком returnType
- [ ] Значення returnValue може бути будь якого типу, Java приведе його до returnType
- [ ] Якщо returnType описано як void то тоді returnValue може бути чим завгодно.


3. Що описує стан об'єкту?
- [ ] Методи
- [X] Поля
- [ ] Опис класу


4. Клас повинен мати принаймні одне поле:
- [ ] Так
- [X] Ні


5. Що задає поведінку об'єкту?
- [X] Методи
- [ ] Поля
- [ ] Опис класу


6. Яким чином створюються екземпляри об’єкту?
- [ ] Використовується ключове слово create
- [ ] Використовується ключове слово make
- [X] Використовується ключове слово new
- [ ] Використовується ключове слово add


7. Які значення приймуть a та b після виконання main
```java
class Test
{
    int a, b;
    Test()
    {
        a = 10;
        b = 20;
        }
}

class Runner
{
    public static void main(String[] args)
    {
        Test obj1 = new Test();
        Test obj2 = obj1;
        
        obj1.a += 1;
        obj1.b += 1;

        obj2.a += 1;
        obj2.b += 1;
    }
}
```
- [ ] 11, 21
- [X] 12, 22
- [ ] 10, 20
- [ ] 2, 2


8. Що відбудеться якщо Ви будете повертати значення в конструкторі
```java
class MyClass
{
    int MyClass()
    {
        return -1;
    }
}
``` 
- [ ] Помилка компіляції
- [ ] Буде працювати як звичайний конструктор
- [ ] Программа завершиться та поверне -1 як код помилки
- [X] Це буде звичайний метод, а не конструктор


9. Чи дозволено використовувати this() та super в методах?
```java
void test()
{
    this();
    super();
}
``` 
- [ ] Так
- [X] Ні


10. Чи буде працювати наступний фрагмент класу
```java
public class A
{
    A a = new A();
}
```
- [ ] Так
- [ ] Ні
- [X] Буде помилка переповнення стеку під час виконання
- [ ] Буде помилка компіляції


11. Чи можливо використовувати локальні змінні без ініціалізації?
- [ ] Так
- [X] Ні
- [ ] Так, за умови що змінна final