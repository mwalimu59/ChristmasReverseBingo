# Christmas Reverse Bingo

It's a game of bingo with a Christmas/holiday song in each square. Any time you hear one of the songs on the card, you mark off that square, and if you mark off five squares in the same row, column, or diagonal you get bingo. Just like the traditional game, except...

It's reverse bingo. If you get bingo, you lose. You win the game by reaching the end of the designated time period without getting bingo, which runs from December 1st through Christmas Eve. And the card has 25 of the most overplayed, hardest to avoid songs on it, so... good luck and best wishes.

In case this sounds familiar, perhaps you've played or at least heard of [Whamageddon](https://whamageddon.com/) and its variants like Mariahpocalypse, or [The Little Drummer Boy Challenge](https://littledrummerboychallenge.com/). Christmas Reverse Bingo drew inspiration from these games and its rules are based in part on their rules. In those games, you lose the game if you hear only one song, but in Christmas Reverse Bingo you have to hear a minimum of five.

## How to Play

First, you need to decide which song list you're playing, the short list or the full list. The short list has 25 songs and every card has the same 25 songs arranged at random. The full list has 75 songs (the 25 from the short list plus 50 more) and each card has 25 chosen randomly from among those 75. The short list version is harder to win if I've done a good job of identifying which 25 songs are hardest to avoid. The full list, besides being easier to win, has more variety and could make the game more interesting if you're playing multiple cards or have a large group playing the game.

Second, you need bingo cards. You have two options here. The first option is the two .pdf files included in this repository. These have 100 cards each, one with short list cards and the other with full list cards. You can print as many pages from these as you need.

The second option is to use the spreadsheet:
1. Download and open the spreadsheet (the .ods or the .xls file in the repository; either should work).
2. You will see two tabs at the bottom, 'Short List' and 'Full List'. Select one of these.
3. Edit the number in the cell to the right of 'Card #:' to any number you like and press enter or click any other cell to make the card update.
4. Print the card; depending on your setup you may be able to print-to-file or print-to-PDF if that works better for you.
5. Repeat the above two steps as many times as the number of cards needed. If desired, you may switch between Short List and Full List.

## The rules

1. It's reverse bingo. If you get bingo, you lose. If you make it all the way to Christmas Day without getting bingo, you win.
2. The game begins at midnight (12:00am) on December 1, and runs through Christmas Eve, ending at midnight (12:00am) on Christmas Day.
3. As soon as you hear enough of any song to recognize it, you must mark it on your bingo card.
4. Any re-recording, remaster, or remix by the same artist counts.
5. If you hear a cover version by a different artist, you're safe (unless of course that version is also on your bingo card).
6. If the title or artist doesn't match exactly but it's the same recording, it still counts. In other words, the recording speaks for itself. Some examples:
 - "The Christmas Song (Chestnuts Roasting)" is sometimes billed as "The Christmas Song (Merry Christmas to All)";
 - "I Believe in Father Christmas", properly attributed to Greg Lake, is sometimes billed as by Emerson, Lake & Palmer;
 - "The Chipmunk Song (Christmas Don't Be Late)" is variously attributed to Alvin and the Chipmunks or simply The Chipmunks.
7. There are some gray areas. These include mashups and collaborations where the artist billed is among them. Use your judgment.

## FAQs

Q: How did you come up with the game?  
A: I don't actually remember how or when I first thought of creating a 'Whamageddon on steroids' with a bingo card. At first I was uncertain if I could come up with 25 songs that are overplayed and unavoidable enough to merit inclusion in the game, but once I started digging, I discovered there are many more than 25 that could qualify and it became a problem of paring down the list. I had also been thinking in terms of producing a single bingo card for all the world, leading to the question of which songs to put in the middle square and the diagonals, since those squares are in more bingos. Eventually I landed on the idea of making the cards random, which not only solved that problem but makes for a more interesting game if you've got a group of people playing different randomly generated cards.

Q: What about the song list?  
A: Ah, yes. I ran a bunch of web searches for lists of most annoying and most overplayed holiday songs, and lists of the most popular Christmas songs. I posted a query on Reddit and received a lot of helpful responses. One resource I used was [The Billboard Holiday 100](https://www.billboard.com/charts/hot-holiday-songs/). On the question of whether to keep it to 25 songs or incorporate more, I ended up making two versions of the game, the short list and the full list. For the full list I chose the number 75 because it's what's used in the normal game of bingo, plus it felt like about the right amount to cut it off at to avoid diluting the game too much with less overplayed songs. For the short list, I decided to include only one song by any artist and only one version of any song. For the full list I'm allowing two per artist and two versions of any song (possibly more for parodies). It's better to have more artists represented in the list than to have a sizable chunk of it taken up by Bing Crosby and Michael Bublé.

Q: There are songs I think should (or shouldn't) be on the short and/or full lists!  
A: The current lists are pretty much a done deal for 2026, but I'll be revisiting the song lists for next year and would be glad to hear your opinions and suggestions for future year updates.

Q: Why Christmas when there are several other seasonal holidays that time of year?  
A: Mostly because none of those other holidays have such a glut of music that we can't avoid hearing that time of year. When is the last time you heard any song related to Hanukkah and thought you were tired of hearing it every year? If anything the game is less a celebration of Christmas than an indictment of a music industry that keeps feeding us the same short playlist of songs year after year. Also note that some of the songs don't mention Christmas, Santa Claus, or the nativity at all, such as *Jingle Bells* and *Winter Wonderland*.

Q: Why isn't there a free square in the middle?  
A: I could have included one, but that would make the game easier to lose. Is that what you really want? But if you really want one, feel free (no pun intended) to edit the contents of that square in the spreadsheet.

Q: What programs does the spreadsheet work with?  
A: I developed it using OpenOffice Calc. I uploaded it to Google Sheets and it apparently works well. I don't have Microsoft Excel on my computer and haven't been able to test it as well as I would like to have, but it worked okay when tried it in [Excel for the Web](https://excel.cloud.microsoft/). If you try it with others, please tell me the results, especially if something doesn't work and you're able to fix it.

Q: What's in those hidden rows of the spreadsheet?  
A: The song list and a random number generator. You're welcome to unhide the rows and study them if you wish, but I highly recommend having those rows hidden when printing bingo cards; otherwise it will print those rows and you'll end up wasting paper and printer ink.

Q: What kind of random number generator is that and why did you do it that way?  
A: First of all, I decided against using the spreadsheet's RAND function because there was no way to set a seed that would give me a reproducible sequence of pseudo-random numbers, especially not across different spreadsheet software. I wanted the bingo cards to be reproducible by anyone anywhere, an idea I got from the old Windows solitaire game Freecell. So basically I rolled my own random number generator, a [linear congruential generator](https://en.wikipedia.org/wiki/Linear_congruential_generator), using arithmetic functions that should be standard across all spreadsheet software. The RNG cycles N times (where N is the number of songs in the list) and uses the RANK and INDEX functions to populate the squares of the bingo card.

Q: What card numbers are valid?  
A: It should work for any integer between 0 and 2,147,483,647 (max int 32). If you need more bingo cards than that, I'd really like to know what you're doing with the game. I've experimented with negative numbers and decimal numbers and they worked, but I won't guarantee those will work correctly or reproducibly in all cases.

Q: It's not even Thanksgiving and I've already heard several songs on the list!  
A: Relax! The game doesn't start until December 1st. The same goes for Christmas Day when the game is already over. If it's still November (I'm assuming you meant US Thanksgiving, not Canadian Thanksgiving), it might be a good time to listen to, familiarize yourself with, and enjoy the songs you'll be trying to avoid for 24 days.

Q: Can I make up my own game that uses your bingo cards? Can I modify your game to use a different song list?  
A: Of course! This is GitHub. If you want to make up your own rules or your own song list, you're welcome to.

Q: Can I send you money?  
A: I don't want your money. I'd much rather hear about what you do with the game and how it goes.
