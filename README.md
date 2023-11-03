# Personal-Site
Personal site built  with Html and CSS

Points:

->Meta: It is an HTML tag that contains metadata about a webpage. They are used by search engine to determine the page content and how to treat a webpage.
->Charset: It is an attribute that tells your browser what character encoding to use for this webpage to show the content as desired.
->UTF-8: It is the version of the character set.

->Utf-8 is the default character set for Html5. Most websites these days have to display characters which are not traditional ASCII characters. When received such characters in HTML source, Browsers should be able to handle those to display properly.

->The UTF-8 character set covers all characters and symbols that exists in this universe. So, it only makes sense to use it to make your site be perceived as it is desired. You want to use an emoji or character, make your site look modern and graphical, UTF-8 to the rescue.

->What if I don’t use `<meta charset=”utf-8”/>’?
Well, then you will to look up HTML entities (&#xxx;) to use that emoji or symbol and display properly.

But, as I said, it’s highly unlikely that you’re not already using it as <!DOCTYPE html>, by default, specifies UTF-8 as character for encoding.

->Well, now you might ask that why is it written specifically, even after writing ‘<DOCTYPE html>’?
Many old browsers are still there which do not support HTML5, even tho, it is a norm. So, for them including this tag is important.