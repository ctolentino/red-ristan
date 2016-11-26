```python


def isPalindrome(arsonsWord):
 leftPos = 0
 rightPos = len(arsonsWord)-1
 
 while rightPost >= leftPos:
  if not arsonsWord[leftPos] == arsonsWord[rightPos]:
   return False
  leftPos+=1
  rightPos-=1
 return True




```
