I made a call to validateDocument with the second cmd argument as a parameter. Here the user should pass in the .xsd file

I added new catch blocks to calidateDocument: SAXParseException and SAXException, which output relevant error messages. I also modified
the error message on Exception

I modified printNodes so that it outputs the information on each of the menu items. I made this very simple because I noticed that I
didn't have to use a NodeList