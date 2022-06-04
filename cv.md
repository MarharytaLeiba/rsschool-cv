# [rsschool-cv](https://MarharytaLeiba.github.io/rsschool-cv)

# Marharyta Leiba

## Junior Frontend Developer

## Contact information:

- Phone: +38 097 9785080
- E-mail: marharyta.kravchenko.parfumer.ua@gmail.com
- Github: [MarharytaLeiba](https://github.com/MarharytaLeiba)
- LinkedIn: [Marharyta Leiba](https://www.linkedin.com/in/marharyta-leiba)

## Summary about myself:
I am looking for positions in Frontend Development. I am looking for a company where I can grow into a highly qualified specialist.

At the moment I am actively studying the course "JS / FE Stage # 0 2022Q2" at the RS School and developing in this direction.

I believe, that my ability to learn and gain new skills will lead me on this path to becoming a proficient Frontend Developer.

## Skills and Proficiency:

- HTML, CSS
- Git, GitHub
- VS Code, Figma

## Code example:

```
public class Solution {
  public static boolean validPhoneNumber(String phoneNumber) {
      char[] cStr = phoneNumber.toCharArray();
      if(cStr[0] != '(') return false;
      if(cStr[4] != ')') return false;
      if(cStr[5] != ' ') return false;
      if(cStr[9] != '-') return false;
            
      for(int i = 1; i < cStr.length; i++){
         if(i != 4 && i != 5 && i != 9){
            if(!Character.isDigit(cStr[i])) return false;
         }
      }
      return true;
  }
}
```
