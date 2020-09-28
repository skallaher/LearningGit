# Motivation

The stories you are about to read are true. The names have been changed to protect the innocent.

## Story: Meltdown

Once upon a time, at a far-off college, the editors of the school newspaper had been
working frantically for two weeks to put together a special super-size edition of
the paper. They had spent late nights writing columns, editing stories, laying out the copy and
pictures, placing ads, and choosing comics. On the night before printing day, they made the
last adjustments to the spacing of words, fixed the last typo, and shut down the
computer for the night.

The next morning, the computer wouldn't boot up due to a corrupted hard drive.

Panic ensued, since all of the work was on that computer, and the last backup was more than
a week old.

There is a happy ending to this story: one of the editors' friends was able to rebuild
enough of the hard drive's partition information to get the latest version of the
paper copied to a new drive, and they got the paper to the printers in time.

## Story: Collaboration

A long time ago, in a university not so far away, a eight students were
working together to write their final paper for a class. They had divided
the paper into sections, and each wrote their part, but then the one who
had volunteered to be the editor had to take all of their emailed parts
and combine them into a single document. This editor then started editing
the complete paper, correcting grammatical mistakes, fixing typos, making
the writing flow better, and organizing the assembled whole in a way that
made sense.

Then all of the other students, who were conscientious and wanted to do the
best job possible, started sending updated versions of their sections. The
editor had to figure out what changed between the original version and the
updated version, find where the part ended up in the document (and many parts
were split into different places in the document for the sake of consistency
and flow), figure out if the editorial changes were still needed for these
updated versions, and finally put the updated text, with whatever edits
were needed, into the correct place.

In the end, the paper was finished on time, and all of the students received
an A for their work. But the editor was exhausted from spending so much
time tracking revisions manually.

## Story: The Impossible Bug

There once was a programmer who was working on a project and he had just about
got everything to work, when one morning he found that the program was just crashing
every time he tried to run it. The programmer tried all kinds of things, but he couldn't
figure out what had changed to break the program. He spent an entire day trying to track
down where the problem was. Eventually he go so frustrated that he completely retyped
the entire program. Only then, when he was able to compare the retyped version against
the original, did he notice that one of the quotes in the file was a "curly" quote, 
which was the problem.

## Lesson learned: use version control

In all of these stories, there is something that is being done manually that would
be a lot easier if it was done by software. In the first story, the missing feature
was creating a backup of the most recent changes to a document. In the second story, it was
integrating changes from multiple authors. In the third story, it was seeing what
has changed in a document since the last time you worked on it.

Fortunately, there are several kinds of "version control" software. Any version
control system (except truly ancient ones) can easily upload file updates to
a remote server for safe backup. Similarly, any version control system provides
methods for letting multiple people work together on the same file and
sensibly resolve any conflicts between their changes. Finally, any version
control system will show you how your current files differ from the last
checked-in version.

One of the most popular version control systems is called "Git". Git is what
we'll be learning about in this project.