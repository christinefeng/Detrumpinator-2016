# Detrumpinator-2016

### Inspiration
We came into this hackathon aiming to create a lighthearted Chrome extension that helps people take life less seriously! We considered a lot of topics targeting various phenomena on the internet – memes, clickbait, spambots, cyberbullying, etc. – but eventually settled on politics, which we're sure has been on everyone's mind in light of recent events. Our aim was to build something that would find comedy in the oversaturation of the 2016 Presidential election all over the internet without getting too political.

### What it does
The Detrumpinator 2016 replaces all mentions of "Donald" with a random adjective, all mentions of "Trump" with a random noun, all mentions of "Make America Great Again" with a random wholesome catchphrase, and all mentions of "#maga" with a random popular Instagram hashtag.

### How we built it
We used [this template](https://9to5google.com/2015/06/14/how-to-make-a-chrome-extensions/) as a foundation for our extension, but modified it significantly to incorporate libraries of nouns and adjectives (which we created from scratch), as well as code to choose random items from these collections of words.

### Challenges we ran into
After we decided to build this extension, we realized we didn't really know how to implement a lot of the features we had envisioned. Just one example: when the extension finds the string "donaldtrump" on the page (e.g. in URLs or usernames), it successfully replaces the term with a correctly-formatted string (all lowercase, with spaces removed). However, in Twitter handles like @IvankaTrump, we haven't thought of a way to detect that and replace her last name with a correctly formatted noun yet. Also, the extension doesn't work on certain websites, such as the homepages of Buzzfeed and Facebook, and it doesn't work on the Google search page for Donald Trump until you toggle Safesearch on/off. We hope to find out why, and fix these problems in the future.

### Accomplishments that we're proud of
We think this extension accomplishes its goal – to make people laugh. We hope seeing headlines like "Protesters vow to fight Grumpy Yogurt Cup presidency" and "7 Reasons Motherly Dumpling Won The Presidential Election" give you a chuckle, no matter who you voted for. We wanted to turn this tension-filled time in American politics into something we can all find some humor in, and I think we succeeded.

### What we learned
Before this hackathon, I had never attempted to make my own Chrome extension, and I knew very little JavaScript. If nothing else, this project helped me get a better grasp on JSON, HTML, and JavaScript, and opened my eyes to possible features we could implement in the future, and even possible projects we could build at future hackathons.
