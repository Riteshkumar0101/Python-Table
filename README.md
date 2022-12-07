# Python-Table
class tables:
    # creating a method
    def gettables(self, i):
        self.i = i
        #loop for the table
        for j in range(2, self.i + 1):
            for k in range(1, 11):
                print(j, "x", k, "=", (j*k))
            print() 
while (True):
    n = int(input("Enter a positive number : "))
    if (n >= 2):
 
        # creating an instance
        obj = tables()
        # calling the method
        obj.gettables(n)
        break
    else:
        print("Enter a number greater than equal to 2: ")
        continue
