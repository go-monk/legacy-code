Almost everyone loves working on greenfield projects. Almost everyone hates working on legacy code.

Greenfield projects allow you to choose your technology, and you don't need to try to understand existing code. It's a lot of fun building new things, especially when you (and your team) are experienced.

On the other hand, legacy code is code handed over to you to maintain. Usually, it's a nightmare. You have to understand the thinking of a programmer who is either long gone or not very able (fuzzy thinking is commonplace) or unwilling (people are often afraid) to explain what they have done. On top of that, tests and documentation might be missing or bolted on in an ad-hoc fashion.

At this point, you have two main options. One is to hate the code and the person who produced it, and complain about it all the time. Easy, right? The other is to try to understand and improve the code. (You could also refuse to work on the project or even for the company. This seldom helps, though. The next project or company will probably have similar legacy code.)

If you decide on the second option, the first step is to try to understand the high-level aspects: who is using the code and how they are using it. Try to use it yourself and read the end-user documentation.

Next, look at the implementation. Try to identify the major components and see how they interact.

Then zoom in to a component or a small part of it and try to figure it out.

Next, try to improve it. Extract functions or methods, rename variables, write tests, ...

If you persist and keep looping over the steps above, things will necessarily start becoming clearer and more enjoyable. Something that was barely readable and took ages to understand might soon read like a story. And this benefits you, your future self, and other people either working on the code or (even indirectly) using it.

---

Based on "The Software Craftsman" book by Sandro Mancuso (2015)
