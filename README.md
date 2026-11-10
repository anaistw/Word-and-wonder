# Word-and-wonder
I don’t wait for the perfect app. I build it. A daily AI tutor for Chinese, Danish and general knowledge, made with Claude and zero hand-written code.

Try it: https://claude.ai/artifact/CdJZuU1sCfNTPc6iB8hxWf

Word & Wonder screenshot

What it does

The page has four tabs:

Chinese: 5 words on one theme, with pinyin, flip cards, a grammar tip, a short chat and a quiz.
Danish: the same at B1 level.
Brain Food: an evening general-knowledge lesson, told like a short story, plus a debate, a poem and a quiz.
Deck: every word I've learned so far, to shuffle and review.

And during the day, I get short messages on my phone:

Time: Morning, Midday & Afternoon.	
What I get
Morning: Today's words and a link to the page
Midday:	A playful recall challenge, with no answers
Afternoon:	New example sentences and yesterday's words
+ 
Evening	The Brain Food lesson

How it works

It's built from four simple pieces:

One page, one link. The page never changes address. 
Only its content changes, so I can pin it to my phone's home screen.

A small database behind the page. Each day is saved as one record. 
This is what keeps my history for the Deck.

Scheduled tasks as the "teacher." 
Each task is a full prompt that runs at a set time, writes the day's lesson and sends me a notification.

Variety on purpose. Cards, chats, debates, poems and quizzes. 
Each weekday has its own theme, so it never feels like the same lesson twice. 

**************
Build your own

Everything was made by prompting Claude, without writing code by hand.

The full step-by-step guide and the master prompt are in guide/.
To make one for another topic, start a new chat with: "Rebuild Word & Wonder, but for [topic]" and attach the guide.

Ideas: interview prep, a daily marketing case study, a book-a-day club.

What I learned

Saying what felt boring got the biggest improvements.
Being specific about my level ("module 5 of my course") worked much better than "intermediate."
Habits beat features. The notifications are what keep me coming back, the same way good apps keep their users.

***************

Built by Anaïs with Claude. Feedback and ideas are welcome!
