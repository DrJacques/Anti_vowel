# Anti_vowel
#Define a function called anti_vowel that takes one string, text, as input and returns the text with all of the vowels removed.  For #example: anti_vowel("Hey You!") should return "Hy Y!".  Don't count Y as a vowel. Make sure to remove lowercase and uppercase vowels.


def anti_vowel(text):
   vowels=["a","e","i","o","u","A","E","I","O","U"]
   text=list(text)
   index = 0
   anti_vowel=""
   for v in vowels:
       while index<len(text):
           if text[index] in vowels:
               del text[index]
               print (index)
               index=index
           else:
                print (text[index])
                index+=1
        
       anti_vowel=anti_vowel.
