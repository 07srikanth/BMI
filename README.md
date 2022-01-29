# BMI
To Calculate BMI using body weight (kgs) and height(meters) 
# weight_in_kg = int(65)
# height_in_centimeters = float(1.80 * 1.80)


def bmi(weight, height):
    return f"your BMI is {weight / float(height * height)}"


def validate_user_input():
    data_weight = int(weight_given_by_user)
    data_height = float(height_given_by_user)
    if data_weight > 0 and data_height > 0:
        real_caculation = bmi(data_weight, data_height)
        print(real_caculation)
    else:
        print("please enter a number greater than 0 and  positive number for weight and height ")

    # while weight_given_by_user  and height_given_by_user != "end":


weight_given_by_user = input("give your weight in KG\n")
height_given_by_user = input("give your height in meters\n")
validate_user_input()
