# Begin Here

Try to keep in mind that everyone is going learn their own way. The tech world is constantly changing with a rapid pace, so the way I learned things is not necessarily going to be the way that someone exactly like me is going to learn things, just because we started at different times when different technologies were mature.

Also, we're different people! So some of the things that I'll talk about won't resonate with you and that's okay. Wherever possible, I'll try to include alternative sources for you to explore on your own. These can be supplemental to the stuff I'll cover, or they can send you off into a whole new direction that I don't know enough about.

With that, let's start with the landscape. I'm going to try to use analogies to cars right now but just remember that the analogy isn't perfect.

## Software

A **software engineer** is the classic example of what someone probably thinks about when they are thinking of someone who writes code for a living. They write thousands and thousands of lines of code to make a piece of software that does something specific for you without you needing to understand how it works.

The end goal of **software development** is ultimately to create an executable file that does something useful when you run it. Examples of the end products of software engineering are: video games, web sites, web browsers, databases, media players, photo editors, command-line consoles, messengers, and anti-virus.

### UIs and APIs

The purpose of a piece of software is usually to make a task that is kind of complicated much simpler. Usually, the way this is done is by providing an **interface** to a more complex system underneath the software.

The kind of **interface** a piece of software provides defines it as being either a front-end system or a back-end system.

### Front-end Systems

Front-end engineers design systems that are made to be used by human beings. They're thinking about how nice an interface looks, how easy it is to use, and whether it is accessible to many different kinds of people. They need to consider users like blind people using screen readers, deaf people who need closed captioning, and color-blind people who can't differentiate between certain colors, and many other situations that might impact how useful their application is.

The interface for a front-end system is called a **user interface**, or a **UI**.

Front-end engineers today almost always are designing **web front-ends**, which are user interfaces that run in a web browser, or **mobile applications**, which are interfaces that run as native applications on your phone. A mature application typically offers both, but start-ups very often only have the resources to provide one or the other, depending on what kind of software they make.

### Back-end Systems

Back-end engineers design systems that are primarily used by other software. This can be software that their company or team also makes, or it can be software made by their customers. The back-end will generally be where a lot of data is stored and where a lot of the more complex computing and logic is written. Usually, front-end systems use at least one back-end system, and sometimes other back-end systems will use other back-end systems.

The interface for a back-end system is called an **application programming interface**, or **API**.

Often, it is easier to make a ton of smaller applications, each with their own API, than it is to make one large and very complicated system with a single API. In the old days, they used to make everything one big program; now we tend to think of one application being made up of many **microservices**, with each **microservice** doing one specific thing very reliably. This makes the code easier to write and deploy, and debugging is a lot easier when only one small part of the app breaks because of a bug.

All this complexity is typically hidden from the human end-user because they only need to see the front-end system, but developers spend a lot of their time thinking about and working on the back-end systems that support the application.

### Servers and Clients

When we talk about program A using program B, engineers usually say that program A is a **client** or a **consumer** of program B's API. In contrast, program A **serves** or **exposes** its API to program B.

This way of talking about inter-systems communication is where the word **server** comes from. Essentially all applications on the Internet are designed with a server-client relationship in mind, including each microservice. Every front-end application talks to a back-end server somewhere in the world to fetch its data, and every back-end application is designed and maintained with the purpose of serving one or more clients.

## Operations

A lot of tech work doesn't actually produce code or executables that anyone else will ever use. Sometimes you just need someone to keep things running, fix problems that come up, and maybe have some general working knowledge to prototype solutions to problems that come up with the cars.

If I'm a mechanic, I might get a car for my own use, but maintain it myself. I know enough about it to take it apart and put it back together in some limited ways, and maybe I can customize it by swapping parts out or even removing parts that I don't think are necessary or desirable. If it breaks or there's a serious problem in the design, I might be able to come up with a stopgap solution that works pretty well, and maybe I'll tell the engineers about my solution in case they want to adopt it as a permanent feature of their future cars.

I might even work in the shop sometimes doing assembly of cars that other people have designed, according to their blueprints.

The person who assembles and maintains the cars, modifies them for specific purposes, and fixes them when they break are *dev ops engineers*. Dev ops stands for "development operations", and it encompasses a ton of work that is absolutely necessary for a website or a web application to function, but is a lot less glamorous than the work that software engineers do.

## Security

There is some overlap here between operations and security, but I generally think of them as being separate because security is generally a different group of people and the skill set for a security analyst or security engineer usually involves non-technical skills as well.

This is also where the car analogy gets a little forced. The closest I can come to is that somewhere out there, there are people who know how to break into, hotwire, sabotage, steal, vandalize, and otherwise do stuff to cars that their owners and creators did not intend or want.

Security is the all-encompassing art of minimizing the amount of damage people like that can do.

This is a _huge_ area, because there are tons of things you can do to keep your car safe. Sometimes it doesn't have anything to do with the actual car. Some are really easy and just require resources; parking your car in a locked garage at night means that casual vandalism and theft is largely prevented. Some are for the truly paranoid, like maybe installing security cameras, motion sensors, and burglar alarms. Maybe you also plant a GPS tracking device somewhere in the car so you can catch the asshole during their joyride. And sometimes it entails really boring common sense measures like remembering to lock the doors and roll up the windows, or remembering to pay your car insurance on time so your policy doesn't lapse.

