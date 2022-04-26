What the project does ->> 
This program reads a folder full of MP3 music and makes a list of your MP3 files in a clean manner.  It then can alphabetize your entire list.  This gets interesting with songs like the one from TOOL called... (-)ions.  The only restriction is that the music has to be in this form "White Christmas - Bing Crosby.mp3" where the song comes first and the artist comes second with a dash in between.  The program goes down into all subfolders from the root of the path you give. Lastly it numbers the lines of music so you can quickly get a count of the songs in that directory.  This helps a bit with duplicates once you see all songs alphabetized.  Need to send a clean list of your songs to a friend?  This might be your program.

9199  Hello Again - Hoobastank.mp3

9200  Hello Again - Lost Prophets.mp3

9201  Hello Again - The Cars.mp3

9202  Hello Dolly - Louis Armstrong.mp3

Why is the project useful ->>
The program is useful because it can collect all your song names in a text file you could export and do almost anything with. For instance, I have a thumb-drive with 4000 songs in my car.  This helps print a clean list I can review when thinking about a song I might want to play aside from shuffle.  This project was just an experiment to write something simple but had to have a form or graphical user interface (GUI) using C++ only.  I mean most colleges teach for years but you stay using command line unless you go to another language.

How users can get started with the project ->>
There is no install and you can simply run the executable.  The documentation is present. I placed the source code here for playing around. Also, the distribution is here with just the executable and manual as if it were freeware.  Keep in mind I had to tell my Malwarebytes the programming folder was off limits so it didn't throw a fit about the executable.


Who maintains and contributes to the project? ->>
No regular updates to this are happening as it was just a weekend project. Feel free to add to this and add your own creativity but give me credit. I won't add more unless I get inspired.

Future additions might be to calculate percent of similar songs to weed out duplicates.  Maybe an HTML page with the list and when you click a radio box it sends that song name to a 'favorites' list?

Backstory and History ->>
I wrote this fun code to organize the names of all the MP3 music files I have.  The MP3 files were collected in a random trade with friends some years ago. Back in the olden days, if you went into your start-menu in Windows and type cmd you’d get a command window or DOS prompt as they used to say.  Then, if you made your way to your music folder by typing cd d: (assuming it’s on drive D) and then cd music*…which moved you into a folder called music.  Anyhow you get the point!  You have to end up in the directory where you keep your music.  You’d then type the following command:   dir/s > MusicData.txt   This command printed folder contents and with the text scrolling bye, redirected it into a file for you called “MusicData.txt”.  Typical command line.

In case you don’t have MP3s, there is a premade list created called MusicData.txt for testing.  The program comes with a foreshortened song list called MusicData.txt and a huge list called MusicDataHugeList.txt.  The huge list can be renamed MusicData.txt to push the program to its limits processing wise.  With these lists you would bypass the first GET MP3 LIST button and work with the other three buttons.

The idea is that I made a program that would do this similar command-line procedure but with a graphic user interface in Windows.  I coded this program to take a text file like the one created in command line and clean it up relatively fast.  The program attempts to take out text where no music is specified with *.mp3 extension on it.  It also takes out blank lines and a few other unneeded file lines.

Programming Code SETUP ->>
To start this program the hard way if you have the C++ code, you can extract into a folder. Next you could go into GMP3project\GMP3\Debug and just run the executable like any other Windows program, because it’s already built.  You can also use the *.sln to open the project in Visual Studios and run as well as alter the code.  

Operations ->> 
Basic Non-programming operations. Double-click on the executable called GetMP3.EXE.
The user is presented with four rectangle buttons and one long rectangle for path input. There is some text at the very bottom of the small window showing program status. To operate this program, you first type in or paste a PATH in the long white input area (such as C:\Users\MyPC\Desktop\music) where the music files are located.  

Start in the top left the GET MP3 LIST buttons will grab all file names in that directory along with a bunch of other unnecessary information such as file sizes and file-dates. Notice the status below the PATH input area to see when it’s done grabbing.  

Optionally you click the button below that only if you wish to see what was written using the VIEW MP3 LIST buttons.  This is to examine the list before it is altered. Next you click on the top right button to sort the text list alphabetically.  

Lastly use the VIEW ALPHA LIST button, so you can view the final product list. Notice that numbers have been added to keep track of how many MP3s there are on the list.  When complete with all four buttons one will have a MusicData.txt showing the initial list before sorting.  There will also be an Alphabetized.txt after sorting


