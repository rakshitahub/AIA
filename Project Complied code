import webbrowser

def find_string(string_list, search_string):
    found_indices = []
    for i, string in enumerate(string_list):
        if search_string.lower() in string.lower():
            found_indices.append(i)
    return found_indices

def choose_option():
    while True:
        choice = input("Enter your choice (1 or 2): ")
        
        if choice == "1":
            print("You chose Standard Landing.")
            break
        elif choice == "2":
            print("You chose Emergency Landing.")
            break
        else:
            print("Invalid choice. Please enter 1 or 2.")

def pick_option():
    print("Please pick an option between 1 and 35:")
    
    while True:
        try:
            choice = int(input("Enter your choice: "))
            
            if 1 <= choice <= 35:
                print("You picked option", choice)
                break
            else:
                print("Invalid choice. Please enter a number between 1 and 35.")
        
        except ValueError:
            print("Invalid input. Please enter a valid number.")

def redirect_to_site(url):
    webbrowser.open(url)

given_list = ["Tejas", "Mirage-2000", "MIG-29", "MIG-21", "MKI", "SUKHOI-30", "JAGUAR", "CHETAH", "CHETAK", "HAWAK"]
user_input = input("Enter an Aircraft to search: ")
found_indices = find_string(given_list, user_input)

if found_indices:
    print(f"The Aircraft '{user_input}' was found at index(es): {found_indices}")
else:
    print(f"The Aircraft '{user_input}' was not found in the list.")

print("Please choose one of the following operations:")
print("1. Standard Landing")
print("2. Emergency Landing")

choose_option()

states = [
    'Andhra Pradesh', 'Arunachal Pradesh', 'Assam', 'Bihar', 'Chhattisgarh',
    'Goa', 'Gujarat', 'Haryana', 'Himachal Pradesh', 'Jharkhand', 'Karnataka',
    'Kerala', 'Madhya Pradesh', 'Maharashtra', 'Manipur', 'Meghalaya', 'Mizoram',
    'Nagaland', 'Odisha', 'Punjab', 'Rajasthan', 'Sikkim', 'Tamil Nadu', 'Telangana',
    'Tripura', 'Uttar Pradesh', 'Uttarakhand', 'West Bengal', 'Andaman and Nicobar Islands',
    'Chandigarh', 'Dadra and Nagar Haveli and Daman and Diu', 'Delhi', 'Ladakh', 'Lakshadweep', 'Puducherry'
]

total_states = len(states)
print("Total states in India:", total_states)
print("List of states:")
for state in states:
    print(state)

pick_option()

# Redirect to a specific website
redirect_to_site("https://www.flightradar24.com/26.88,80.91/6")
