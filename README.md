sno=int(input('enter sno:'))
sname=input('enter name:')
s1=int(input('s1 marks:'))
s2=int(input('s2 marks:'))
s3=int(input('s3 marks:'))
s4=int(input('s4 marks:'))
s5=int(input('s5 marks:'))
s6=int(input('s6 marks:'))
total=s1+s2+s3+s4+s5+s6
avg=total/6
if avg>=91:
    print('o-grade')
elif avg>=81:
    print('A-grade')
elif avg>=71:
    print('B-grade')
elif avg>=60:
    print('C-grade')
elif avg>=50:
    print('D-grade')
elif avg>=40:
    print('pass')
 else:
    print('fail')
output:
sno:8
name:abhi
s1 marks:98
s2 marks:97
s3 marks:85
s4 marks:98
s5 marks:97
s6 marks:95
o-grade
