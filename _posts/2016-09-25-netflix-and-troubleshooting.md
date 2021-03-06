---
layout: post
title: Of Penguins and Marxmanship	
tags: [netflix, news, entertainment, brazil, são paulo, books, apache server,virtual host, bootstrap, arch linux, philosophy]
---

```
<VirtualHost *:80>
    ServerAdmin webmaster@gringolalia.com
    DocumentRoot "/srv/http/gringolalia.com"
    ServerName gringolalia
    ServerAlias www.gringolalia.com
    ErrorLog "/var/log/httpd/domain1.com-error_log"
    CustomLog "/var/log/httpd/domain1.com-access_log" common
</VirtualHost>
```

The style used for `<code>` blocks is in need of some adjustment, but if you can make this out, you will see it is an Apache virtual host configuration file. 

This should be easy to set up and I should have learned this long ago, but I am having difficulties. 

The [troubleshooter](https://wiki.apache.org/httpd/TroubleshootingVhosts) says I should not need to declare the following unless my Apache is younger than v2.3.11.

```
NameVirtualHost 192.168.0.1:80
```

My version is 2.4.7. 

Oh, but `sudo bonk self on forehead`! I just forget to change the `ErrorLog` line to match `gringolalia.com`. I wonder sometimes if I am detail-oriented enough for this line of work.

That fixed things.

#### On the Sabbath the Infernal Machine Rested

![The infernal machine inspects sambodian source code](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/categoriessambodiascaled.png)

But forgive me. [I promised I would not blog about the infernal machine on the Sabbath](http://bretonio.gitlab.io/echolalia/post/dropdown/). 

![index.html of a Bootstrap exercise](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/bootcampscaled.png)

On the seventh day, the gringo stopped hacking Bootstrap -- above --and rested. More or less.

So here I am, [starting a new post in Jekyll](https://jekyllrb.com/docs/posts/) in what I have now officially designated as my Sunday life in general blog. 

My [Holiday in Sambodia](https://en.wikipedia.org/wiki/Holiday_in_Cambodia) blog, writing about things that Frazer and Diana and the Crocker clan in general along with my [millions of Facebook followers](https://www.facebook.com/braytonio) might like to read about. Like a weekly Xmas letter. Inform all and sundry of latest developments if any. 

I could write about things I witnessed, say, on the 7:00 a.m. Route 6232 bus that roars up the Avenida Teodoro Sampaio to the Hospital das Clínicas with a violent rattle hum and jolt every second or so. It is my new daily grind. SUS is subsidizing a Bilhete Único transit pass for me even tho I am an Auslander. 

Who I mostly rub elbows with are domestic workers busing two hours or more from the favelas of the *periferia* to work in homes of São Paulo [dondocas](http://www.wordreference.com/pten/dondoca). 

What is this place? Freaking Johannesburg?

As to the uneven ride, well, São Paulo is not the best paved megalopolis in the world. Our street, for example, is still paved with *paralelepípedos*. 19th-Century cobblestones. They say there were cattle drives in the neighborhood well into the 1960s. **Cattle drives**. 

And do not get me started on the sidewalks of Sambodia. It seems every property owner is responsible for his own and the result is a rapid race to the bottom. The Sambodians seem to believe that public easements paid for with tax money are a Communist plot.

But what else? 

I could also write about things I witnessed on Neuzona's laptop when tuned to YouTube or Netflix. 

I am, by the way, to inherit that laptop soon and I [have a radical Manchurian Candidate treatment in mind for it](http://bretonio.gitlab.io/gringolalia/2016/09/17/malabarismo/). 

I mean really: Windows Vista? Prep for surgery, a brain transplant is on the way. I should not need more than half an hour injecting Antergos or Apricity OS or Manjaro from a pen drive.

Or maybe I could write about books I am reading or trying to read. 

Or maybe I could write on the "Brazil Love It or Leave It" anthem commissioned by the `generalíssimos` of the 1960s and 1970s, the one the nuns made Neuza sing every day as a child. Neuza loves to show me things on You Tube. Like Miss Piggy videos. This is really cute.

Or write about something written by [Lygia Fagundes Telles](https://en.wikipedia.org/wiki/Lygia_Fagundes_Telles) as borrowed from the [Cancer Ward](https://en.wikipedia.org/wiki/Cancer_Ward) library -- a novella alternately narrated by a fifty-something fading actress and her cat. Overtones of Samuel Beckett, I find.

Or perhaps my topic for the day is what Neuzona and I refer to as the  "[terrorists](https://en.wikipedia.org/wiki/The_Americans_(2013_TV_series) and [spies](https://en.wikipedia.org/wiki/The_Americans_(2013_TV_series)" time of day. This is when we break off work at 6:00 p.m or 7:00 p.m. to eat dinner and tune in Netflix -- which is steadily robbing us of our Brazilian cultural identity, we fear.

(What is television without the *novela das nove* and William Bonner -- he pronounces it *boner*, ha ha -- anchoring the `Jornal Nacional'? The Sunday infotainment spectacular *Fantástico* is where most Brazilians seem to get their news.)

Yesterday, for example, we were shocked! shocked! to see [Dar Adal](http://homeland.wikia.com/wiki/Dar_Adal) riding in the same Islamabad motorcade as the cruel al-Haqqani! 

Many people work very hard building blogs and wikis and Wikipedia pages about this sort of thing.

Or perhaps I could write on [Capitalism & Schizophrenia](https://en.wikipedia.org/wiki/Capitalism_and_Schizophrenia) -- I have been thumbing through it during one-hour down times and lunch times at the Cancer Ward -- about which there is very little wiki action at all. (A [Portuguese edition of A Thousand Plateaux](http://escolanomade.org/wp-content/downloads/deleuze-guattari-mil-platos-vol1.pdf) is downloadable for free.)

Do not ask me why it is I subject myself to the tortuous -- tortious? -- prose of this notoriously difficult work by Deleuze & Guatarri some twenty years after being assigned it by [Avital Ronell](https://en.wikipedia.org/wiki/Avital_Ronell) at Berkeley. For our first-year theory seminar. 

It was Avital who brought Derrida to Berserkeley that year on the visit that began the unlikely friendship between Derrida and Jurgen Habermas, who joined forces to oppose the 2003 Iraq invasion and jointly authored [Philosophy in a Time of Terror](https://www.researchgate.net/publication/249724812_Book_Review_Philosophy_in_a_Time_of_Terror_Dialogues_with_Jurgen_Habermas_and_Jacques_Derrida). 

You can [read about it in Wikipedia](https://en.wikipedia.org/wiki/Jacques_Derrida). And I was there! This dates me.

But what about the following astonishing proposition?

>Capitalism produce schizophrenics the same way it produces Ford motor cars and Maytag refrigerators.

Remind me to re-style the `<blockquote>` element on this template, by the way.

So why then? I never discard a book and still have volumes purchased for classes in the old Pomona College days. But when I decide to re-read a little philosophy after all these years, David Hume is more my bag, or Kierkegaard, or Wittgenstein: 

>That whereof we cannot speak meaningfully we must pass over in silence.

I have taken this proverb as license to ignore everything ever written by Martin Heidegger without feeling guiltily that I should. 

[Speech Acts](https://en.wikipedia.org/wiki/Speech_act) or [How To Do Things With Words](https://en.wikipedia.org/wiki/J._L._Austin) are more my style. Create a simple but profound analytic tool. Publish it on GitHub and let people apply it to their own projects. Such as [The Scandal of the Speaking Body](https://books.google.com.br/books?id=K7G3zKn-2QsC&pg=PA113&lpg=PA113&dq=shoshana+felman+le+scandale+du+corps+parlant&source=bl&ots=Vs4cvVP3H5&sig=3QuOCW1nKcyKtoIZApQH347X6go&hl=en&sa=X&ved=0ahUKEwiQtrHflKvPAhVKE5AKHeltArcQ6AEINDAD#v=onepage&q=shoshana%20felman%20le%20scandale%20du%20corps%20parlant&f=false).

#### Honing My Marxmanship?

The thing is that after all these years I still have yet to read all my Marx and Engels. They are available [in Portuguese on line](https://www.marxists.org/portugues/marx/) so I could justify my reading as a language training exercise.

I have read [Nick Dyer-Witheford](https://viewpointmag.com/2015/09/08/cyber-proletariat-an-interview-with-nick-dyer-witheford/) of [Cybermarx fame](http://eprints.rclis.org/6252/3/Chapter2.pdf) and a fair bit of Gramsci but not the original bearded prophet of the apocalypse -- Greek, as you know, for revolution, or "overturning".

[Cybermarx](http://eprints.rclis.org/6252/7/Chapter6.pdf), at least, might answer some of my questions about those so-called desiring-machines and their desiring-production in Deleuze. 

Do not pay for that book, by the way. It is [freely downloadable]().

In any case -- if I do not give up first -- I am hoping [my young philosopher friend](http://www.luizfernandofontesteixeira.com.br/) can help me wade through all this, or point the way to a coherent reading program, or at least teach me why according to Lacan the unconscious is structured **like** a language. 

I mean, why not **as** a language? With communicative functions? And does this mean that **language** is structured **like** the unconscious? Is this why everything bad in English -- the English used by rappers, anyway -- is a motherfucker?

I asked LF the other day the question I always asked freshman students of Plato -- why does everyone agree with everything Socrates said -- and he said the question was a highly dangerous one for the profession of psychiatry.

#### Chewing Gum For the Mind

```
npm root
/home/bretonio/node_modules/
npm root -g
/usr/local/lib/node_modules

npm config set prefix /usr/local
```

Will that solve my problem with [NPM](https://www.npmjs.com/)? 

The idea of trying it makes me nervous.

But I said enough of that. 

Someone is giving a show in the park nearby and singing George Harrison in a very bad accent. 

Shortly we will release our hounds onto the Internet of dogs so they can download and upload their olfactory e-mails. I have become the designated pooper scooper lately. How did I get talked into that? 

What is needed here is some chewing gum for the mind, as Diana likes to call the fantasy novels stacked up by her bedside. 

When Neuza is out in the evening I will sometimes select a sci-fi title, the sort of thing she is highly prejudiced against. 

I sometimes run into trouble -- "a session is open on another device" -- on account of Big Neuza my mother-in-law, who plugs into our Netflix feed and sometimes gets carried away with watching *That 70s Show*. 

It is creepy the way Netflix knows what you are doing and watching and pausing and running.

Other than all that, it is pretty much all infernal machine all the time. I have an ambitious [project to carry out](http://sambodia-docs.surge.sh/) and only six months to do it in.

#### Max Weber Foreber

Neuza says that my compulsion to use all my free time in what I insiste is a profitable manner is a [product of my Protestant upbringing](https://en.wikipedia.org/wiki/Protestant_work_ethic) -- everybody knows this theory and applies it to Americans here. But I tend to agree. 

The red-headed Myra Duncan Brayton of Missouri, b. 1908, was a powerful influence along these lines. If you want to go to band camp then you have to sell the peanut brittle door-to-door! 

And my grandather as well, Lieutenant-Colonel Paul Richard Brayton. His constant greeting: "Hey, there, Tiger! How are you getting along with your work?"

As though everything you did was part of your work. For a farm boy, dawn to dusk his whole life long, this was probably true. And remember: these were survivors of the Great Depression we are talking about. 

But then there was also a strong current of [Buddhist fascism](https://en.wikipedia.org/wiki/Soka_Gakkai) involved in my upbringing, if you can your head around the paradox of that. I really hate discussing this even after all this time. Chalk it up to the 1960s. 

And finally there were the Anglican influences. I liked the hymnal and the fact that the big book did not try to hide the [Apocrypha](https://en.wikipedia.org/wiki/Apocrypha) from us. But I have not sought out the [Brazilian communion](https://en.wikipedia.org/wiki/Anglican_Episcopal_Church_of_Brazil) since I have been here. (Truth is I bowed out in the late 1990s.)

But as to chewing gum for the mind? The thing is that there is very little in the way of Brazilian science fiction or pulp fiction in general, and the price of books here as I always complain is absurd. Usurious! 

![Penguin Brasil](https://raw.githubusercontent.com/bretonio/bretonio.github.io/master/images/penguincia.gif)

Calculating in terms of minimum salary and the basic shopping basket, only the so-called Sambodian elites can afford to read books, and the numbers suggest they are not that fond of doing so. 

These are people who would rather be reading New Age self-help books and [Veja magazine](https://sites.google.com/site/luisnassif02/) -- an information warfare asset operating on the model of the journalism of [moral panic](https://en.wikipedia.org/wiki/Moral_panic).

Not even [the partnership between Cia. das Letras and Penguin Classics](http://www.companhiadasletras.com.br/destaques/penguin.php) -- the first title published was *O Príncipe* (Machiavelli)-- has made a difference in this dynamic. 

In the Conjunto Nacional on the Avenida Paulista there is a shop front dedicated to the Penguin Clásicos but the prices are not exactly in line with the noble Penguin tradition of literature of the highest quality designed to fit in the overalls of the riveter or man behind a plow. 

[For sixpence](https://en.wikipedia.org/wiki/Penguin_Books). 

The only recognizable feature of the Brazilian editioins are the format, the orange and white branding, and the mascot. 

The Sambodians are all about branding. 

They will line up for steaks flown in from Australia or coffee imported from Seattle just to be able to be seen consuming the brand: Outback, say, or the most visible case of coals to Newcastle, which is Starbucks. 

(One reads that Starbucks expansion is stagnant and maybe even negative growth.)

In Brazil, the term *propaganda* has no negative connotations and the term *public relations* coined by Bernays to replace it is little used. Consider the ESPM -- [Escola Superior de Propaganda e Marketing](http://revistadaespm.espm.br/).  

### Unscientific Postscript

But blogging has now expanded to fill the time alotted.

*O Brasil, ame-o ou deixe-o*. 

Brazil. Love it or leave it. 

I guess I might well *deixar* it if I could bring Neuza along and I had two months rent in my pocket. But this is not the cards any time soon. 

In the meantime I exist in the cloud, with a`git push` here and a `git clone` there. I will post this link to Facebook and you can read at your leisure. 

2,203 words according to [ghostwriter](https://github.com/wereturtle/ghostwriter). Where is that subroutine that estimates []how much reading time a post will require](https://github.com/michael-lynch/reading-time)?