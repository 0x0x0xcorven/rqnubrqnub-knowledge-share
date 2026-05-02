# rqnubrqnub-knowledge-share
books, papers and references on technology, political economy, and everything in between. read more, depend less


# rqnubrqnub-knowledge-share

books, papers and references on technology, political economy, and everything in between. read more, depend less.

---

> *this list is opinionated. it reflects a specific worldview: that technology is never neutral, that infrastructure is political, and that understanding power requires reading across disciplines. start anywhere. follow the threads.*

---

## table of contents

- [Technology](#technology)
- [Geopolitics](#geopolitics)
- [Politics](#politics)
- [Economics & Political Economy](#economics--political-economy)

---

## Technology

### Systems & Infrastructure

**The Design of Everyday Things** — Donald Norman
Before you touch a compiler, understand how humans interact with systems. Norman's framework for affordances and feedback loops applies as much to kernel design as to doorknobs. Foundational.

**The Art of Unix Programming** — Eric S. Raymond
Not just about Unix. About a philosophy of software: do one thing well, compose, prefer text streams, write programs that talk to other programs. If you internalized this, half of modern enterprise software would make you physically ill — which is the correct reaction.

**Unix and Linux System Administration Handbook** — Evi Nemeth et al.
The brick. Read it cover to cover at least once. Reference it forever. The chapters on networking and storage alone are worth the full read. Nothing flashy, just depth.

**The Linux Programming Interface** — Michael Kerrisk
If you work on Linux and haven't read this, you're guessing. Kerrisk documents the entire Linux/POSIX API with precision and context. Syscalls, signals, processes, threads, IPC — all of it. Keep it close.

**Computer Systems: A Programmer's Perspective** — Bryant & O'Hallaron
The book that bridges the gap between high-level programming and what actually happens on the hardware. Cache behavior, memory layout, linking, exceptions. The kind of knowledge that makes you faster at debugging than people who've been coding twice as long.

**Operating Systems: Three Easy Pieces** — Remzi & Andrea Arpaci-Dusseau
Free online. No excuses. Virtualization, concurrency, persistence — explained with unusual clarity. The "crux of the problem" sections alone are worth it.

**Systems Performance** — Brendan Gregg
How to actually understand what a running system is doing. Gregg's methodology for performance analysis is rigorous and tool-agnostic. The chapter on USE (Utilization, Saturation, Errors) will change how you look at metrics.

**The Practice of System and Network Administration** — Limoncelli, Hogan & Chalup
Operational thinking. How to run things at scale, how to think about reliability, how to document, how to hand off. The human side of infrastructure.

---

### Security & Cryptography

**The Web Application Hacker's Handbook** — Stuttard & Pinto
Methodical. Goes through every major class of web vulnerability with clarity. Dated in places but the mental models hold. Read alongside modern OWASP documentation.

**Hacking: The Art of Exploitation** — Jon Erickson
One of the few security books that teaches you to think like an attacker from first principles. Assembly, shellcode, buffer overflows — explained from the ground up. Don't skip the programming sections.

**Applied Cryptography** — Bruce Schneier
The classic. Protocols, algorithms, implementation pitfalls. Schneier is direct about what breaks and why. Some sections are dated but the core reasoning about threat models remains essential.

**Cryptography Engineering** — Ferguson, Schneier & Kohno
The successor. More practical than Applied Cryptography, more focused on building real systems. The chapters on key management and protocol design are particularly sharp.

**The Tangled Web** — Michal Zalewski
A forensic examination of how browsers work and why the web security model is a patchwork of historical accidents. If you work in web security, this is required reading. If you don't, it'll make you deeply skeptical of the entire stack.

**Practical Malware Analysis** — Sikorski & Honig
Hands-on. Labs included. Covers static and dynamic analysis, unpacking, anti-analysis techniques. One of the best structured approaches to understanding what malware actually does and how to reverse it.

**The Art of Memory Forensics** — Ligh et al.
Memory analysis done properly. How to extract artifacts from RAM dumps across Windows, Linux, and Mac. The methodology chapters are applicable beyond forensics — they teach you how processes, handles, and kernel structures actually look in memory.

**Silence on the Wire** — Michal Zalewski
Passive traffic analysis and covert channels. A different kind of security book — less about attacks, more about what information leaks from systems that were never designed to be observed. Quiet and unsettling in the best way.

**Countdown to Zero Day** — Kim Zetter
The Stuxnet story. Reads like a thriller but is meticulously reported. The best accessible account of how a nation-state cyberweapon actually works and what its discovery revealed about the geopolitics of cyber conflict.

---

### Networks

**TCP/IP Illustrated, Volume 1** — W. Richard Stevens
There is no substitute. If you want to understand how the internet actually works, read Stevens. Every protocol dissected with packet traces. The chapter on TCP connection management alone is worth more than most networking courses.

**Computer Networks** — Andrew Tanenbaum
The textbook. Covers everything from physical layer to application layer with academic rigor. Pair it with Stevens for depth on the protocols you care about most.

**Interconnections** — Radia Perlman
Bridges, routers, and the protocols that hold networks together. Perlman invented spanning tree. She explains routing and bridging with more clarity than anyone else. Underrated.

**Network Warrior** — Gary Donahue
Practical. Cisco-focused but the concepts transfer. How real networks are actually built, configured, and maintained. The sections on routing protocols and QoS are particularly useful.

**The Internet Peering Playbook** — William B. Norton
How the actual physical internet is structured. Peering agreements, IXPs, transit providers, the economics of bandwidth. Essential context for understanding why the "global" internet has such a specific topology.

---

### Software & Programming

**Structure and Interpretation of Computer Programs** — Abelson & Sussman
SICP. The MIT classic. Not about a specific language — about computation itself. Teaches you to think in terms of abstraction, procedures, and data. Read it even if you never write a line of Scheme.

**The C Programming Language** — Kernighan & Ritchie
Short. Dense. Written by the people who built the language. Read it twice.

**Programming Rust** — Blandy & Orendorff
The best introduction to Rust's ownership model. Explains not just how but why — why the borrow checker exists, what problems it solves, what it costs. If ownership still feels arbitrary after reading this, read it again.

**The Pragmatic Programmer** — Hunt & Thomas
Practical wisdom about how to actually work as a developer. Not about a language or framework. About habits, thinking, and craft. More durable than most technical books.

**Clean Code** — Robert C. Martin
Controversial in places but the core message — that code is read far more than it's written — is correct. Read critically. Apply selectively.

**Compilers: Principles, Techniques, and Tools** — Aho, Lam, Sethi & Ullman
The Dragon Book. Not easy. But understanding how compilers work changes how you write code, how you debug, and how you think about language design. The chapters on lexing, parsing, and optimization are foundational.

---

### Surveillance, Privacy & Digital Rights

**No Place to Hide** — Glenn Greenwald
The Snowden documents, contextualized. What mass surveillance actually looks like at scale, what it costs, and why the "nothing to hide" argument is structurally wrong. Read alongside the primary source documents.

**Data and Goliath** — Bruce Schneier
The surveillance economy mapped out clearly. Who collects what, how it's used, what the risks are, and what might be done about it. Schneier is careful with claims. Trust his analysis.

**The Age of Surveillance Capitalism** — Shoshana Zuboff
Dense and long. Worth it. Zuboff names and analyzes the specific economic logic that turns human behavior into a commodity. The concept of "behavioral surplus" is one of the most useful analytical tools for understanding the tech economy.

**Permanent Record** — Edward Snowden
The personal account. How someone inside the surveillance apparatus came to understand what it was doing. Read it for the technical details of how the NSA's systems actually worked, not just the politics.

**Weapons of Math Destruction** — Cathy O'Neil
Algorithms that make consequential decisions about people — credit, employment, criminal justice — and how they encode and amplify existing inequalities. O'Neil is a mathematician writing for a general audience without losing rigor.

---

## Geopolitics

### Power & International Order

**The Grand Chessboard** — Zbigniew Brzezinski
Cold but clarifying. Brzezinski lays out the logic of American geostrategy with unusual honesty. Whatever you think of the prescription, the diagnosis of Eurasian geopolitics and the importance of controlling the "heartland" has aged remarkably well.

**The Tragedy of Great Power Politics** — John Mearsheimer
Offensive realism in full. States want security, security is never guaranteed, so states accumulate power without limit. Mearsheimer's framework predicts conflict wherever power vacuums exist. Read it alongside critics to understand the limits of structural realism.

**On China** — Henry Kissinger
Kissinger is not a neutral observer. But his account of Chinese strategic culture — the concept of *shi*, the long view, the preference for positioning over confrontation — is useful for anyone trying to understand how Beijing thinks. Read critically.

**The Silk Roads** — Peter Frankopan
A reorientation of world history around Central Asia and the trade routes that connected civilizations. Makes the Belt and Road Initiative feel less like a new idea and more like a return to historical patterns.

**Prisoners of Geography** — Tim Marshall
Geography as destiny. How mountains, rivers, and coastlines shape foreign policy. Accessible, sometimes oversimplified, but genuinely useful as a framework. The chapters on Russia and China are particularly relevant.

**The End of the World Is Just the Beginning** — Peter Zeihan
Deglobalization thesis. Zeihan argues that the US-underwritten global order is ending and maps what happens to supply chains, demographics, and food security when it does. Provocative. Some predictions are already aging poorly. Worth reading anyway.

**Destined for War** — Graham Allison
The Thucydides Trap applied to US-China relations. When a rising power threatens an established one, conflict is historically likely. Allison examines sixteen historical cases and asks whether this time can be different.

---

### Technology & Geopolitics

**Chip War** — Chris Miller
The best account of the semiconductor industry as geopolitical battleground. How Taiwan became indispensable, how the US built and then offshored its chip manufacturing capacity, and why export controls on chips are the new sanctions. Essential reading.

**The Code Breaker** — Walter Isaacson
CRISPR and the race to control biological technology. The geopolitical implications of biotechnology are underappreciated. Isaacson tells the story of a scientific revolution while raising questions about who owns the tools of life.

**LikeWar** — P.W. Singer & Emerson Brooking
Information warfare on social media. How the tools built for advertising became weapons for influence operations, how state and non-state actors use them, and what the new battlefield looks like. More relevant every year.

**The Hacked World Order** — Adam Segal
Cyber conflict as a feature of international relations, not a bug. Segal maps out how states use cyber capabilities for espionage, sabotage, and influence — and how the absence of agreed norms makes everything more dangerous.

**Stealth War** — Robert Spalding
Chinese strategic competition framed as unrestricted warfare. Biased in places but contains useful documentation of the mechanisms — technology transfer, investment, academic exchange — through which strategic advantage is accumulated below the threshold of armed conflict.

---

### Development & Dependency

**How Europe Underdeveloped Africa** — Walter Rodney
The structural argument for why colonial extraction produced permanent underdevelopment. Rodney documents the mechanisms — not just political subjugation but economic restructuring that made independent development impossible. Foundational for anyone thinking about development seriously.

**Confessions of an Economic Hit Man** — John Perkins
Memoir of someone who worked in the machinery of debt-trap development economics. Polemical and self-serving in places but the structural description of how multilateral loans create dependency is worth engaging with seriously.

**The Shock Doctrine** — Naomi Klein
Crisis as political opportunity. Klein documents how moments of social disruption — coups, disasters, financial crises — have been used to push through economic restructuring that would otherwise be politically impossible. Chicago School economics as a political project.

**Bad Samaritans** — Ha-Joon Chang
The most direct takedown of the "free trade" development consensus. Chang shows that every currently developed nation used industrial policy, tariffs, and state intervention to develop — and now kicks away the ladder. Essential for developmentalists.

---

## Politics

### Theory & Philosophy of Power

**The Prince** — Niccolò Machiavelli
Read it as a manual, not a scandal. Machiavelli describes power as it actually operates, not as it presents itself. The chapters on fortresses, allies, and advisors remain more relevant than most political science published in the last century.

**Leviathan** — Thomas Hobbes
The foundational argument for the state. Hobbes's description of the state of nature — "solitary, poor, nasty, brutish, and short" — is not just political theory, it's a threat model. Understanding why the state exists is prerequisite to critiquing it.

**The Social Contract** — Jean-Jacques Rousseau
The counterpoint to Hobbes. Legitimacy comes from the people, not from power alone. The "general will" concept is slippery but generative. Read alongside Hobbes to understand the tension at the center of modern political thought.

**On Liberty** — John Stuart Mill
The liberal argument for individual freedom against collective power. Mill's harm principle is deceptively simple. His chapters on freedom of thought and expression are as relevant to platform moderation debates as they were to Victorian censorship.

**The Origins of Totalitarianism** — Hannah Arendt
Arendt traces the ideological and institutional conditions that made Nazism and Stalinism possible. The analysis of how propaganda destroys the distinction between fact and opinion is uncomfortably current. Read slowly.

**Discipline and Punish** — Michel Foucault
Surveillance as a form of power. The Panopticon model — where the mere possibility of observation produces compliance — anticipates the surveillance economy by decades. Dense but the core argument is irreplaceable.

**The Anatomy of Fascism** — Robert Paxton
What fascism actually is, historically and structurally. Paxton refuses easy definitions and instead identifies fascism by its practices and emotional appeals. Useful for avoiding both over- and under-application of the term.

**Manufacturing Consent** — Chomsky & Herman
The propaganda model of media. How institutional pressures — ownership, advertising, sourcing — shape what gets reported and how. The methodology is more important than any individual case study. Learn to apply it independently.

---

### State, Technology & Control

**The Permanent Bureaucracy** — various
The deep state as a structural phenomenon rather than a conspiracy. How administrative institutions develop their own interests, cultures, and resistance to political direction. Essential for understanding why governments are hard to change from the inside.

**The Fifth Risk** — Michael Lewis
What governments actually do and what happens when the people running them don't understand their own machinery. Lewis focuses on the US but the analysis of technical expertise and institutional knowledge applies universally.

**How Democracies Die** — Levitsky & Ziblatt
Democratic erosion as a gradual process. Not coups but the slow weakening of norms, institutions, and checks. The historical comparisons are useful; the implicit argument that norms are load-bearing is important.

**The People vs. Democracy** — Yascha Mounk
The separation of liberalism from democracy — how illiberal democracies and undemocratic liberalism both emerged as stable configurations. More diagnostic than prescriptive, which is honest.

---

### Activism, Resistance & Civil Disobedience

**Civil Disobedience** — Henry David Thoreau
The original argument. Short. Read it as a philosophical foundation before engaging with any contemporary debate about protest, resistance, or the limits of legal obligation.

**Letter from Birmingham Jail** — Martin Luther King Jr.
Not a book but essential. King's argument for the moral obligation to resist unjust laws, and his critique of the "white moderate" who prefers order over justice, is one of the most precise political documents ever written.

**The Revolution Will Not Be Funded** — INCITE! Women of Color Against Violence (ed.)
A critique of the non-profit industrial complex and how institutional funding shapes and limits radical organizing. Uncomfortable reading for anyone who works in or adjacent to funded activism.

**Beautiful Trouble** — Andrew Boyd & Dave Oswald Mitchell (eds.)
Tactical and strategic handbook for creative activism. Less theoretical than the others — more of a toolkit. Useful for thinking about how narrative, spectacle, and action interact.

---

## Economics & Political Economy

### Development Economics

**The Wealth of Nations** — Adam Smith
Read the actual book, not the summary. Smith is more nuanced than his modern interpreters. His concerns about monopoly power, rent-seeking, and the interests of merchants against consumers are routinely ignored by people who invoke his name.

**Capital in the Twenty-First Century** — Thomas Piketty
The inequality thesis with the data behind it. r > g — return on capital exceeds economic growth — as the structural driver of wealth concentration. Disputed in methodology but the empirical work is serious and the framework is generative.

**The General Theory of Employment, Interest and Money** — John Maynard Keynes
Difficult but necessary. Keynes's argument that markets don't self-correct and that aggregate demand matters is the foundation of modern macroeconomics. The chapters on uncertainty and animal spirits are more interesting than the formal model.

**Development as Freedom** — Amartya Sen
Freedom not as a means to development but as its definition. Sen's capability approach reframes what development is for — not GDP but the actual ability of people to live the lives they have reason to value. Quietly radical.

**The Bottom Billion** — Paul Collier
Four traps that keep the poorest countries poor: conflict, natural resources, landlocked geography, and bad governance. Collier is a mainstream development economist but his diagnosis is honest about the limits of standard prescriptions.

**Kicking Away the Ladder** — Ha-Joon Chang
The historical argument that developed countries used industrial policy and protection to develop — then, once developed, promoted free trade as universal doctrine. Compact and well-documented. Chang at his most focused.

**The Entrepreneurial State** — Mariana Mazzucato
The state as risk-taker and innovator, not just regulator. Mazzucato documents how foundational technologies — the internet, GPS, touchscreens, most of what's in a smartphone — were developed with public funding. The implications for how we think about value creation are significant.

**Why Nations Fail** — Acemoglu & Robinson
Inclusive vs. extractive institutions as the determinant of development. The historical case studies are strong; the policy prescriptions are weaker. Read alongside Chang for a more complete picture.

**The Mystery of Capital** — Hernando de Soto
Why capitalism works in some places and not others. De Soto's answer — the absence of formal property rights that allow assets to become capital — is partial but important. The chapters on extra-legal property systems are genuinely illuminating.

---

### Political Economy & Capitalism

**Das Kapital** — Karl Marx
Volume I at minimum. Whatever your conclusions, Marx's analysis of commodity fetishism, surplus value, and the logic of accumulation is indispensable for understanding capitalism. The chapter on the working day is one of the greatest pieces of political economy ever written.

**The Communist Manifesto** — Marx & Engels
Short. Historical. The analysis of how capitalism dissolves traditional social structures and produces its own gravediggers is more interesting than the political prescription. Read it as a diagnosis, not a blueprint.

**Capitalism, Socialism and Democracy** — Joseph Schumpeter
Creative destruction. Schumpeter's argument that capitalism's dynamism is inseparable from its instability, and his prediction that capitalism would eventually undermine the conditions for its own reproduction, has aged well.

**The Great Transformation** — Karl Polanyi
The market economy as a historically specific and politically constructed institution, not a natural order. Polanyi's concept of the "double movement" — market expansion producing its own social counter-movement — is essential.

**Imperialism, the Highest Stage of Capitalism** — Lenin
Read as a historical and analytical document, not a political program. Lenin's argument that capitalism inevitably produces monopoly and then seeks foreign markets and investment opportunities explains a lot about 20th century history.

**Twenty-First Century Monetary Theory** — various (MMT literature)
Modern Monetary Theory as a framework for understanding sovereign currency issuers. Contentious but important for anyone thinking about development finance and the constraints on public investment. Start with Stephanie Kelton's *The Deficit Myth* for accessibility.

---

### Technology Economics & Platform Power

**The Master Switch** — Tim Wu
The cycle of open and closed in communication technologies. Radio, telephone, film, internet — each starts open, each gets consolidated, each becomes a tool of control. Wu's concept of the "Separations Principle" is the most coherent policy proposal to come out of this analysis.

**Platform Revolution** — Parker, Van Alstyne & Choudary
How platform businesses actually work — network effects, multi-sided markets, governance challenges. Useful for understanding the economics of companies that look like monopolies because they are.

**The Shallows** — Nicholas Carr
What the internet is doing to how we read, think, and remember. Carr's argument is grounded in neuroscience and is more careful than the genre usually produces. Whether or not you agree with the conclusion, the question is worth taking seriously.

**The Filter Bubble** — Eli Pariser
Personalization algorithms as political infrastructure. When everyone sees a different version of reality, the conditions for shared public discourse erode. Written in 2011 and more accurate every year.

**Chokepoint Capitalism** — Cory Doctorow & Rebecca Giblin
How dominant platforms use their position to extract value from creators and workers. The analysis of Amazon, Spotify, and publishing as chokepoint monopolies is sharp. The policy proposals are worth engaging with.

---

### History of Economic Thought

**The Worldly Philosophers** — Robert Heilbroner
The best introduction to the history of economic thought — Smith, Ricardo, Marx, Veblen, Keynes, and others — told as intellectual biography. Required context for understanding where economic ideas come from and what problems they were invented to solve.

**A History of Economic Thought** — Eric Roll
More academic than Heilbroner but more complete. Traces the development of economic theory from mercantilism to the 20th century. Useful as a reference as much as a read.

**Debunking Economics** — Steve Keen
A rigorous critique of neoclassical economics from within the discipline. Keen dismantles the foundations of mainstream micro and macro with technical precision. Not light reading but important for anyone who wants to understand the limits of the dominant framework.

---
