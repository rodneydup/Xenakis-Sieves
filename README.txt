        _           _          _     _          _       _           _        
       / /\        /\ \       /\ \  /\ \    _ / /\     /\ \        / /\      
      / /  \       \ \ \     /  \ \ \ \ \  /_/ / /    /  \ \      / /  \     
     / / /\ \__    /\ \_\   / /\ \ \ \ \ \ \___\/    / /\ \ \    / / /\ \__  
    / / /\ \___\  / /\/_/  / / /\ \_\/ / /  \ \ \   / / /\ \_\  / / /\ \___\ 
    \ \ \ \/___/ / / /    / /_/_ \/_/\ \ \   \_\ \ / /_/_ \/_/  \ \ \ \/___/ 
     \ \ \      / / /    / /____/\    \ \ \  / / // /____/\      \ \ \       
 _    \ \ \    / / /    / /\____\/     \ \ \/ / // /\____\/  _    \ \ \      
/_/\__/ / /___/ / /__  / / /______      \ \ \/ // / /______ /_/\__/ / /      
\ \/___/ //\__\/_/___\/ / /_______\      \ \  // / /_______\\ \/___/ /       
 \_____\/ \/_________/\/__________/       \_\/ \/__________/ \_____\/        
                                                                             
----------------------------------------------------------------------------

From Chapter XII of Formalized Music

Written by Iannis Xenakis and Gérard Marino at CEMAMu (now CIX)

----------------------------------------------------------------------------

Edited By Curtis Roads and Rodney DuPlessis (2019)

----------------------------------------------------------------------------

This program was originally written in BASIC by Iannis Xenakis and later translated to C by Gérard Marino. Gérard Marino's code included some libraries that, at the time of writing (2019), are now obsolete. Curtis Roads adapted the code to work with std libraries and Rodney DuPlessis corrected some further errors to create this version that will compile on most modern operating systems with a C compiler.

There are two programs: PointsFromSieve, which generates points from a given sieve, and its complement, SieveFromPoints deduces a sieve from given points.

----------------------------------------------------------------------------

To compile:

Binaries are provided for Linux (Ubuntu) and MacOs 10.14. If these don't work, you can compile the source code in the src folder yourself.

Compile in a terminal using your preferred C compiler. For example:

gcc PointsFromSieve.c -o PointsFromSieve.ix

or

clang PointsFromSieve.c -o PointsFromSieve.ix

----------------------------------------------------------------------------

Usage:

Both programs use command line interfaces, so you'll need to run them from a terminal.

Usage is simple. Run the program in a terminal and follow the instructions that are subsequently given to you.

----------------------------------------------------------------------------


(Documentation written by Rodney DuPlessis 22-03-2019)
