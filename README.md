# Cyber Range Network Exercise Development (Broken Authentication)

This is a project I worked on with 3 other students as
my senior project for school. The task was to develop
an exercise for an entry level cyber security class.
We decided rather than have one large exercise, we
would develop several small exercises to give students
exposure to more potential exploits. To organize this
we decided to create a Jupyter Notebook that contained
all of the exercises. To access the Notebook, students
would have to access a website provided by their
professor which would allow them to access a virtual
machine where the exercises are stored.

As for my exercise, I was tasked with was developing a 
broken authentication exploit. The basic summary is
students would get a list of randomly generated
passwords. Among these passwords was a correct password
that they would have to use to login to a dummy page.
The dummy page would contain a token that the student
must grab and put in a url. If the token is correct,
The student would be given access to a phrase that
they can copy and paste, and put in a Jupyter Notebook
cell to complete the exercise.

I included the README that I gave professors in the
"E2_Broken_Authentiaction" directory which goes into
more depth of how it works and the different files
used. Since this is all very difficult to explain
in text, I also included the video I used to
demonstrate how everything works.
