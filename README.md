#This program helps you determine an investment after ten years.
def main():
    print("This program helps you determine an investment after ten years")

    principal=eval(input("Enter principal value :"))

    apr=eval(input("Enter annual interest rate :"))

    for i in range(10):
         principal=principal*(1+apr)

    print("The value in 10 years is", principal)
main()
