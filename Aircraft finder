def find_string(string_list, search_string):
    found_indices = []
    for i, string in enumerate(string_list):
        if search_string.lower() in string.lower():
            found_indices.append(i)
    return found_indices

given_list = ["Tejas", "Mirage-2000", "MIG-29", "MIG-21", "MKI", "SUKHOI-30", "JAGUAR", "CHETAH", "CHETAK", "HAWAK"]
user_input = input("Enter a Aircraft to search: ")
found_indices = find_string(given_list, user_input)

if found_indices:
    print(f"The Aircraft '{user_input}' was found at index(es): {found_indices}")
else:
    print(f"The Aircraft '{user_input}' was not found in the list.")


