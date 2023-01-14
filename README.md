List0 = []

List1 = []

List2 = []

ListRe = []




for Xi in range(0,int(input("Enter Count Number:"))):

    List0.append(int(input()))

for i in List0:

    if i not in ListRe:

     ListRe.append(i)

for num in ListRe:

    if  num >=0 and  num %2 != 0:

        List1.append(num)

    if num % 2 == 0 and num >=0:

        List2.append(num)
    

    
     

print("تمام اعداد وارد شده غیرقابل قبول:",List0)

print("تمامی اعداد:",ListRe)

print("اعداد فرد",List1)

print("اعداد زوج",List2)
