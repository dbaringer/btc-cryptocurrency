# btc-cryptocurrency
btc-cryptocurrency

About Json Files
I found some issues on the json file:
1- There was an syntax error  on the structure data file, but it was fixed
2-Json elements with room between words. On my opinion it should be set with no room.
 
3- On my opinion, I found some weird data structure regarding Illustrator and Genres specification: 
Some books contain basic string strucuture,  however, others contain an string array structure. It was handled by an unusual object variable on the C# back-end code.

Ilustrator and Genred should have the same structure for the whole json file, that is, it should be everything as string or everything as array


==================================================================================================================================================================
How you run this app:

You must open this project with Visual Studio 2015 or latest
You must install Newtonsoft.Json -Version 12.0.1
	- Open your visual studio ide
	- Go to menu Tools -> NuGet Package Manager -> Package Manager Console
	- Execute this command: Install-Package Newtonsoft.Json -Version 12.0.1


Be sure the file books.json is placed in the path "~/App_Data/books.json" of this application 

Compile the project
If no error displayed, click run (play) on your Visual Studio IDE

Once everything is ok, your favorite brower navigator must be open and show you the page
