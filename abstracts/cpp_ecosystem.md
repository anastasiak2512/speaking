# C++ ecosystem: For better, for worse

When legacy code is mixed with modern language features and patterns, when the rich heritage of C++ and its compatibility restrictions co-exist with the adoption of best practices from other languages and technologies, some of us C++ developers become lost and need to follow and stick to a more conservative path. Recent independent research studies show that developers are staying with C++11, only slowly moving to C++14 and rarely adopting C++17. They tend to avoid using unit testing frameworks, are barred from throwing exceptions, and often still build packages manually. Alongside the areas where strict limitations are imposed on the subset of the language used, there are others, like game development, that find workarounds to emulate language features not yet accepted to the language standard. What are the real reasons for this state of affairs, what biases might be at play, and what are some of the improvements planned?

In this talk, we will overview the C++ ecosystem based on several independently conducted research studies, identify the common aligning trends across all the sources, and analyze the reasoning behind them.

Importantly, we’ll see how the work of the C++ committee and tooling evolution can help overcome these difficulties and usher in a brighter future for C++. We’ll get a glimpse into some of the most valuable recent proposals and changes to the language, and see how tooling is helping, or can help, move to newer standards faster.

## Outline

This is not really a practical talk with which you could learn a new language feature or two, but it is more of a high-level overview of the C++ development ecosystem. Still, it should be useful for C++ developers of any level or specialization. Those who are just getting started with the language should take away an understanding of the whole ecosystem and some direction to help find their own path, while C++ committee members and language influencers will gain deeper insight into the needs of the C++ community.

* First, I plan to overview the current state of C++ development, using information gathered from several independent sources. These include surveys conducted by JetBrains through both internal and external channels, one of which attracted more than 4,000 C++ developer respondents; a survey run by the C++ Foundation; and a few other third-party research studies.
* Next, we’ll explore which language features, tools, and techniques are used across different areas of development, to help us identify the key evolution paths in the ecosystem. In addition, I’ll briefly overview some typical areas of application of C++ to identify the most important needs and requests of C++ developers.
* Last, we’ll discuss how the current language evolution addresses these needs. I will also focus on how the tooling can collaborate with the language to help drive the adoption of new features.

