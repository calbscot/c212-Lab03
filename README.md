# c212-Lab03import java.math.BigDecimal;

public class Lab03 {
  public static void main(String[] args) {
  
  BigDecimal a, b, c, d, e;
  a = new BigDecimal(1); 
  b = new BigDecimal(2); 
  c = new BigDecimal(3); 
  d = new BigDecimal(4); 
  e = new BigDecimal(5);

  //System.out.println(a.add(b)); // Problem 1
  //System.out.println(b.multiply(c)); //Problem 2
  //System.out.println(a.subtract((b.subtract((c.subtract(d)))))); //Problem 3
  //System.out.println(a.subtract(b).subtract(c).subtract(d)); //Problem 4
  //System.out.println(b.multiply(c).add((d.multiply(e))));  //Problem 5
   
  

  /*Answers:
  *6: The length is 4
  *7: The expression evaluates to -1 because the character at (2) is m 
  *   which has a value of 13, and when subtracted from 'n' with a value of 14 the answer is
  *   -1
  *8: The letter a has a value of 1 in the alphabet, 1 + 3 = 4 and d is the fourth value
  * in the alphabet so the expression gives the character d
  *9: 13 % 7 = 6. 7 goes into 13 one time with a remainder of 6
  *10: 5 % 7 = 5. 7 goes into 5 0 times with a remainder of 5
  *11: 13 / 7 = 1. 7 can only go into 13 1 time
  *12: 5 / 7 = 0. 7 can not go into 5
  *13: The expression evaluates to true, the first half (false && false)
  *    evaluates to false and false || true will evaluate to true because it's an or
  *    expression and a true value exists
  *14: The expression is false, the expression in the parentheses will evaluate to true
  *    so it becomes false && true which will evaluate to false since the boolean values 
  *     aren't both true 
  *15: 2 / 3 * 3 = 0. 2 / 3 is 0 and 0 multiplied by anything is 0.
  *16: 3 * 2 / 3 = 2. 3 * 2 evaluates to 6 and 6 divided by 3 is 2.
  *17: b, the outcome will always reflect the value of b
  *18: True, the outcome will always be true since it's a value OR true
  *19: b = (n != 0); if n has a value of 0, then b will be false, else b will always be true.
  *20: b = n < 3 || n > 5; b will be true if n is less than 3, or b will be dependent on whether 
  *    or not n is greater than 5.
  *21: b = (n != 0); problem 21 is the same as problem 19 but written as a ternary operator
  *22: !b, the outcome will always be the opposite of whatever b is
  *23  n == 4, if n has a value of 4 then the expression will be true, if not then it will be false.
  *24: n > 5, n has to be bigger than 5 to be true, and less than 5 to be false
  *25: False. No matter what the value of n is the expression will never be true. n!=n.
  *26: n > 3, n has to be bigger than 3 to be true, and less than 5 to be false
  *27: True. ++n-n++ returns a value of 1, and the value of true can be converted to 1. 
  *28: y = 2. Since y is not less than 10, it doesn't pass the first condition check
  *    and since the second if statement is inside the first if statement,
  *    the code goes to the else statement where y = 2
  *29: y = 10. There are no brackets so if the first condition isn't passed, which
  *    it isn't because x is not less than 10, than none of the other conditions are valid
  *    so y stays as 10 
  *30: y = 10. Starting at 6, --y gives y a value of 5, and then + y-- adds the current 
  *    y value of 5 giving you a value of 10. After 10 is returned, y becomes 9,
  *    but 10 is the value of y that is returned to the user after the expression.
  *31: f(3) = 6. because 2 * 3 = 6.
  *32: f(f(3)) = 12. f(3) = 6 and f(6) = 12.
  *33: f(h(3)) = 38. h(3) = 3 * 6 + 1 = 19, f(19) = 2 * 19 which equals 38.
  *34: h(h(3)) = 115. h(3) = 19, h(19) = 3 * 2 * 19 + 1 which equals 115
  *35: g(g(g(3))) = 0. g(3) = 3 - 1 which equals 2, g(2) = 2 - 1 which equals 1, g(1) = 1-1
  *    which equals 0.
  *36: It is an infinite loop. i starts at 0 and with increments of 3, it will never reach 10.
  *37: It is an infinite loop because the updater is i = i++, and not i++ which would make 
  *    a non infinite loop.
  *38: Not an infinite loop. Starting from 10, i will decrement by 3 until it reaches 1,
       since going further would go below 0 and the loop stops there. 
  *39: It is an infinite loop with no output because the compiler views the semicolon as 
       a body of the loop statement, so the code inside the curly brackets will no longer
  *    be part of the while loop, because the empty code before the ; is the new body.
  *40-41: Distance between centers: Center = sqrt((X1 - x2)^2 + (y1 - y2)^2);
  *     If Center <= r1 + r2, then the circles are overlapping.
  *     Find the bottom right coordinate of the rectangles with the given
  *     coordinate and the dimensions, for our rectangle it would be (x1, y1) with the 
  *     values of (550, 280), the second rectangle that would be tested to check for overlap
  *     can be given the points (x2, y2) in the top left and (x3, y3) in the bottom right. 
  *     The top left of the first triangle is (x, y) from the problem
  *     The rectangles over lap under these conditions: 
  *     if((x < x3) && x1 > x2) && (y < y3) && (y1 > y2))
  */
 

  
 

   
  }
}
