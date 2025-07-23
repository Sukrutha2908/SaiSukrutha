# Input data
string = "EXF Education - Masters in Data Science"
name = "Sukrutha"

# 1. Output the length
print("length :", len(string))

# 2. Reverse the string
print(string[::])

# 3. Personalized sentence
print(f'My name is "{name}", I am a student in {string}')

# 4. Replace EXF with SVU
modified_string = string.replace("EXF", "SVU")
print(modified_string)

# 5. Split the string into a list of words
word_list = string.split()
print(word_list)
