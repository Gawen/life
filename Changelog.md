# Changelog

## With 3 sounds, I can make computers talk with each other
Friday June 13 1997

I knew some computers could talk with each other over phone lines. I already heard the sound passing through the phone line (I don't remember how because I didn't have any modem that time). But I knew this noise was probably the data.

R2-D2 was doing simpler sounds to talk with C3PO though. In my electronic club, they told me how to generate such sounds (sine waves) and how to detect them. So I thought I could build a R2-D2-like modem.

But I asked myself : "how many sounds do I need ?" ("How many signals do I need to transmit data between two computers".)

And after a lot of thought, Eureka, my answer is 3.

Why ?

I can't remember. That's what I read from my manual, but I don't understand what I wrote.

Actually I kind of realized I had to send something like a clock through the line to make the receiver distingish each bit. That would mean I'd need 2 bits : one for the data, and one for the clock. That'd mean 4 sounds (one for 00, 01, 10 and 11).

But for some reason I decided it was 3, and even now I can't understand my manuals when I try to explain why. 3 is actually a good answer because it is possible for each bit send to change the sound and so avoid the fact the receiver will confuse two bits in one. But the decoding is kind of complex, requires graph theory, and I seriously don't think I got that at that age.

So if anybody understands why I tried to do this, please comment! :-)

## My first political virus
Tuesday May 27 1997

There is this French politician named "Le Pen" who prefers to spread hatred between peoples than peace and cooperation. And as my familly is pretty politically engaged and my father-side family is from Algeria, I decided to create the most powerful and anti-racist computer Virus ever existed : a Virus which will print "Le Pen is a big c***" when the computer starts.

Here some notes I wrote about this powerful Virus (in **QBasic** !).

![Page 1](http://gawen.me/life/tutorials/lepen/page_1.jpg)

Virus: Le Pen

1 Its role.

It won't do any anomaly on the computer it will reside on.
It'll put in ``AUTOEXEC.BAT`` one line which will prints: "LE PEN IS A BIG C***".

2 How it does it ?

It'll add in ``AUTOEXEC.BAT`` some lines which will be :

    CLS
    ECHO .  <-- (10 times)
    ECHO LE PEN IS A BIG C*** (or NINNY)
    ECHO .  <-- (9 times)
    PAUSE
    CLS


NB: I was a bit ashamed to have used the C-word, so I replaced it by 'ninny' in case my parents read my book.

![Page 2](http://gawen.me/life/tutorials/lepen/page_2.jpg)

The silent install program

    10 OPEN "C:/AUTOEXEC.BAT" FOR INPUT AS #1
    20 OPEN "C:/AUTOEXE1.BAT" FOR OUTPUT AS #2
    30 INPUT #1, A$
    40 IF EOF(1) THEN GOTO 70
    50 PRINT #2, A$
    60 GOTO 30
    70 FOR A = 1 TO 5
    80 PRINT #2, "ECHO "
    90 NEXT A
    100 PRINT #2, "ECHO LE PEN IS A BIG ****"
    110 CLOSE #1
    120 CLOSE #2
    130 END


Sorry, the code is not indented.

Please use at your own risk. This could damage your computer irremediably!

## V = R * I
Thursday April 04 1996

It was like normal afternoon children activities, like sports, but here for sciences.

Some great guys explained me how works a resistor, transistor, ... These was awesome times. I went there every Wednesday afternoon for several years.

## OK, so variables and instructions are actually english words
Friday July 28 1995

There is this program I can access through the DOS named ``QBasic``.

And actually it looks like the same than the Mupy. But there, variables and instructions are no longer numbers and images but English words.

My very first program:

    10 INPUT A
    20 INPUT B
    30 PRINT A+B

You can use this code, I licensed it under the MIT license. (You're welcome)

## Hey honey, I found this computer, it will teach you how to program
Sunday April 09 1995

Once, my mom came back with this weird box from a bric-a-brac sale.

There was a book, and a big calculator with weird keys with numbers and images on them.

The book told me how to create a program to ask the user a number, then an other, and prints the sum. Or other stuffs like that.

![mupy](http://gawen.me/life/images/mupy_pic.jpg)

Later, I understood this was actually a computer for children, with a very simple BASIC interpreter inside, based on a 4 bits microcontroller. It was aimed to learn children how to program. This toy was built in 1985 by a French company.

Unfortunately I lost this precious object. I'm looking actively to get a new one.

This definitely started my geek life.

Link: [French Silicium Article](http://www.silicium.org/site/index.php?option=com_content&view=article&id=136:info-realite-mupy&catid=40:france&Itemid=29)

## My first tutorial
Thursday November 17 1994

My mother explained me how worked the MS-DOS thing and this very beautiful and nice rendered MS Windows 3.11 (state of the art). Here's a HOWTO tutorial to open a .DOC file from a floppy.

![Page 1](http://gawen.me/life/tutorials/open_doc_from_floppy/page_1.jpg)

Book of Computers and Floppies. Thursday November 1994, 17th

![Page 2](http://gawen.me/life/tutorials/open_doc_from_floppy/page_2.jpg)

Explanation to enter in a floppy which doesn't have any name in a 386SX computer.

You press on the "W" key then you press on the "Enter" key. After you click on the "Window" press on the screen then you press the sentence at the very top of the square. You go to "File Explorer" You put ...
 
![Page 3](http://gawen.me/life/tutorials/open_doc_from_floppy/page_3.jpg)

... the floppy. You press the key on the screen "A:/".

End

Turn the page

![Page 4](http://gawen.me/life/tutorials/open_doc_from_floppy/page_4.jpg)

* Way to write on computer

To put a file you go to File Explorer. You go to the C:/ key on the screen. You go to Window the key on the screen you go to DOC. You take your font. You click once. You go in "File". You go in "Copy". The computer asks you in which thing there you put the floppy. Go in "Copy".

End

## My first computer
Monday March 21 1994

My father needed to write a dissertation for his job. He wanted to try writing it on a computer for the first time.

Moreover my parents thought the computer thing may be something important in the future, and they wanted me to know few things about it.

Best decision ever...

![386 SX](http://gawen.me/life/images/386sx.jpg)

## I Like Molliere
Wednesday October 13 1993

![Les Trétaux du Charrel](http://gawen.me/life/images/amateur_stage.jpg)

## Hello, World!
Wednesday September 02 1987

:-)

