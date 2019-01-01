def letter_changes(str):
    newStr=[]
    arr= list(str)
    for val in arr:
        if(val=="z"):
            newStr.append("a")
        elif((val<"z") and (val>="a")):
            newStr.append(chr(ord(val)+1))
        else:
            newStr.append(val)
    for i, val in enumerate(newStr):
        
        if(newStr[i]=="a"or newStr[i]=="e"or newStr[i]=="i" or newStr[i]=="o" or newStr[i]=="u"):
           newStr[i]=newStr[i].upper()
         
    s=""
    newStr=s.join(newStr)

    return newStr

letter_changes("fun times!")
