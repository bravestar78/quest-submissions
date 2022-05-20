1. In a script, initialize an array (that has length == 3) of your favourite people, represented as Strings, and log it.
![image](https://user-images.githubusercontent.com/104528601/168520784-dbf2d994-9338-4166-aadf-56fc86106d2c.png)

2. In a script, initialize a dictionary that maps the Strings Facebook, Instagram, Twitter, YouTube, Reddit, and LinkedIn to a UInt64 that represents the order in which you use them from most to least. For example, YouTube --> 1, Reddit --> 2, etc. If you've never used one before, map it to 0!
![image](https://user-images.githubusercontent.com/104528601/169446884-e077c414-2f5d-4100-bc4d-16641bf2878c.png)

3. Explain what the force unwrap operator ! does, with an example different from the one I showed you (you can just change the type).
It gets rid of the optional type.  If the value is nil, the program will panic, otherwise it will work just fine.
![image](https://user-images.githubusercontent.com/104528601/169451528-8255657e-c064-41ad-b89c-336078181d1b.png)

4. Using this picture below, explain...
What the error message means - the funtion returned a different type than it was expecting ||
Why we're getting this error - dictionaries return optional values, the function expected to return String type, not String? type. ||
How to fix it - it can be fixed by either adding an optional operator  - ``pub fun main(): String?{`` or a force unwrap operator - ``return thing[0x03]!``
![image](https://user-images.githubusercontent.com/104528601/169451920-a83c6b35-c0e4-406a-b64e-0bef4f8a8489.png)
