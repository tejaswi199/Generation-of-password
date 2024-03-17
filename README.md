import random
passlen=int(input("enter the length of password: "))
s="abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?"
p="".join(random.sample(s,passlen))
print(p)
