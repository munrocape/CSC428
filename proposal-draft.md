#A- HCI Project Proposal and Preliminary Literature Review
###Total: 5%
###Due Date: October 7th, 2015, 11:59pm

```

# Please add your name, email
Group 7
Kyra Assaad, kyra.assaad@mail.utoronto.ca
Zach Munro-Cape, zach.munro.cape@mail.utoronto.ca
Ajit Pawar, ajit.pawar@mail.utoronto.ca
Ishan Thukral, ishan.thukral@mail.utoronto.ca
Colin White, colin.white@mail.utoronto.ca

```

###PART 1: Topic Description (50/100 pts)

```
Write a proposal describing a HCI research topic that your team will address for the class project
Include a justification explaining why you think your project is an interesting HCI research topic.
Your topic description is met to be a high level description (in simple and clear text) that
introduces the instructor and the TA to your research project. Your topic description is very
important because it formalizes what your team is trying to do.
---
Rubric: Topic is well-described. Justification explaining why this is an interesting HCI 
research topic is provided and relevant.

```

As smartphone technology has evolved, multitasking is now supported on many mobile devices. This allows users to have many applications (apps) running at once and switch between them to save start up time and save state in a given app. Unlike PCs, screen real estate is much smaller on smartphones, meaning (for most devices) only one app can be in the foreground. The ability to have one app open and save state while launching another app is becoming increasingly important for users to utilize their devices efficiently.
The mechanism by which users swap active apps can vary wildly between devices. Sorted lists of applications, search methods, or gestures are common interactions to switch apps on smartphones.

Furthermore, having multiple apps open at once is now commonplace and encoraged by device manufacturers and app developers. For example, you may draft an email, then launch a photo editor, and then insert this edited photo into the email draft. Facebook, a company who previously had only one app, has split its flagship app into apps that correspond to functional components and encouragse users to seamlessly switch between them.

This paper aims to measure the effectiveness, efficiency, and accuracy of multiple methods for a user to switch to an already open app, open a new instance of an app, or close an app down.

###PART 2: Initial Literature Review (50/100 pts)

```
The purpose of this part is to do an initial literature review for your project that will help you
understand better the context of your research topic and the theoretical and contextual issues that
constrain and influence your project. Your literature review should be on your specific research
topic at least four (4) published papers (from journals or conferences) that are relevant to your
HCI research project. Note that this is a preliminary literature review. Your team will be able to
change and add references in the final version of the paper (the final version of the paper will
have to include at least six (6) published papers).
The literature review must written in full sentences (no bullet points). Organize your literature
review such that the current state of the art is reviewed, followed by the identification of your
research topic. The review should be between 500 - 750 words. All cited papers must be listed in
a reference section at the end of your literature review and follow the CHI reference style (see
CHI template).

Rubric: Literature review specific to the research topic and includes least four (4) published 
papers. Literature review is written in full sentences. Current state of the art is reviewed.

```
####Literature Review
The research on application switchers in smartphones is quite sparse. However, there has been research conducted on the costs of interruption when application switching to a user's workflow, as well as designing more efficient application switching interfaces for web and desktops. The results of this research help inform the design of this study.

Warr and Chi [5] explored whether a “cards”-based mobile webpage switcher such as Google Chrome, which stacks open webpages like cards in the display, would result in faster webpage switching and less errors than a “pages”-based switcher such as Safari, where the webpages are displayed as pages laid out next to each other. The research revealed that it is faster to switch webpages in the “cards”-based interface compared to the “pages”-based interface [5]. This research was conducted in early 2013 with the Safari interface from iOS 6. As of October 2015, the most recent Safari interface is from iOS 9, which has since done away with the “pages”-based switcher and now implements a “cards”-based switcher. In iOS 8, Safari used a “cards”-based switcher for webpages, but the interface for switching between apps was still a “pages”-based switcher. In iOS 9, the application switcher has been updated to be a “cards”-based switcher as well. This study will be testing the application switchers of iOS 8, iOS 9, and Android for speed and error rate. 

In "Multitasking and interruptions during mobile web tasks" [6], Nagata examined the impact of distractions - like answering a text message while purchasing an item form the internet - on performance of the original task (purchasing an item) as well as the performance of the user dealing with the secondary task, the text message compared to if the user was only answering a text message. They compared performance - total time taken, accuracy of completing a given task, as well as transition time - of users completing tasks and managing secondary tasks on Desktop versus Mobile devices. One of the take-aways from this was the impact of scrolling on the mobile device on distraction time. While this device was from 2001, and their have been marked improvements in handheld devices, delayed transition time on the mobile and desktop workflows impacted performance.

In "A multiple, virtual-workspace interface to support user task switching" [1], Henderson and Card observed that users interacting with an interface often organize tasks along a number of different dimensions, the most important of them being "locality" of tasks. The study found that users often form clusters of windows (applications) corresponding to a specific task. This insight led to development of interfaces that produce "virtual views" that allow users to focus their interactions within semantically meaningful cluster of windows. Today, many window management strategies borrow inspiration from this study, namely Apple's exposé feature (Mac OS X) and information awareness widgets such as Apple's Dashboard.

####References
1. Stuart K. Card and Austin Henderson, Jr.. 1986. A multiple, virtual-workspace interface to support user task switching. In *Proceedings of the SIGCHI/GI Conference on Human Factors in Computing Systems and Graphics Interface* (CHI '87), John M. Carroll and Peter P. Tanner (Eds.). ACM, New York, NY, USA, 53-59. DOI=10.1145/29933.30860 http://doi.acm.org.myaccess.library.utoronto.ca/10.1145/29933.30860
2. Gerard Kim and Hyeong Cheol Kim. 2011. Designing of multimodal feedback for enhanced multitasking performance. In *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems* (CHI '11). ACM, New York, NY, USA, 3113-3122. DOI=10.1145/1978942.1979403 http://doi.acm.org.myaccess.library.utoronto.ca/10.1145/1978942.1979403
3. Luis A. Leiva. 2011. MouseHints: easing task switching in parallel browsing. In *CHI '11 Extended Abstracts on Human Factors in Computing Systems* (CHI EA '11). ACM, New York, NY, USA, 1957-1962. DOI=10.1145/1979742.1979861 http://doi.acm.org.myaccess.library.utoronto.ca/10.1145/1979742.1979861
4. Luis Leiva, Matthias Böhmer, Sven Gehring, and Antonio Krüger. 2012. Back to the app: the costs of mobile application interruptions. In *Proceedings of the 14th international conference on Human-computer interaction with mobile devices and services* (MobileHCI '12). ACM, New York, NY, USA, 291-294. DOI=10.1145/2371574.2371617 http://doi.acm.org.myaccess.library.utoronto.ca/10.1145/2371574.2371617
5. Andrew Warr and Ed H. Chi. 2013. Swipe vs. scroll: web page switching on mobile browsers. In *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems* (CHI '13). ACM, New York, NY, USA, 2171-2174. DOI=10.1145/2470654.2481298 http://doi.acm.org.myaccess.library.utoronto.ca/10.1145/2470654.2481298
6. Nagata, Stacey F. "Multitasking and interruptions during mobile web tasks." *Proceedings of the Human Factors and Ergonomics Society Annual Meeting.* Vol. 47. No. 11. SAGE Publications, 2003.

###What to submit
```
Your project proposal must be typed and submitted as an electronic copy. The document can be
in Microsoft Word .DOC or Adobe Acrobat PDF formats.

Your document must also include:
• Team member names and email addresses on the cover page. DO NOT include
STUDENT NUMBERS.
• A group name
Additionally, complete a Group Information Form (see Portal). Much of the information will be
helpful to you as a group, but the photos will especially help the TA and the instructor learn your
names.
Submit both your proposal and the group information form through the UofT portal
(Blackboard). One submission per group; the instructor will assign you a group number and a
TA.

```
