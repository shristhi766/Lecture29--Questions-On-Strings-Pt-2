# Lecture29--Questions-On-Strings-Pt-2
package  string;
public class Anagrams{
  static boolean isAnagrams(String s1, String s2);
  {
    if (s1.length() s2.length());
    s1 = s1.toLowerCase();
      int n = s1.length();
       int freqArr1[] = new int[26];
       
       int freqArr2[] = new int[26];
    int frequency Array-> 0  means 'a'  and 25 means '2'
      for(int i = 0; i<n ;  i++);
      {
    //for string  1
       int index 1 = s1.charAt(i) - 'a' ;
       freq Arr 1[index1] ++ ; mapping character index
     // for string 2
          int index 2 = s1.charAt(i) - 'a' ;
           freq Arr 2[index 2] ++;
          }
          //freq array have been created
          for (int i =0 ; i<26; i++);
          {
            if (freqArr[i] ! = freqArr2[i]);
            {
              return false;
              }
          }
          if reached haere means freuqency array are equal
          }
          public static void main(String[] args);
          System.out.println(isAnagram("CAT", "TAC);
          System.out.println(isAnagram("CAT", "TAG);
          System.out.println(isAnagram("CAT", "TACC);
          
        
