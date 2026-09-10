# Bold text

print("\033[32m" + "\033[1m" + "Welcome to Cloud City!" + "\033[0m")
print("Cloud City, Sustainable City, and the Future of Urban Living")

# now want to ask the user for the name and age, then store them in the dictionary
personal_info = {}

def get_user_info():
    name = input("Enter your name: ")
    age = int(input("Enter your age, precisely: "))
    personal_info['name'] = name
    personal_info['age'] = age

get_user_info()

print("Your personal info has been successfully stored in the dictionary.")

# Now want to create random dictionaries if the user details don't match
# with the dictionary they created earlier

kalenjin_list = [
    "Kibet",
    "Kipchoge",
    "Kipchumba",
    "Kipchirchir",
    "Kipkemoi",
    "Kipkemboi",
    "Kipkorir",
    "Kipkoech",
    "Kiplagat",
    "Kiplangat",
    "Kipngeno",
    "Kipng’etich",
    "Kipng’etuny",
    "Kipngetich",
    "Kiprono",
    "Kiprotich",
    "Kipruto",
    "Kiprung’ang",
    "Kiprugut",
    "Kipkosgei",
    "Kipsang",
    "Kipsigis",
    "Kiptala",
    "Kiptanui",
    "Kiptum",
    "Kiptoo",
    "Kiptui",
    "Kipkirui",
    "Kipketer",
    "Kipng’or",
    "Kipng’eno",
    "Kipng’etuny",
    "Kiptabus",
    "Kiptebes",
    "Kipleting",
    "Kiprono",
    "Kipsang",
    "Kiprotich",
    "Kipruto",
    "Kiptoo",
    "Kiptum",
    "Kiplimo",
    "Kiplangat",
    "Kiplagat",
    "Kipkoech",
    "Kipkorir",
    "Kipkemoi",
    "Kipkemboi",
    "Kipchirchir",
    "Kipchumba",
    "Kipchoge",
    "Kibet",
    "Kipngetich",
    "Kipng’eno",
    "Kipng’or",
    "Kipng’etuny",
    "Kiprono",
    "Kiprugut",
    "Kiprung’ang",
    "Kiptala",
    "Kiptanui",
    "Kiptui",
    "Kipketer",
    "Kipkirui",
    "Kipleting",
    "Kiptabus",
    "Kiptebes",
    "Cheruiyot",
    "Chepkoech",
    "Chebet",
    "Jepchirchir",
    "Jepkosgei",
    "Jepkemoi",
    "Jepkorir",
    "Jepketer",
    "Jepng’etich",
    "Jepchumba",
    "Jelimo",
    "Chepng’etich",
    "Chepkirui",
    "Chepkemoi",
    "Chepkoech",
    "Chepkwony",
    "Cheptoo",
    "Chepterit",
    "Chepchirchir",
    "Chepkorir",
    "Chepkwony"
]

gikuyu_list = [
    "Wanjiku",
    "Wambui",
    "Wairimu",
    "Wangari",
    "Wanjiru",
    "Waceke",
    "Wangui",
    "Wambura",
    "Wanjiru",
    "Wairimu",
    "Wangari",
    "Wambui",
    "Wanjiku",
    "Waceke",
    "Wairimu",
    "Wangari"
]

luo_list = [
    "Achieng",
    "Akinyi",
    "Atieno",
    "Adhiambo",
    "Auma",
    "Anyango",
    "Awino",
    "Achieng'",
    "Akinyi'",
    "Atieno'",
    "Adhiambo'",
    "Auma'",
    "Anyango'",
    "Awino'"
]

# Check if the user's details match the dictionary
name = personal_info['name']
age = personal_info['age']

if (name, age) not in personal_info.items():
    import random

    random_names = [
        "Alice",
        "Bob",
        "Kipngetich",
        "Langat",
        "John",
        "Kiprono",
        "Kipkoech",
        "Kiptoo",
        "Kipkemoi",
        "Kipchirchir",
        "Kiptoyot",
        "Kipkorir",
        "Kiplangat",
        "Kipkemboi",
        "Kiprotich",
        "Kipngeno",
        "Kiptolelyon"
    ]

    random_ages = [random.randint(18, 87) for _ in range(100000)]

# Ask the user for the age and name again to see if they match
print()
name = input("Enter your name again: ")
age = int(input("Enter your age again: "))

if (name, age) != (
    personal_info['name'],
    personal_info['age']
):
    print("Your name and age do not match with the stored information.")
    print("Here are some randomly generated names and ages for you:")

    random_name = random.choice(random_names)
    random_age = random.choice(random_ages)

    print(f"Random Name: {random_name}, Random Age: {random_age}")

    choice = input(
        "Would you like to use this random name and age? (yes/no): "
    )

    if choice.lower() == 'yes':
        personal_info['name'] = random_name
        personal_info['age'] = random_age

        print("Your information has been updated with the random name and age.")
    elif choice.lower() == 'no':
        print("Your information remains unchanged. ")
        breakpoint = input(
            "press enter to conntinue and and enter name again:"
        )
        breakpoint = input("Press enter and enter your age again:")
    else:
        get_user_info()
