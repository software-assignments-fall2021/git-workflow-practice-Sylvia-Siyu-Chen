# The Article
This article is written by _JOEL SPOLSKY_, 
who is currently a software engineer in New York City. （**Updated**:He is not just any software developer, but **the founder of the companies behind Stack Overflow and Trello** )
This article is about the encoding and decoding of **Unicode** and **Character Sets**; it covers almost everything regarding processing code and char 
and is put in a pretty understandable and hilarious way. 

Here is the [link](https://www.joelonsoftware.com/2003/10/08/the-absolute-minimum-every-software-developer-absolutely-positively-must-know-about-unicode-and-character-sets-no-excuses/).

# The Content
It firstly discussed from a historical perspective how human languages, rather ancient ones, were transformed into some digital representations (for example, how to interpret **Content-Type: text/plain; charset="UTF-8"**). It then focused on the mapping and encoding algorithm of Unicode (and the brilliant concept of UTF-8 lol), which is quite handy in terms of dealing with text-related develp. 
![image](https://user-images.githubusercontent.com/79240358/135329633-fa78a18e-03bd-49ab-bfd2-6e474bd946a1.png)

Have fun reading :)

Comment by Daniel James Cucuzza:

I just wanted to share a funny story with my experience reading this article. Coincidentally, my boss for my internship last semester sent this to me thinking it would be a funny article to inform the importance of using the right character set. Basically, the software they were developing used regular ASCII strings as it was built with C/C++. Something that seemed so convenient was secretly going to screw them over. This came to light when a company outside of the United States bought the source code for the software in question. That meant that they had to painstakingly find all ASCII strings and wrap them around a QT macro called tr(...) to convert all c-strings into QStrings. Imagine having to do this to a codebase that is over twenty years old! 


