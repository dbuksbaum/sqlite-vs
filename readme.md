# SQLite3 Visual Studio Project for Windows

While x86 builds of sqlite are available, x64 builds are harder to find. Ok,
they are impossible to find on a reliable basis. What's worse, is that I can
never find them with FTS turned on. So, I created my own project just to 
build it they way I like. 

There will be no attempt to make this clean, or useful for anyone else but
little ole' me, so if you want something special or different - fork it and
do it. If its really useful, push it back and i will include it. Why am I 
pain on this? Because I didn't want to be building sqlite.dll's to begin
with. I want someone else to do it and I get to be a user. So, this is
a classic minimalist approach for something I don't want to do. :)

Beyond that - enjoy!

## Compilation Notes
* Uses the SQLite3 [Amalgamation](http://sqlite.org/cvstrac/wiki?p=TheAmalgamation)
* Generates x86 & and x64 with both static and dynamic MSVC runtime's
* Has the following [compilation options](http://www.sqlite.org/compile.html) set:
	* SQLITE_API=__declspec(dllexport)
	* SQLITE_ENABLE_COLUMN_METADATA
	* SQLITE_ENABLE_FTS4
	* SQLITE_ENABLE_FTS3_PARENTHESIS

	

