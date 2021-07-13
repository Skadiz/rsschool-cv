# Vsevolod Kurochka
* Contacts:
  * Phone: +380986971819
  * E-mail: kurochkaseva@gmail.com
* Student of IT university in Poland (PJATK) at specialization IT(gameDev), looking for a start of my IT career (prefer the developer one). 
  * My personal traits: _honest, organized, punctual, flexible, problem solver, team player_  
* **Skills:**
  * Java
  * C++
  * C#
  * HTML+CSS+JS
  * NodeJS(Express framework)
  * React
  * Ms SQL, MySQL, Oracle
  * Unity 2D
  * .NET
  * UML
* Code from https://www.codewars.com/kata/56f173a35b91399a05000cb7/solutions/java

   ```java
   import java.util.*;
    public class Kata {
      public static int findLongest(String str){
        int n = str.length();
        int res = 0, curr_len = 0;
        for (int i = 0; i < n; i++)
          {
              if (str.charAt(i) != ' ')
                  curr_len++;
              else
              {
                  res = Math.max(res, curr_len);
                  curr_len = 0;
              }
          }
        return Math.max(res, curr_len);
      }
    }
    ```
