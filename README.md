# LT-Internship
**Goal of Project:**
To scrape data from html and only print the [id] and [title] for each image within a specific album.

**How to use:**
1. Unzip the file.
2. Open "LT-Internship-Project" directory.
3. Open "LT-Internship-Project.sln" using Visual Studio or any other Python friendly IDE.
4. Click "run".  (If in Visual Studio the run button will be a green play button on the top tool bar.)
![run button visual studio](https://user-images.githubusercontent.com/75749470/101669469-cee10400-3a06-11eb-824a-8a5121f6358d.jpg)

**While running the program:**
1. The program will ask for the user to input which album they would like to view.
2. After the user inputs the album number, the program will display everything within the album the user chose to view.

**Why this program isn't finished:**
1. Instead of printing everything within the album, the program should output only the [id] and [title].

**Solutions I have tried in order to fix the problem:**
1. **print(scraped)**

*#This works but outputs everything*

**2. print(scraped["id","title"])**

*#ERROR: string indices must be integers*

3.  **del readable["url"]**

    **del readable["thumbnailUrl"]**
    
    **del readable["albumId"]**
    
    **finished = str(readable)**
    
    **print(finished)**
    
*#ERROR: DEL NOT ABLE*

*#I turned scraped into an exec in order to try to remove everything that we didn't want to output then turn it back into a str.*

**Once the problem is resolved I would like to add:**
1. A prompt asking the user to either view another album or to end running the program.
