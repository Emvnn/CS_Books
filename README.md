# Teach Yourself Computer Science
If you’re a self-taught engineer or bootcamp grad, you owe it to yourself to learn computer science. Thankfully, you can give yourself a world-class CS education without investing years and a small fortune in a degree program. 💸

There are plenty of resources out there, but some are better than others. You don’t need yet another “200+ Free Online Courses” listicle. You need answers to these questions:

- **Which subjects should you learn, and why?**
- **What is the best book or video lecture series for each subject?**

This guide is our attempt to definitively answer these questions.

## Outline
Study all nine subjects below, in roughly the presented order, using either the suggested textbook or video lecture series, but ideally both. Aim for **100-200 hours of study** of each topic, then revisit favorites throughout your career. 🚀

---

| **Subject** | **Why study?** | **Book** | **Videos** |
|------------|---------------|----------|------------|
| **[Programming](Programming/)** | Don’t be the person who “never quite understood” something like recursion. | *Structure and Interpretation of Computer Programs* | Brian Harvey’s Berkeley CS 61A |
| **[Computer Architecture](Computer%20Architecture/)** | If you don’t have a solid mental model of how a computer actually works, all of your higher-level abstractions will be brittle. | *Computer Systems: A Programmer's Perspective* | Berkeley CS 61C |
| **[Algorithms and Data Structures](Algorithms%20and%20Data-Structures/)** | If you don’t know how to use ubiquitous data structures like stacks, queues, trees, and graphs, you won’t be able to solve challenging problems. | *The Algorithm Design Manual* | Steven Skiena’s lectures |
| **[Math for CS](Math%20for%20CS/)** | CS is basically a runaway branch of applied math, so learning math will give you a competitive advantage. | *Mathematics for Computer Science* | Tom Leighton’s MIT 6.042J |
| **[Operating Systems](Operating%20Systems/)** | Most of the code you write is run by an operating system, so you should know how those interact. | *Operating Systems: Three Easy Pieces* | Berkeley CS 162 |
| **[Computer Networking](Computer%20Networking/)** | The Internet turned out to be a big deal: understand how it works to unlock its full potential. | *Computer Networking: A Top-Down Approach* | Stanford CS 144 |
| **[Databases](Databases/)** | Data is at the heart of most significant programs, but few understand how database systems actually work. | *Readings in Database Systems* | Joe Hellerstein’s Berkeley CS 186 |
| **[Languages and Compilers](Languages%20and%20Compilers/)**  | If you understand how languages and compilers actually work, you’ll write better code and learn new languages more easily. | *Crafting Interpreters* | Alex Aiken’s course on edX |
| **[Distributed Systems](Distributed%20Systems/)** | These days, most systems are distributed systems. | *Designing Data-Intensive Applications* by Martin Kleppmann | MIT 6.824 |

## Still too much?
If the idea of self-studying 9 topics over multiple years feels overwhelming, we suggest you focus on just two books: *Computer Systems: A Programmer's Perspective* and *Designing Data-Intensive Applications*. These two books provide incredibly high return on time invested, particularly for self-taught engineers and bootcamp grads working on networked applications. They may also serve as a "gateway drug" for the other topics and resources listed above.

## Why learn computer science?<a name="Why"></a>
There are 2 types of software engineer: those who understand computer science well enough to do challenging, innovative work, and those who just get by because they’re familiar with a few high level tools.

<a href="https://twitter.com/jenna/status/838161631662092289">
    <img align="right" width="500" alt="bilotta-tweet" src="https://github.com/user-attachments/assets/d7535b63-7da3-4f31-a129-1f393162f056" />
</a>


Both call themselves software engineers, and both tend to earn similar salaries in their early careers. But Type 1 engineers progress toward more fulfilling and well-remunerated work over time, whether that’s valuable commercial work or breakthrough open-source projects, technical leadership or high-quality individual contributions.

Type 1 engineers find ways to learn computer science in depth, whether through conventional means or by relentlessly learning throughout their careers. Type 2 engineers typically stay at the surface, learning specific tools and technologies rather than their underlying foundations, only picking up new skills when the winds of technical fashion change.

Currently, the number of people entering the industry is rapidly increasing, while the number of CS grads is relatively static. This oversupply of Type 2 engineers is starting to reduce their employment opportunities and keep them out of the industry’s more fulfilling work. Whether you’re striving to become a Type 1 engineer or simply looking for more job security, learning computer science is the only reliable path.

---

### Frequently Asked Questions

#### Who is the target audience for this guide?

We assume you're a self-taught software engineer, a bootcamp graduate, an early-stage student, or currently studying and looking to complement formal education with self-study. The question of when to begin this journey is purely personal, but most people benefit from gaining some work experience before diving deep into computer science theory. For example, we notice that students tend to enjoy learning about database systems after working with databases in a professional context or about computer networks after working on a web project.

#### What about Artificial Intelligence/Computer Graphics/Favorite Topic-X?

We've tried to limit our list to computer science topics that all practicing software engineers should know, regardless of specialization or industry, with an emphasis on systems. From experience, we’ve found that these topics give the highest return for the vast majority of self-taught engineers and bootcamp graduates and lay a strong foundation for further study. After this, you'll be in a much better position to pick up textbooks and papers and learn core concepts independently. Here are our recommended starting points for some common "electives":

* For Artificial Intelligence: Take the [Introduction to AI course by Berkeley](http://ai.berkeley.edu/home.html), watch the videos, and complete the excellent Pacman projects. As a textbook, use *Artificial Intelligence: A Modern Approach* by Russell and Norvig.
* For Machine Learning: Take Andrew Ng’s course on Coursera. Be patient and make sure to understand the basics before diving into hot new topics like Deep Learning.
* For Computer Graphics: Work through the material from [CS 184 at Berkeley](inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html) and use *Computer Graphics: Principles and Practice* as a textbook.

#### How strict is the suggested order?

Realistically, all of these subjects overlap significantly and refer back to each other cyclically. For example, the relationship between discrete mathematics and algorithms: Learning mathematics first helps you analyze and understand algorithms deeply, but learning algorithms first gives greater motivation and better context for discrete mathematics. Ideally, you’ll revisit these topics multiple times throughout your career.

Therefore, the suggested order is mainly intended to make your entry easier. If you have a good reason to prefer a different order, feel free to do so. The key "prerequisites" in our opinion are: Computer architecture before operating systems or databases, and networks and operating systems before distributed systems.

#### How does this compare to the Open Source Society or freeCodeCamp curriculums?

When this guide was first written in 2016, the [OSS guide](https://github.com/ossu/computer-science) had too many topics, suggested low-quality sources for many of them, and didn’t provide reasoning or guidance on why and which aspects of certain courses would be valuable. We’ve tried to focus the course list on what you, as a software engineer, should really know, and to help you understand why each course was recommended. In the following years, the OSS guide has improved, but we still believe this one offers a clearer, more cohesive path.

FreeCodeCamp mainly focuses on programming, not computer science. If you're new to programming, we recommend prioritizing that and returning to this guide in 1-2 years.

#### What about Language X?

Learning a specific programming language is a completely different level from learning a computer science area. Learning a language is much _easier_ and much _less valuable_. If you already know a few languages, we highly recommend following this guide and filling in the gaps by learning languages or postponing that until later. If you’ve learned programming well (e.g., through *Structure and Interpretation of Computer Languages*), and especially if you’ve learned compilers, it should take no more than a weekend to learn the basics of a new language, after which you can familiarize yourself with the libraries/tools/ecosystem.

#### What about trendy Technology X?

No single technology is so important that learning its application should be a core part of your education. On the other hand, it's great if you're excited about a particular topic. The trick is to work backward from the specific technology to the underlying field or concept and thoroughly learn that before looking at how your trendy technology fits into the bigger picture.

#### Why still recommend SICP?

Just try it out. Some people are blown away by SICP, a characteristic that few other books share. If you don't like it, you can always try something else and maybe return to SICP later.

#### Why still recommend the Dragon Book?

The Dragon Book is still the most comprehensive source for compilers. It has a bad reputation, usually for emphasizing certain topics that are less frequently covered in detail today, like parsing. The thing is, the book was never meant to be worked through from front to back, but rather to provide enough material for instructors to assemble a course. Similarly, a self-learner can choose their path through the book or, even better, follow the suggestions that instructors of public courses have made in their course descriptions.

#### How do I get affordable textbooks?

Many of the textbooks we recommend are available online for free thanks to the generosity of their authors. For those that aren't, we recommend buying used copies of older editions. In general, if multiple editions of a textbook exist, an older edition is likely perfectly sufficient. It’s unlikely that the latest version is ten times better than an older one, even if that’s exactly the price difference!

#### Who put this together?

This guide was originally written by [Oz Nova](https://twitter.com/oznova_) and [Myles Byrne](https://twitter.com/quackingduck), with updates in 2020 by Oz. It is based on our experience teaching over 1,000 mostly self-taught engineers and bootcamp graduates the fundamentals of computer science, both in small groups in San Francisco and live online. Thanks to all our students for their continuous feedback on self-learning resources.

We’re confident you can teach yourself everything listed above with enough time and motivation. However, if you prefer an intensive, structured, instructor-led program, you might be interested in our [Computer Science Intensive Course](https://bradfieldcs.com/csi/). We [DO NOT](https://ozwrites.com/masters/) recommend pursuing a Master's degree.
