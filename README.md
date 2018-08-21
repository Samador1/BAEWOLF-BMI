# BAEWOLF-BMI

def weight():
	wt = int(input("Enter the weight of a BAEWOLF: "))
	return wt
def height():
    ht = int(input("Enter the height of a BAEWOLF: "))

def BMI():
    Weight = weight()
    Height = height()
    BMI = (Weight * 703) / (Height * Height)
    return Weight, Height, BMI

def display():
    Weight, Height, BMI1 = BMI()
    print("\nWeight of a BAEWOLF:", Weight)
    print("\nHeight of a BAEWOLF:", Height)
    print("\nBMI is:", round(BMI1,3))

def main():
    display()

main()
