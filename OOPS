# OOPS_PYTHON
class human:
  def __init__ (self,n,o):
     self.name = n
     self.occupation = o
  def do_work(self):
    if self.occupation=="tennis player":
      print(self.name,"plays tennis")
    elif self.occupation=="singer":
      print(self.name,"sings a song")
  def speaks(self):
    print(self.name,"says how are you")
tom=human("tom cruise","actor")
tom.do_work()
tom.speaks()
maria=human("maria sharapova","singer")
maria.do_work()
maria.speaks()


class book:
  def __init__ (self,t,au):
    self.title=t
    self.author=au
  def display(self):
    print(self.title,self.author)
b1=book("chanakya","chanakya neeti shastram")
b1.display()

class dog:
  def __init__(self,d,b):
    self.dogname=d
    self.breed=b
  def display(self):
    print(self.dogname,self.breed)
d1=dog("chinnu","blacky")
d2=dog("tommy","bladder")
d1.display()
d2.display()

class rectangle:
  def __init__(self,l,b):
    self.length=l
    self.width=b
  def area(self):
    return self.length*self.width
  def calculate(self):
    print(self.length,self.width)
r1=rectangle(233,456)
r1.calculate()
print(r1.area())

class bank:
  def __init__(self,an,bal):
    self.acc=an
    self.bal=bal
  def withdraw(self):
    amount=float(input("enter amount to withdraw"))
    if self.bal>=amount:
      self.bal-=amount
    elif self.bal<amount:
      print("Insuffiecient funds")
    else:
        print("invalid")
  def deposit(self):
    amount=float(input("enter amount to be deposited"))
    self.bal+=amount
choice=input()
b1=bank(110023586,25000)
if choice=="1":
    b1.withdraw()
else:
    b1.deposit()
    print(b1.bal)

class car:
  def __init__(self,brand,model):
    self.brand=brand
    self.model=model
  def start(self):
    print(f"{self.brand}{self.model} has started")
c1=car("ferrari","f1")
c1.start()
    
class student:
  def __init__(self,name,m1,m2,m3):
    self.name=name
    self.m1=m1
    self.m2=m2
    self.m3=m3
  def avg(self):
    return (self.m1+self.m2+self.m3)/3.0
  def display():
    print(self.name,self.avg)
s1=student("chetan",98,78,89)
s1.avg()



    
