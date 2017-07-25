Program Name: JavaTestFive

Programmer/Author:  Nancy Schorr



Date: July 22, 2017 

This program parses JSONinput from either a file or a url. It showcases the use of REST apis to a read data and store it as a JSON object, JSON array and other Java objects for further manipulation.

It uses the example website: http://jsonplaceholder.typicode.com/albums and reads the data.

It will also read a local JSON file.  For the program to complete successfully you need to either create a JSON file named 'C:\jasondata2.json' or use any name and change the name inside the program. To easily create a JSON file you can download the data contained in the file url above and save it.

The secret to easily reading a URL and storing it's contents is really just a few lines.  You want to use a BufferedReader to experience efficient reading of characters, arrays, and lines.

Once you have an entire JSON string (starting with "[") you can turn it into a Collection, JSONArray, ArrayList or Map as shown in the program.