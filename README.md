# Eric-Owusu-0009
#Q.1 
original_string = "Programming"  
reversed_string = original_string[::-1]  
print(f"1. Reversed String: {reversed_string}")  

#Q.2 
full_name = input("Enter your full name: ")  
names = full_name.split()  
initials = '.'.join([name[0].upper() for name in names]) + '.'  
print(f"2. Initials: {initials}")  

#Q.3 
def is_palindrome(s):  
    return s == s[::-1]  

string_to_check = input("Enter a string: ")  
if is_palindrome(string_to_check):  
    print(f"3. '{string_to_check}' is a palindrome.")  
else:  
    print(f"3. '{string_to_check}' is not a palindrome.")  

#Q.4 
sentence = input("Enter a sentence: ")  
word_count = len(sentence.split())  
print(f"4. The number of words in the sentence is: {word_count}")  

#Q.5  
original_string = "This is a string and it is an example."  
modified_string = original_string.replace("is", "was")  
print(f"5. Modified String: {modified_string}")  

