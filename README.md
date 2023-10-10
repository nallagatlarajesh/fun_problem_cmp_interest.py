# fun_problem_cmp_interest.py
def compound(p,r,t,n):
    amt=p*(1+r/100)**n*t
    cint=amt-p
    print("compound interest is:",cint)
p=int(input("enter the principal"))
r=int(input("enetr the rate of interest"))
t=int(input("enetr the time period in years "))
n=int(input("enter the number of times the interest is  compounded"))
compound(p,r,t,n)
