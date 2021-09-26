# Bryan's User Page
Hi there! I'm a 4th year Math-CS major at the **University of California San Diego**. I'm mainly interested in ~~algebra~~ ***group theory, cryptography, numerical analysis, and music***.

Here is a link to go to the site's [README.md](README.md). It should contain a link to go back to the site.

## Table of Contents
1. [Cryptography](#cryptography)
2. [Other Interests](#other-interests)
3. [Music](#music)
   1. [More Standard Music](#more-standard-music)
4. [Tasks](#tasks)

### Cryptography
For those interested more into cryptography, there is this really good *generalized* list on [Github](https://github.com/sobolevn/awesome-cryptography). Otherwise, I suggest that you take a look into some basic group theory take a specific look at the [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem)) system for those who are mathematically inclined to get your feet wet. I heavilly recommend starting with **modular arithmetic _then_ Fermat's Little Theorem**. After that, I recommend learning about **Euler's Totient Function**, at which point you should have an idea on how RSA works computationally. If you want to know more about why it works, I suggest consulting an abstract algebra textbook such as *Algebra* by Michael Artin and looking specifically into Groups of finite order *p* where *p* is a prime while also crossreferencing the wikipedia page.

### Other Interests
Some of you who are reading this page may know this snippet of code that often comes up as an introduction in algorithm design classes.

```c++
unsigned long fibIterative(unsigned long n) {
  if (n == 0) {
    return 0;
  }

  unsigned long fn2 = 1;
  unsigned long fn1 = 1;
  unsigned long fn = 0;

  for (unsigned long i = 3; i <= n; i++) {
    fn = fn1 + fn2;
    fn2 = fn1;
    fn1 = fn;
  }

  return fn1;
}
```
Optimizations on well known algorithms like these are my favorite type of things to look at and compare to what is usually the initial and intuitive design of an algorithm.

### Music
In terms of music, I quite literally listen to anything. Though I do have a tendency to listen to music that uses synthesizers even though I am classically trained. Plus you never know when you might hear something super cool that you would've never heard if you stuck to a genre. In particular, I really like to recreate sounds through the use of generated waveforms to get as close as possible to the original sound without actually using the original sample. This gives it a "8-bit" or retroish feel and when compared to the original we can still pick out which instrument it is which I find to be really interesting.

Here is a comparison of a (in my opinion) rather great track from the popular MMORPG Final Fantasy 14
- [Original](https://www.youtube.com/watch?v=GTlbyBg3PeI)
- [Chiptune version](https://youtu.be/uKeYe8L60Mo)

While not truly 8-bit, it is a great recreation of the intent and feel of the original.

#### More Standard Music
Otherwise, here are a list of recommendations of some of my more favorite traditional pieces.
- [Rachmaninov - The Isle of the Dead; Op 29 (Classical)](https://youtu.be/dbbtmskCRUY)
- [2 8 1 4 - Shinjuku Golden Street (Vaporwave)](https://www.youtube.com/watch?v=fgDvrTmF-Fo)
- [The Midnight - The Equaliser (Retrowave)](https://www.youtube.com/watch?v=YP5oIrV0ONk)
- [Audien and Echosmith - Favorite Sound (Indie Rock)](https://www.youtube.com/watch?v=ORA0kWZ7DnA)

### Memes
Before you go, take this meme. It is dangerous to go alone.
![Meme](https://github.com/bdnguyenucsd/cse-110-lab-1/tree/add-gitignore/images/security.png)

> Credit to Randall Munroe, the creator of xkcd comics. Original can be found [here](https://xkcd.com/538/).

### Tasks
- [x] Finish Lab 1.
- [ ] Get through the quarter.
