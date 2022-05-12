# sri88
 def checkbalance(s):
    while(True):
        if '[]' in s:
            s=s.replace('[]','')
        elif '()' in s:
            s=s.replace('()','')
        elif '{}' in s:
            s=s.replace('{}','')
        else:
            return not s
s=input()
if checkbalance(s):
    print("Balance")
else:
    print("Not balance")
        
