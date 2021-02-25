# Code Analysis++

Martin Fowler once wrote that high-quality software is actually cheaper to produce than low-quality software. We agree with that sentiment, and we warmly welcomed the C++ Core Guidelines when they were introduced in 2015. Research and surveys conducted in the C++ Community consistently demonstrate the popularity of the Clang family of tools, as well as the growing demand for static analysis to be added to code editors. 

In this talk, we’ll explore the current capabilities of existing C++ static analyzers and discuss some of the enforcements listed in the C++ Core Guidelines from a toolability aspect. We’ll also look into the recent “Simplify C++” trend in the language’s evolution, and to wrap things up we’ll take a look at how technology-specific analysis (like MISRA and AUTOSAR) is being adopted. 

A variety of checks will be discussed, from catching a dangling pointer to conforming to the preferred code style and naming scheme. And I want to share a crazy idea I have about gamifying static analysis. Let’s play!

# Статический анализ кода++

В одной из статей Мартин Фаулер писал, что софт более высокого качества обходится дешевле в создании (а не только поддержке, как можно было бы подумать). Отчасти поэтому сообщество C++ тепло встретило C++ Core Guidelines, представленные в 2015 году. Хотя в них не всегда четко прослеживается грань между абстрактными советами в стиле «хорошо писать хорошо» и более конкретными предложениями, которые можно реализовать в статических анализаторах, наподобие «в таких ситуациях надо проверять вот это». Что же умеют современные статические анализаторы? Какие типичные боли C++ и стилистические неточности они отлавливают? Как разработчики предпочитают взаимодействовать с подобными инструментами? В докладе поговорим об этих вопросах и даже обсудим геймификацию в анализаторах кода.
