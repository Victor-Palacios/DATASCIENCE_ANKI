## Thanks!

If you're reading this, you're probably looking to contributing to this project. 
**The fact that you're considering spending some time here is very generous of you.**
Thank you very much!

If you have any questions, feel free to reach out to Victor Palacios, the author and maintainer.

## Goal of this Repository

To create and maintain a free, intelligent, flashcard repository for data science as a community. 

### How Goal is Achieved

Anki flashcards ([VIDEO](https://youtu.be/FHVOAr8MxxQ?t=88), [DOWNLOAD](https://apps.ankiweb.net), and [ARTICLE](https://www.freecodecamp.org/news/use-spaced-repetition-with-anki-to-learn-to-code-faster-7c334d448c3c/)),
Cloze Deletion ([VIDEO](https://www.youtube.com/watch?v=IRY1rYxd9EM) and [MANUAL](https://apps.ankiweb.net/docs/manual.html#cloze-deletion)), and
Occlusion ([VIDEO](https://www.youtube.com/watch?v=c-4xOe79epU&list=PL3MozITKTz5YFHDGB19ypxcYfJ1ITk_6o&index=2&t=0s) and [DOWNLOAD](https://ankiweb.net/shared/info/1374772155)).

#### More about Anki

Anki is a free, intelligent, flashcard system that maximizes learning and minimizes repetition.

Once you understand the basics of how Anki works, you can watch how to [make optimal flashcards](https://www.youtube.com/watch?v=AbvaITy3oeQ) because if you make bad Anki cards, that will demotivate and make you feel like you’re wasting your time. As well, **making optimal Anki flashcards is a requirement if you wish to contribute flashcards to this repository**.

While Anki does have data science [decks already uploaded](https://ankiweb.net/shared/decks/Data%20Sci), most are not optimized for learning and frequently violate the [minimum information principle](https://www.supermemo.com/en/archives1990-2015/articles/20rules#minimum%20informationprinciple).

## Ways to Contribute
1. Create Anki cloze deletion or occlusion flashcards and upload them to this repository
2. Make this repository more beautiful by reading:
  - [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) and adding tables, images, etc
  - [36 Amazing Python Open Source Projects (v.2019)](https://medium.mybridge.co/36-amazing-python-open-source-projects-v-2019-2fe058d79450) to get a sense of what beautiful projects look like
  - [Starting an Open Source Project guide](https://opensource.guide/starting-a-project/)
3. Correct anything: mistakes on any flashcards, grammatical errors on the repository, or missing words anywhere (unless omitted for spacing issues on flashcards)
4. Clarify anything: hard-to-understand paragraphs, etc.

### Contributing Anki Cloze Deletion Flashcards

Here are rules and examples of the types of the cards you should contribute and should not contribute:

**FLASHCARD RULES**

1. Cloze Deletion or Occlusion flashcards only
  >Why? These types of cards typically adhere to the [minimum information principle](https://www.supermemo.com/en/archives1990-2015/articles/20rules#minimum%20informationprinciple)
2. 7 lines maximum per flashcard (that is, 7 returns/enters)
  >Why? Less is better. Looking at a giant blob of text can be demotivating. You want the flashcards to pack as much information as succinctly as possible. Want to read more about memory and learning? See the [Anki manual](https://apps.ankiweb.net/docs/manual.html#active-recall-testing).
3. 42 characters maximum per line (spaces count as 1 character)
  >Why? 7 lines x 42 characters per line fits perfectly on small phone screens so no scrolling is needed to answer a flash card.
4. Leave at least 1 of the 7 lines free of text (i.e., include at least 1 blank line)
  >Why? 7 full lines of text is daunting, especially back-to-back. The goal is to learn 40 cards per day, review 160 cards per day, and do both in 1 hour exactly. For that to be the case, as a general rule, if you can’t answer a card within about 15 seconds, it’s probably better to give up and show the answer than keep struggling to remember. That is only possible if we constrain how much text is on a single card.
5. No algorithms because they typically violate rule 2, 3, 4 and the minimum information principle
  >Why? In general, Anki is not meant to learn complex material, but rather focus on building block items so that when you encounter complex material it is easier to absorb and recall later.
6. Don’t create tricky wording cards (ex: FRONT remove “x” from list with index number BACK del lst[0])
  >Why? You will review these cards hundreds of times. It is best that you review only meaningful information to develop your spidey sense (that sense when you know something is wrong or right, but can't explain why right away). This sense is best developed by practicing straightforward cards.
7. Don’t copy and paste any paid source material into your flashcards that you upload to this public deck (like DataCamp material for example) (this type of material is okay for personal decks but not for publicly shared decks)
  >Why? We don't want companies asking us to take this deck off the web. If in doubt, make sure to use generic terms for something like python code: df.z.plot(x,y), or write things in your own voice, or summarize, etc.
8. Tag each card with 1 of 7 categories (i.e., statistics, python, machine learning, deep learning, statistics + python, machine learning + python, or deep learning + python)
  >Why? This helps me create [sub-decks](https://www.reddit.com/r/Anki/comments/5nujhp/how_to_make_subdecks_and_organize_your_collection/) so that people learning data science can choose what topics they want to study or review first.
9. If cards require explanation, use as much space on the BACK of the flashcard as needed
  >Why? Take all the time you need to understand why the front of the card has the answer it does, but when reviewing, minimal information on the front of the card is paramount.

Helpful, but not required:

1. Remove articles (a, the, etc.) if you don't absolutely need them
  >Why? Reduction of cognitive load and reading time.
2. Use arrows, colons, and other symbols like <, >,or = to show transformation or separate ideas instead of using words 
  >Why? Humans process imagery faster than words.
3. Use # to indicate the topic (like Melt, DF, Regression, etc.), followed by a blank space, and then the Cloze Deletion or Occlusion
  >Why? Directing your mind where to focus helps your attention.

**GREAT EXAMPLES:**

<img src="https://github.com/Victor-Palacios/Data_Science_Interview_Questions_using_Cloze_Deletion/blob/master/IMAGES/Anki_Flashcard_Front.png" width="600">

<img src="https://github.com/Victor-Palacios/Data_Science_Interview_Questions_using_Cloze_Deletion/blob/master/IMAGES/Anki_Flashcard_Back.png" width="600">

**AVOID THIS:**

<img src="https://github.com/Victor-Palacios/Data_Science_Interview_Questions_using_Cloze_Deletion/blob/master/IMAGES/AVOID_Anki_Flashcard_Front.png" width="600">

<img src="https://github.com/Victor-Palacios/Data_Science_Interview_Questions_using_Cloze_Deletion/blob/master/IMAGES/AVOID_Anki_Flashcard_Back.png" width="600">

<img src="https://github.com/Victor-Palacios/Data_Science_Interview_Questions_using_Cloze_Deletion/blob/master/IMAGES/AVOID_Anki_Flashcard.png" width="600">

## Setting Up to Contribute
1. Download [Anki](https://apps.ankiweb.net)
2. Download [Image Occlusion](https://ankiweb.net/shared/info/1374772155) to Anki
  >Or to download this add-on, please copy and paste the following code into Anki: 1374772155
3. Download [CrowdAnki: JSON export&import](https://ankiweb.net/shared/info/1788670778) to Anki
  >Or to download this add-on, please copy and paste the following code into Anki: 1788670778
4. Create a GitHub account for yourself
5. Clone this repository to your account
  >If you need a refresher on how to do this and the steps below, this [repository](https://github.com/Stvad/CrowdAnki/blob/master/README.md#import-from-github) covers these in greater detail.
6. Create a branch to hold your changes: Always branch out from `master` to work on your contribution. It's good practice to never work on the `master` branch.
7. Open the "Learn Fundamentals of Data Science with Anki using Cloze Deletion and Image Occlusion" deck in Anki using Anki's import 
  >It's a JSON file located in the 00_MASTER_Anki_JSON_file folder (I recommend using https://desktop.github.com to manipulate github without using the terminal) 
8. Try studying from the deck to get a feel for how the flashcards are made.
9. Once you're comfortable with Anki, create your own deck using Create Deck (title it: New_Cards_Your_GitHub_UserName) if you want to add flashcards to this repository
  >If you want to edit/correct/improve cards in the master deck, simply write which card(s) need(s) improvement in the Issues section of Github and I'll fix it.
10. Export your new deck that you want to add to the master deck via Export in Anki and use the format "CrowdAnki JSON"
11. Add your new deck (in json format) into the 01_UNDER_REVIEW folder.
12. Sync and your done!
  >I'll review the cards you want to add, then give feedback if anything needs to be changed. If there's no feedback needed, I'll just add your cards to the master deck.

## Code of Conduct

The following quote sums up the **Code of Conduct**.

   > Be cordial or be on your way. --Kenneth Reitz

This guide is based on the [Camelot: PDF Table Extraction for Humans](https://github.com/atlanhq/camelot/blob/master/CONTRIBUTING.md) contributor's guide.
