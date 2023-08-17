
````python
# Online Python - IDE, Editor, Compiler, Interpreter
import re

# text = """![[https://some-link.com]] some random text. 
#More random text ![[https://some-other-link.org]]"""
text = input("Enter wikilink")
size = input("Enter size")

p = re.compile(r'!\[\[(.+?)\]\]')

new_text = re.sub(p, fr'\n![{size}](\1)', text)

print(new_text)
````
