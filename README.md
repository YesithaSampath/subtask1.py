# subtask1.py
number = input("Entre a number : ")
number = int(number)
i = 1
para = i*i
while para-number<=0:
    i+=1
    para=i*i
else:
    print('largest square number less than or equal to entered number is',(i-1)*(i-1))
