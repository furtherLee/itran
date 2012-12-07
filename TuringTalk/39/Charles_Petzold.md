iTuring: What have inspired you to write a book about Turing (the Annotated Turing)? Are there any stories behind the scene? Is there any connection between this book and your other works?

CP: When I was writing “Code” I became very interested in the early history of computing and the mathematical foundations of computing. I tried to read Alan Turing’s paper on computability, but I found it very difficult. At one point I thought “This paper is so important, somebody should write a book about it.” That’s a very dangerous thought! Who else will write this book if not me?

I decided I’d like to try to write a book about Turing’s paper as early in 1999, but I didn’t really get moving until 2004, when I scanned the paper and and printed it out, and I cut it up into separate paragraphs and sentences, and taped those pieces to pages of a yellow legal pad. I wrote a lot of the annotation text by hand on the pages of this pad, and the book took another four years to finish.

iTuring: Not only your technical books, also Coding and the Annotated Turing, they are all highly reviewed by readers, as an enthusiastic one, I’m curious about how you manage to construct these successful books? How do you digest huge volume of information into such a beautifully written book? Are there any critical decisions you have to make along the way?

CP: I spend a lot of time thinking about organization and order. What needs to comes first? What needs to come after that? This is never immediately obvious. Sometimes I’m working on a chapter, and I realize that I need an earlier chapter to provide a foundation for this chapter. This might cause a lot of upheaval in the existing chapters.

I can’t simply write a book starting with Chapter 1, and then Chapter 2, and then Chapter 3. Instead of growing from beginning to end, my books always seem to grow outward, and I need to skip around a lot. I also need to be thinking about the book all the time. I can’t spend a couple hours during the day working on the book, and the other hours doing something else. I need to live with the book.

iTuring: A preview of your upcoming book Programming Windows 6th shows that you used C# language and XAML in your book. Why not using C like in the 5th edition? And do you have any plan to write a book about .NET ?

CP: Windows 8 introduces a new programming interface for writing Windows Store applications, and you really can’t use C. You can use C++, but I thought that writing the book using C# rather than C++ would be clearer to both C# and C++ programmers. However, I am converting all the code samples form C# to C++. I’ve written several books on .NET – on Windows Forms, on the Windows Presentation Foundation, on WPF 3D, and on Windows Phone. I like .NET a lot, and I like C# and XAML, and I was very happy to see these programming interfaces and languages play a major role in Windows 8.

iTuring: You have started your career as programmer and writer in 1984, and a year later you focused on Windows. Knowing that Windows was not a very hot topic by then, we are very curious about your career choice, why Windows?

CP: When I first saw pre-release versions of Windows in 1985, I was curious how the applications worked. Obviously even simple Windows programs knew what size they were, because they changed their appearance based on the size of their window. How did that work exactly? What was the mechanism? Curiosity was a big part of my earlier interest in Windows. But I also had experience writing programs for DOS that stayed in memory while other programs were running. These were called Terminate and Stay Resident (TSR) programs, and they were very nasty to use and caused a lot of problems. I knew that these TSRs were not a long-term solution to multitasking on the PC. I knew that the operating system rather than individual applications needed to manage multitasking. I knew that the operating system had to manage the video display so it could be shared by multiple applications.

Windows seemed like a good solution to these problems.

iTuring: Big data, cloud computing, and mobile are among the hottest keywords today, now that Windows8 is released, what do you think are the biggest challenges for Windows? And what is your expectation for Windows’s future?

CP: I am not a good soothsayer, but we all use several different devices now – a phone, a tablet, a desktop machine. We want to share data among these computers, which means this data should probably exist in the cloud. But we also want most of our data to be private, which means that each of these computers must know who we are.

Eventually, we want to sit down at any computer, or pick up any computer, and be able to access our own private data. That’s one very big challenge.

But each of us is also several different identities within ourselves. We have an identity at work, we have an identity within our family, we have an identity among our friends, perhaps we have a multi-player game identity. We must be able to separate these identities. For example, when we write an email at work, we don’t want an address book full of our Facebook friends. But if we take a break from work for lunch, then we might want to interact with those friends and not the boss. I think this type of separation of ourselves into different identities is also a big challenge.

iTuring: Windows’s application development techniques are totally based on .NET, whose prototype is to transmit software through web page to remote server and then, implement. As web is becoming more and more popular, it seems that everything could be in the cloud, does it conflict with .NET’s original ideas? Is developing software this way somehow outdated? And what do you expect of the future of software development language?

CP: We don’t want everything in the cloud all the time. When we sit down to work on a spreadsheet, we don’t want to download Excel before we can work. And we probably don’t want Excel implemented on a web page in HTML5 and JavaScript. At the very least, applications and data should be cached on the local machine for fast startup.

But how is this different from an application store? An application store knows that we have purchased an application, so we can uninstall it from our local machine and re-download it whenever we want. The application is connected with our identity rather than specific hardware, but for performance purposes it makes more sense for the application to be installed on the hardware.

I am very much in favor of managed languages such as Java and C#. Managed languages make development faster because they help us avoid bugs, and managed languages let us run a single binary on many different processors. However, for some applications, we run into performance issues with managed languages. This tells us that it is not yet time to abandon languages that compile to native code, such as C++.

As long as performance is an issue, and as long as we care about performance, we cannot restrict ourselves to just one approach to writing applications and storing applications in the cloud.

iTuring: It is known to all that the Turing Machine plays a vital role in the field of Computer Science, and it is the foundation of Algorithm Analysis and Programming. Is there any possibility that nowadays the Turing Machine has become the bottleneck of the development of the Computer Science due to its design philosophy? Does it mean a negative answer for people to be able to develop real AI in the future?

CP: The Turing Machine was developed as a model for human beings carrying out algorithms. We don’t know if the Turing Machine is also a model for human thought in general. Much of our thinking seems to us not like algorithmic thinking at all, but that might be an illusion. Deep down inside, it’s possible that our minds are really Turing Machines.

If our minds are Turing Machines, then theoretically we can realize AI on digital computers, and it’s only a software problem. If our minds are not Turing Machines, then we need a different kind of computer for AI. The Turing Machine only describes the limitations of digital computers. It does not pertain to non-digital computers. The hard part is conceiving and designing a computer that does not have the limitations of a Turing Machine because it is not a digital computer.

iTuring: Natural intelligence and artificial intelligence are supposed to generate sequenced message from chaotic model, from this perspective, is algorithm posing some kind of restriction upon computer scientists? Is it possible another computational model other than Turing machine is better at generating artificial intelligence?

CP: If we encounter a computer that passes the Turing Test, many of us will simply deny that this computer has true intelligence. As computer scientists and programmers, we know that no matter how smart it might be, and how human it might act, this computer simply does not have consciousness. It is not self aware. It can crunch numbers, and it can mimic us externally, but it can’t think like us.

The Turing Test is supposed to be strictly behaviorist. What happens inside the computer is not supposed to be an issue. But this is not satisfactory. But what’s worse is this: We deny that computers think like us but we don’t know how we ourselves think! We don’t understand our own consciousness.

I think that the most accurate theories of the mind are probably those that describe consciousness as the communication between loosely coupled areas of the brain and the rest of the nervous system. But it’s a very mysterious process. We don’t know how it works, so we don’t know what kind of hardware or software we need to create consciousness.

We don’t even know how we would judge success in creating a computer with consciousness. If a computer told us that it was self aware and had consciousness, would we believe it?

iTuring: Any book about computational theories would introduce NP-complete problems, and it seems that computer science is restrained into the field of deterministic algorithm. As it seems that innovative study like non-deterministic algorithm and algorithm exploration are less favored in the academic field and in the industry, what’s your opinion about it?

CP: This is an area I don’t know much about, but a lot of thinking about non-deterministic Turing Machines is extremely theoretical at this time. Of course there’s a resistance to doing a lot of research about computers that we can’t actually play with. This whole field will certainly become more important as quantum computers become more real.

iTuring: Turing Machine, λ Calculus, μ-Recursive Function and URM (Unlimited Register Machine) are four equivalent computational models. Why has Turing Machine become the best known one in non-academic areas?

CP: First reason: The Turing Machine has a name rather than a Greek letter. Second reason: The Turing Machine can be visualized as an actual piece of hardware with a tape. The Turing Machine has a name and a face.

iTuring: How do you see Turing’s contribution to computer science comparing to Von Neumann? And after processing so much information about Turing, how do you see Turing as a person?

CP: Alan Turing was a classic introvert, and John von Neumann was a classic extravert. I think their contributions to computer science were very much in keeping with their personalities. Turing could focus on difficult problems, and he could think in very original and ingenious ways, but I don’t think he was much of an organizer. Von Neumann had a very strong personality. He could synthesize ideas coming from many different sources and people, and put them together. It is very clear to me that Turing’s paper on computability helped clarify von Neumann’s thinking about the nature of digital computing, but it was von Neumann who was more effective in bringing these ideas into the real world.

I don’t think I would have liked von Neumann as a person. But after spending so much time with Alan Turing’s writings and legacies, I had a real affection for him. It is sad that he was treated so terribly.

