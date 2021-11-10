# NLP-RE

Regular expressions or RegEx is a sequence of characters mainly used to find or replace patterns embedded in the text. 

A regular expression (shortened as regex or regexp; also referred to as rational expression) is a sequence of characters that specifies a search pattern. Usually such patterns are used by string-searching algorithms for "find" or "find and replace" operations on strings, or for input validation. It is a technique developed in theoretical computer science and formal language theory.

 We use re.findall() to extract all the strings from the document which follows the following format:

any character a-z, any digit 0-9 and symbol '_' followed by a '@' symbol and after this symbol we can again have any character, any digit and especially a dot.

 # removing links
newString = re.sub(r'(https|http)?:\/\/(\w|\.|\/|\?|\=|\&|\%)*\b', '', newString)
