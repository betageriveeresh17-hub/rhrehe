import sys 
#Check if Jenkins passes a command-line argument
if len(sys.argv)>1;
  string = sys.argv[1]
else:
   string = input("enter a string:")
   if string.lower() ==string[::-1].lower():
   print(f"{string}' is a palindrome.")
else:
   print(f"{string}' is a palindrome.")
