# Jeff-Atwood-Effective-Programming-Takeaways
My takeaways from Jeff Atwood's blog to book '[Effective Programming](https://www.amazon.com.au/Effective-Programming-More-Than-Writing-ebook/dp/B008HUMTO0)'.

1. The value of effective communication. The difference between a tolerable programmer and a great programmer is not how many programming languages they know, and it's not whether they prefer Python or Java. It's whether they can communicate their ideas. By persuading other people, they get leverage. By writing clear comments and technical specs, they let other programmers understand their code, which means other programmers can use and work with their code instead of rewriting it. Absent this, the code is worthless. Exercising this skill through blogging and writing is a good way to improve. 

2. The Multi-Tasking Myth. Task switches, particularly in programming, take a really, really, long time. 

3. Always assume the problem bug is your fault. Whatever the problem with your software is, take ownership. A pair of studies [in 1973 and 1984] found that, of total errors reported, roughly 95% are caused by programmers, 2% by systems software (the compiler and the operating system), 2% by some other software, and 1% by the hardware.

4. The value of code brevity. Every new line of code you willingly bring into the world is code that has to be debugged, code that has to be read and understood, code that has to be supported. Clearly and concisely write only that which is required. Eliminate any unnecessary lines and don't be verbose.

5. Finding a practical ground with code comments. Compromise between the two polar extremes of no comments whatsoever and carefully formatted epic poems every second line of code. This ties in with point 1. You should always write your code as if comments didn't exist. This forces you to write your code in the simplest, plainest, most self-documenting way you can humanly come up with. Then by all means, add comments... carefully. 

6. Learn to read the source. Everyone's software becomes my software because all of their bugs are my bugs.

7. Success is rarely determined by the quality of your ideas, but it is frequently determined by the quality of your execution. In software development, execution is staying on top of all the tiny details that make up your app. If you're not constantly obsessing over every aspect of your application, relentlessly polishing every little part of it - no matter how trivial - you're not executing. At least, not well.

8. It's been shown time and time again that there is no correlation between years of experience and skill in programming. After about 6 or 12 months working in any particular technology stack, you either get it or you don't. I'm not saying experience doesn't matter in software development. It does. But consider the entire range of a developer's experience, and realise that time invested does not automatically equal skill. Otherwise, you may be rejecting superb software engineers simply because they lack "(n) years of experience" in your narrow little technological niche - and that's a damn shame.

9. When your code is reviewed by another human being - whether that person is sitting right next to you (peer programming), or thousands of miles away - you will produce better software.

10. We have meetings because we think we need them, but all too often, meetings are where work ends up going to die. Meetings should be under an hour, have a clearly defined purpose and be optional...

11. The programmers bill of rights: at least two monitors, a fast PC, their choice of mouse and keyboard, a comfortable chair, a fast internet connection, quiet working conditions.

12. Microsoft's [healthy computing guide](https://support.microsoft.com/en-us/help/4101085/accessories-setting-up-your-desktop) is an effective and succinct reference.

13. When you're working on end-user software, and it doesn't matter if you're working on a web app, adding a feature to an existing application, or working on a plug-in for some other application, you need to design the UI first. To the end user, the interface is the application. Stay out of technical development environments when mocking your user interface. See [Paper Prototyping: The Fast and Easy Way to Design and Refine User Interfaces](https://www.amazon.com.au/Paper-Prototyping-Interfaces-Interactive-Technologies-ebook/dp/B006M86382).

14. Keep your unit testing and code coverage in perspective - the ultimate unit test is whether users want to use your application. All of the other tests you write are totally irrelevant until you can get that one to pass.

15. Even if version 1 sucks, ship it anyway. Instead of spending three months fixing up this version in a sterile, isolated lab, you could be spending that same three month period listening to feedback from real live, honest-to-god, annoyingly dedicated users of your software. Now, i'm not saying that you should release crap. What's important isn't so much the initial state of the software, but what you do after releasing the software.

16. Peer code reviews are the single biggest thing you can do to improve your code.

17. I pity the fool who doesn't write unit tests. Whenever you are tempted to type something into a print statement or a debugger expression, write it as a test instead. That small change in mindset could lead to bigger shifts like test-first development. However, automated test suites are a poor substitute for real-world beta testing by actual beta testers. Users are erratic. Users have weird software installed on their PCs. The real and best testing occurs when you ship your software to beta testers.

18. The most common way to get usability wrong is to listen to what users say rather than actually watching what they do. Acting on user feedback alone is questionable.

19. If it looks corporate, change it.
