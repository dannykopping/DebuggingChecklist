## Web Debugging Checklist

  1. **Blame yourself.**
    * In debugging, having an ego will only cause you to work longer and harder to solve a bug. Be humble; accept your humanity. Make 100% sure that the way you're attacking a problem is _actually_ isolating the problem.
    * Are you able to reproduce the problem every single time you try? People use testing frameworks to not only replicate bugs, but to make sure the bug actually goes away
  2. **Blame your framework.**
    * Are you working with a framework or library of some kind?
    * Are you sure it's not manipulating the results or getting in your way?
  3. **Blame your tools.**
    * Have you got cache enabled? Are you working in IE6? Try to ensure that your tools aren't giving you false-positives or false-negatives. Use an HTTP proxy like [Charles Proxy](http://www.charlesproxy.com/) to debug HTTP requests.
  4. **Blame your environment.**
    * Is your server configured the way you need it to be?
    * Are you running the correct version of the software you need?
    * Could another piece of software be getting in the way?
    * Be sure to disable any caching technologies to ensure you're always looking at the most recent data, and that your _actual_ code is executing every time (not some cached version).
    * Have you tried turning it off & on again? =)
  5. **Blame your language.**
    * Is the code you're debugging very complex or novel? Maybe it's a bug in your language (highly unlikely)
    * Always break the problem down into as small a piece as you can - it's probably you
  6. **Blame the world.**
    * Have you tried logging a bug?
    * Have you tried asking a question on [Stack Overflow](http://stackoverflow.com)?
    * Have you asked a friend? Sometimes speaking the problem out loud can give you insight into the problem at hand.

---

## General Considerations ##

* **ALWAYS** check your premises. Assuming makes you an ass.
* **ALWAYS** make sure your problematic code is actually being executed.
* **ALWAYS** be patient. Getting hot-headed, murdering prostitutes and swearing at co-workers won't solve the problem.
* **ALWAYS** remember that you're human, the code you're writing was written by a human, the language with its frameworks, servers & environments were all written by humans. Shit happens - be humble.
* **ALWAYS**, share your experiences so that other poor souls can solve their problems quicker with your help. You may be a snowflake, but your code problems probably aren't.
