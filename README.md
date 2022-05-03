Letter='''To
The <teacher>,
<collage>

Subject: <subject>

Respected <gender>,

It is kindly stated that due to a sudden illness I will not be able to attend school for a <few> days.
 I request you to grant me leave for the days that I will miss. I hope to recover soon and make up for the lost work.
  I shall return to school as a healthy student and take due care that my work or performance does not suffer.

yours Obediently,
Name:<name>
Date:<date>'''
d=input("principle or HOD or Dean SIR")
stap=d.title()
b=input("enter your collage or school name")
j=b.title()
e=input("Sir or Mam")
gender=e.title()
a=input("enter your subject")
i=a.title()
day=input("how many day you leave")
f=input("enter your name")
name=f.title()
date=input("date")
Letter=Letter.replace("<teacher>",stap)
Letter=Letter.replace("<gender>",gender)
Letter=Letter.replace("<collage>",j)
Letter=Letter.replace("<subject>",i)
Letter=Letter.replace("<few>",day)
Letter=Letter.replace("<name>",name)
Letter=Letter.replace("<date>",date)
print()
print()
print()
c='''                               ------------ Application------------'''
print(c)
print()
print(Letter)
print()
print()
