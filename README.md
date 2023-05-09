# code_clause-Plagiarism-Checker-in-Python
from difflib import SequenceMatcher

string1 = 'My name is Akshitha'
string2 = 'I am studying BCA'

match = SequenceMatcher(None,
                        string1, string2)

result = match.ratio() * 100

print(int(result), "%")
