How do I know if my program will perform well in production? What does it mean to “perform well”? How much memory will it need? How much traffic can it serve? Are there any memory leaks or race conditions? What part of processing takes up most of the time? Can I optimise it?

Every developer should be able to answer those questions about their code. But most of us don’t bother. Why? Because analysing performance is hard and as a result it is often skipped in the development process or ignored until things get really slow. Or we may simply not know where to start.

Writing efficient code is a valuable skill that takes time to learn. Being able to analyse performance can not only prove that our code is efficient and safe to run in production, but also teaches us what to avoid next time. It may seem daunting at first, but with the right tools at hand it is a highly rewarding process.

In this talk, we will analyse and optimise the performance of a simple PHP application. By demonstrating how to use some of the excellent open source projects such as xdebug, xhprof or php-meminfo, I hope to give you a good idea of where to start with analysing and optimising your PHP code.
