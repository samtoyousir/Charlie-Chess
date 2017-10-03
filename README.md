# Charlie-Chess
Dear Friends,

Thanks for expressing interest in helping build a Chess Engine. Sorry for the delay on this, homecoming was a bit crazy, but that’s all done now!

After hearing from most of you, and talking to Dr. Panaggio, it seems like the best plan is to start with MATLAB/Octave (something we know a bit of), and as we grow in our C++ or need more computing power, switch over to C++. 

To reiterate: My primary goal is to learn computing skills, not to build some sort of winning computer.
However, I’m really motivated by the idea of creating a chess computer, so I think mixing the two will really help!

It’s kind of a big project, but we don’t have deadlines really and you can do as much or as little as you like.

Dr. Panaggio has already been very helpful and connected us to some resources. Here are some questions he sent me.

By the way, as a starting point you might want to want to think about the following issues:

1.  How do we represent a board?  It would be nice to store the state of a game in a compact way.  The most intuitive way would be to use a matrix (or cell array if you want characters instead of numbers). However, I understand that there is a standard format called PGN for tracking chess matches. That would be harder to work with, so perhaps it would be helpful to write a function to convert between a matrix representation and a PGN format.  

2. Do we want to visualize the board? It is possible to create a graphical user interface (so you can just click to make moves) instead of a text based version of the game.  You will need to decide whether you want to do that. (For what it's worth, I would suggest worrying about that later.)

3.  What are the small manageable tasks you will need to be able to do?  Once you do so, you should compile a list of the functions, the names, and the types of inputs and outputs and then divide them up among your teammates and try to build and test them one by one.  

Example:  
Name: LegalMoves
Inputs: current state of the board as a cell array, piece location/ type (the one you want to move) as an index to a location on the board
Outputs: list of legal moves for that piece as an n by 2 matrix containing the indices of the locations where that piece is allowed to move

4.  Since this is a collaborative effort, it would be a good idea to have a way to share files.  Within the programming community, a development platform known as GitHub is standard.  I would recommend that you and your team members sign up for free accounts and use that as a way of keeping all of the files you create in one place and controlling for different versions of the project.  To get started, you might want to work through a tutorial like this: https://guides.github.com/activities/hello-world/
-Dr. Panaggio

Here is the link of our GitHub. Try to make an account on there. I’ll be adding things throughout the week, and if we need to schedule an in person meeting we can. I like to think we can get a meeting in a few times a month to chat and help us move forward faster.
I don’t know all that it can do, but I’m excited to learn.

Here is a quick video introducing what a chess computer does: https://www.youtube.com/watch?v=kdJnrrZeng0 

Please let me know if you know of anyone else who might be interested.

Y’all are a blessing.

Thanks,
Sam



