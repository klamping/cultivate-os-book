This is not a book about Open-Source Software.

Open-source software has won as a movement. Even the most closed companies have adapted 



Several years ago, I was having frequent conversations with a past colleague and good friend of mine about the subject of Open-source Software. In our role at the time, we were tasked with developing and supporting an infrastructure framework for over 300 developers. His focus was on the server-side, mine on the front-end.

During our conversations, we began to grow an interest in how open-source projects run their show. We were specifically interested in some key parts:

1. Most open-source projects don't have dedicated, co-located teams. How do they cope?
2. How do they get people to volunteer their time?
3. How do they support their ever growing user base while staying adaptable?

It's hard to remember the specifics of the conversations, but the idea remains clear: Open-source projects face problems that, when you think about it, many internal projects face within companies.

1. Even if everyone is in the same office space, at a certain user base size, you're essentially working as a distributed team due to space constraints.
2. Teams will always be understaffed. Consumers of your project will likely be very busy with their own work and will have little time for contributing back.
3. After a certain number of users, you won't be able to keep up with the constant flow of "drive-by" questions and e-mails. You must balance time spent supporting your fellow teams with time spent developing new features. 

From these discussions, we started applying the open-source model to our internal work. We tried using more written communication, so that people could more easily access project information and documentation without having to set up meetings with us.

We also realized that switching to version based releases that projects "pull" down would allow us a much more iterative approach to development, compared to us pushing releases on top of their in-flight projects and causing a mess.

Additionally, we flirted with the idea of implementing our own flavor of [the Node Stability Index](http://nodejs.org/api/documentation.html#documentation_stability_index), to help promote a healthier product lifecycle for introducing, supporting and deprecating functionality.

In this book, I hope to share in great detail how we implemented these ideas, and to dive in to related thoughts I've had on the subject since parting ways with that specific project. Hopefully the information can help you better support the team your working with, even if you're not truly "Open-source".
