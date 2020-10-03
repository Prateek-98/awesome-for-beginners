import re
n = int(input())
for i in range(0,n):
  try:
    re.compile(input())
    is_valid = print("True",end='\n')
  except re.error:
    is_valid = print("False")
