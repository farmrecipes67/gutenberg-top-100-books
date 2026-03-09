# 📚 Gutenberg Top 100 Books - AI Analysis

> JSON data for the top 100 most popular Project Gutenberg books including AI-generated summaries, character analyses, geographic locations, and unusual vocabulary.

<!-- Open Graph Tags -->
<!-- og:title = "Gutenberg Top 100 Books - AI Analysis" -->
<!-- og:description = "Comprehensive AI-generated analysis of the 100 most popular public domain books from Project Gutenberg" -->
<!-- og:type = "website" -->

## 🌟 About

This repository contains structured JSON data for the **100 most downloaded books** from [Project Gutenberg](https://www.gutenberg.org), the world's oldest digital library of free eBooks.

Each book has been analyzed using AI (powered by OpenAI GPT models) based on the **actual book text** to extract:

- **📝 Summary** — A concise ~100-word summary
- **👥 Characters** — Major and notable characters with name, estimated age, personality traits, and lifespan/fate
- **🗺️ Locations** — Geographic locations mentioned in the text with real latitude/longitude coordinates
- **📖 Unusual Words** — 100 rare, archaic, or unusual words found in the text with definitions and context

## 📁 Structure

```
├── README.md
├── index.json          # Master index of all 100 books
└── books/
    ├── 00001-the-declaration-of-independence.json
    ├── 00011-alices-adventures-in-wonderland.json
    └── ... (100 book files)
```

## 📊 Data Format

Each book JSON file follows this schema:

```json
{
  "gutenberg_id": 11,
  "title": "Alice's Adventures in Wonderland",
  "author": "Carroll, Lewis",
  "gutenberg_url": "https://www.gutenberg.org/ebooks/11",
  "summary": "...",
  "characters": [
    {
      "name": "Alice",
      "age": "7-8 years old",
      "personality": "Curious, imaginative, polite",
      "lifespan": "Survives; wakes from dream"
    }
  ],
  "locations": [
    {
      "name": "Oxford, England",
      "latitude": 51.752,
      "longitude": -1.2577
    }
  ],
  "unusual_words": [
    {
      "word": "antipathies",
      "definition": "Deep-seated feelings of aversion",
      "context": "Alice confuses 'antipodes' with 'antipathies'"
    }
  ]
}
```

## 📚 Books Included

| # | Title | Author | Gutenberg ID |
|---|-------|--------|--------------|
| 1 | Frankenstein; or, the modern prometheus | Shelley, Mary Wollstonecraft | [84](https://www.gutenberg.org/ebooks/84) |
| 2 | Wuthering Heights | Brontë, Emily | [768](https://www.gutenberg.org/ebooks/768) |
| 3 | Moby Dick; Or, The Whale | Melville, Herman | [2701](https://www.gutenberg.org/ebooks/2701) |
| 4 | Pride and Prejudice | Austen, Jane | [1342](https://www.gutenberg.org/ebooks/1342) |
| 5 | Romeo and Juliet | Shakespeare, William | [1513](https://www.gutenberg.org/ebooks/1513) |
| 6 | The Complete Works of William Shakespeare | Shakespeare, William | [100](https://www.gutenberg.org/ebooks/100) |
| 7 | A Room with a View | Forster, E. M. (Edward Morgan) | [2641](https://www.gutenberg.org/ebooks/2641) |
| 8 | Alice's Adventures in Wonderland | Carroll, Lewis | [11](https://www.gutenberg.org/ebooks/11) |
| 9 | Simple Sabotage Field Manual | United States. Office of Strategic Services | [26184](https://www.gutenberg.org/ebooks/26184) |
| 10 | The strange case of Dr. Jekyll and Mr. Hyde | Stevenson, Robert Louis | [43](https://www.gutenberg.org/ebooks/43) |
| 11 | Middlemarch | Eliot, George | [145](https://www.gutenberg.org/ebooks/145) |
| 12 | Little Women; Or, Meg, Jo, Beth, and Amy | Alcott, Louisa May | [37106](https://www.gutenberg.org/ebooks/37106) |
| 13 | The Great Gatsby | Fitzgerald, F. Scott (Francis Scott) | [64317](https://www.gutenberg.org/ebooks/64317) |
| 14 | Jane Eyre: An Autobiography | Brontë, Charlotte | [1260](https://www.gutenberg.org/ebooks/1260) |
| 15 | The Blue Castle: a novel | Montgomery, L. M. (Lucy Maud) | [67979](https://www.gutenberg.org/ebooks/67979) |
| 16 | Crime and Punishment | Dostoyevsky, Fyodor | [2554](https://www.gutenberg.org/ebooks/2554) |
| 17 | The Enchanted April | Von Arnim, Elizabeth | [16389](https://www.gutenberg.org/ebooks/16389) |
| 18 | The Picture of Dorian Gray | Wilde, Oscar | [174](https://www.gutenberg.org/ebooks/174) |
| 19 | Twenty years after | Dumas, Alexandre | [1259](https://www.gutenberg.org/ebooks/1259) |
| 20 | My Life — Volume 1 | Wagner, Richard | [5197](https://www.gutenberg.org/ebooks/5197) |
| 21 | Cranford | Gaskell, Elizabeth Cleghorn | [394](https://www.gutenberg.org/ebooks/394) |
| 22 | The Expedition of Humphry Clinker | Smollett, T. (Tobias) | [2160](https://www.gutenberg.org/ebooks/2160) |
| 23 | The Adventures of Ferdinand Count Fathom — Complete | Smollett, T. (Tobias) | [6761](https://www.gutenberg.org/ebooks/6761) |
| 24 | Beowulf: An Anglo-Saxon Epic Poem | Unknown Author | [16328](https://www.gutenberg.org/ebooks/16328) |
| 25 | The Adventures of Roderick Random | Smollett, T. (Tobias) | [4085](https://www.gutenberg.org/ebooks/4085) |
| 26 | History of Tom Jones, a Foundling | Fielding, Henry | [6593](https://www.gutenberg.org/ebooks/6593) |
| 27 | A Modest Proposal: For preventing the children of poor people in Ireland, from being a burden on their parents or country, and for making them beneficial to the publick | Swift, Jonathan | [1080](https://www.gutenberg.org/ebooks/1080) |
| 28 | A Doll's House : a play | Ibsen, Henrik | [2542](https://www.gutenberg.org/ebooks/2542) |
| 29 | Dracula | Stoker, Bram | [345](https://www.gutenberg.org/ebooks/345) |
| 30 | The Importance of Being Earnest: A Trivial Comedy for Serious People | Wilde, Oscar | [844](https://www.gutenberg.org/ebooks/844) |
| 31 | Adventures of Huckleberry Finn | Twain, Mark | [76](https://www.gutenberg.org/ebooks/76) |
| 32 | A Tale of Two Cities | Dickens, Charles | [98](https://www.gutenberg.org/ebooks/98) |
| 33 | The King in Yellow | Chambers, Robert W. (Robert William) | [8492](https://www.gutenberg.org/ebooks/8492) |
| 34 | The Adventures of Sherlock Holmes | Doyle, Arthur Conan | [1661](https://www.gutenberg.org/ebooks/1661) |
| 35 | The Count of Monte Cristo | Dumas, Alexandre | [1184](https://www.gutenberg.org/ebooks/1184) |
| 36 | The Brothers Karamazov | Dostoyevsky, Fyodor | [28054](https://www.gutenberg.org/ebooks/28054) |
| 37 | The Yellow Wallpaper | Gilman, Charlotte Perkins | [1952](https://www.gutenberg.org/ebooks/1952) |
| 38 | 韓詩外傳, Complete | Han, Ying, active 150 B.C. | [7290](https://www.gutenberg.org/ebooks/7290) |
| 39 | The Prince | Machiavelli, Niccolò | [1232](https://www.gutenberg.org/ebooks/1232) |
| 40 | Leviathan | Hobbes, Thomas | [3207](https://www.gutenberg.org/ebooks/3207) |
| 41 | Great Expectations | Dickens, Charles | [1400](https://www.gutenberg.org/ebooks/1400) |
| 42 | Metamorphosis | Kafka, Franz | [5200](https://www.gutenberg.org/ebooks/5200) |
| 43 | Embers, Complete | Parker, Gilbert | [6271](https://www.gutenberg.org/ebooks/6271) |
| 44 | Grimms' Fairy Tales | Grimm, Jacob | [2591](https://www.gutenberg.org/ebooks/2591) |
| 45 | White nights, and other stories | Dostoyevsky, Fyodor | [36034](https://www.gutenberg.org/ebooks/36034) |
| 46 | The Scarlet Letter | Hawthorne, Nathaniel | [25344](https://www.gutenberg.org/ebooks/25344) |
| 47 | Walden, and On The Duty Of Civil Disobedience | Thoreau, Henry David | [205](https://www.gutenberg.org/ebooks/205) |
| 48 | Ulysses | Joyce, James | [4300](https://www.gutenberg.org/ebooks/4300) |
| 49 | The Adventures of Tom Sawyer, Complete | Twain, Mark | [74](https://www.gutenberg.org/ebooks/74) |
| 50 | Thus Spake Zarathustra: A Book for All and None | Nietzsche, Friedrich Wilhelm | [1998](https://www.gutenberg.org/ebooks/1998) |
| 51 | The Souls of Black Folk | Du Bois, W. E. B. (William Edward Burghardt) | [408](https://www.gutenberg.org/ebooks/408) |
| 52 | War and Peace | Tolstoy, Leo, graf | [2600](https://www.gutenberg.org/ebooks/2600) |
| 53 | Anne of Green Gables | Montgomery, L. M. (Lucy Maud) | [45](https://www.gutenberg.org/ebooks/45) |
| 54 | Moby Multiple Language Lists of Common Words | Ward, Grady | [3206](https://www.gutenberg.org/ebooks/3206) |
| 55 | Second Treatise of Government | Locke, John | [7370](https://www.gutenberg.org/ebooks/7370) |
| 56 | The Confessions of St. Augustine | Augustine, of Hippo, Saint | [3296](https://www.gutenberg.org/ebooks/3296) |
| 57 | Treasure Island | Stevenson, Robert Louis | [120](https://www.gutenberg.org/ebooks/120) |
| 58 | Narrative of the Life of Frederick Douglass, an American Slave | Douglass, Frederick | [23](https://www.gutenberg.org/ebooks/23) |
| 59 | 肉蒲團 | Li, Yu | [52205](https://www.gutenberg.org/ebooks/52205) |
| 60 | Oedipus King of Thebes: Translated into English Rhyming Verse with Explanatory Notes | Sophocles | [27673](https://www.gutenberg.org/ebooks/27673) |
| 61 | The Enchiridion | Epictetus | [45109](https://www.gutenberg.org/ebooks/45109) |
| 62 | The Odyssey: Rendered into English prose for the use of those who cannot read the original | Homer | [1727](https://www.gutenberg.org/ebooks/1727) |
| 63 | Meditations | Marcus Aurelius, Emperor of Rome | [2680](https://www.gutenberg.org/ebooks/2680) |
| 64 | The Wonderful Wizard of Oz | Baum, L. Frank (Lyman Frank) | [55](https://www.gutenberg.org/ebooks/55) |
| 65 | The Republic | Plato | [1497](https://www.gutenberg.org/ebooks/1497) |
| 66 | The City of God, Volume I | Augustine, of Hippo, Saint | [45304](https://www.gutenberg.org/ebooks/45304) |
| 67 | Beyond Good and Evil | Nietzsche, Friedrich Wilhelm | [4363](https://www.gutenberg.org/ebooks/4363) |
| 68 | The lesser Key of Solomon, Goetia, the book of evil spirits : $b contains two hundred diagrams and seals for invocation and convocation of spirits, necromancy, witchcraft and black art | Unknown Author | [72679](https://www.gutenberg.org/ebooks/72679) |
| 69 | A Study in Scarlet | Doyle, Arthur Conan | [244](https://www.gutenberg.org/ebooks/244) |
| 70 | The divine comedy | Dante Alighieri | [8800](https://www.gutenberg.org/ebooks/8800) |
| 71 | The Works of Edgar Allan Poe — Volume 2 | Poe, Edgar Allan | [2148](https://www.gutenberg.org/ebooks/2148) |
| 72 | Sense and Sensibility | Austen, Jane | [161](https://www.gutenberg.org/ebooks/161) |
| 73 | The Interesting Narrative of the Life of Olaudah Equiano, Or Gustavus Vassa, The African: Written By Himself | Equiano, Olaudah | [15399](https://www.gutenberg.org/ebooks/15399) |
| 74 | The Hound of the Baskervilles | Doyle, Arthur Conan | [2852](https://www.gutenberg.org/ebooks/2852) |
| 75 | Gulliver's Travels into Several Remote Nations of the World | Swift, Jonathan | [829](https://www.gutenberg.org/ebooks/829) |
| 76 | Paul Clifford — Complete | Lytton, Edward Bulwer Lytton, Baron | [7735](https://www.gutenberg.org/ebooks/7735) |
| 77 | Modern ships of war | Reed, Edward J. (Edward James), Sir | [73887](https://www.gutenberg.org/ebooks/73887) |
| 78 | Anna Karenina | Tolstoy, Leo, graf | [1399](https://www.gutenberg.org/ebooks/1399) |
| 79 | 池北偶談 | Wang, Shizhen | [25162](https://www.gutenberg.org/ebooks/25162) |
| 80 | The Ballad of the White Horse | Chesterton, G. K. (Gilbert Keith) | [1719](https://www.gutenberg.org/ebooks/1719) |
| 81 | Frankenstein; Or, The Modern Prometheus | Shelley, Mary Wollstonecraft | [41445](https://www.gutenberg.org/ebooks/41445) |
| 82 | Heart of Darkness | Conrad, Joseph | [219](https://www.gutenberg.org/ebooks/219) |
| 83 | On Liberty | Mill, John Stuart | [34901](https://www.gutenberg.org/ebooks/34901) |
| 84 | Ang "Filibusterismo" (Karugtóng ng Noli Me Tangere) | Rizal, José | [47629](https://www.gutenberg.org/ebooks/47629) |
| 85 | Don Quixote | Cervantes Saavedra, Miguel de | [996](https://www.gutenberg.org/ebooks/996) |
| 86 | A Christmas Carol in Prose; Being a Ghost Story of Christmas | Dickens, Charles | [46](https://www.gutenberg.org/ebooks/46) |
| 87 | The Art of War | Sunzi, active 6th century B.C. | [132](https://www.gutenberg.org/ebooks/132) |
| 88 | The Romance of Lust: A classic Victorian erotic novel | Anonymous | [30254](https://www.gutenberg.org/ebooks/30254) |
| 89 | The Iliad | Homer | [6130](https://www.gutenberg.org/ebooks/6130) |
| 90 | The Reign of Greed | Rizal, José | [10676](https://www.gutenberg.org/ebooks/10676) |
| 91 | Peter Pan : $b [Peter and Wendy] | Barrie, J. M. (James Matthew) | [16](https://www.gutenberg.org/ebooks/16) |
| 92 | 隨園詩話 | Yuan, Mei | [52206](https://www.gutenberg.org/ebooks/52206) |
| 93 | Frankenstein; Or, The Modern Prometheus | Shelley, Mary Wollstonecraft | [42324](https://www.gutenberg.org/ebooks/42324) |
| 94 | How the Other Half Lives: Studies Among the Tenements of New York | Riis, Jacob A. (Jacob August) | [45502](https://www.gutenberg.org/ebooks/45502) |
| 95 | McTeague: A Story of San Francisco | Norris, Frank | [165](https://www.gutenberg.org/ebooks/165) |
| 96 | Bleak House | Dickens, Charles | [1023](https://www.gutenberg.org/ebooks/1023) |
| 97 | Les Misérables | Hugo, Victor | [135](https://www.gutenberg.org/ebooks/135) |
| 98 | The Turn of the Screw | James, Henry | [209](https://www.gutenberg.org/ebooks/209) |
| 99 | The Poems of Giacomo Leopardi | Leopardi, Giacomo | [19315](https://www.gutenberg.org/ebooks/19315) |
| 100 | Dubliners | Joyce, James | [2814](https://www.gutenberg.org/ebooks/2814) |

## 🤖 Generation Details

- **Source**: [Project Gutenberg](https://www.gutenberg.org) top 100 most popular books
- **AI Analysis**: OpenAI GPT models via automated pipeline
- **Generated**: 2026-03-09
- **Created by**: [Papersaurus](https://github.com/farmrecipes67) 🦕

## 📄 License

The book texts are in the **public domain** courtesy of Project Gutenberg. The AI-generated analyses in this repository are provided as-is for educational and research purposes.

## 🙏 Acknowledgments

- [Project Gutenberg](https://www.gutenberg.org) for making literature freely accessible
- [Gutendex API](https://gutendex.com) for the catalog API
- AI models for analysis generation

---

*Built with love by Papersaurus 🦕✨*
