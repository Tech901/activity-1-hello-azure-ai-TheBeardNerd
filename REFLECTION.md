# Reflection -- Hello, Azure AI

Answer these questions after completing the activity (2-3 sentences each). Connect your answers to specific things you observed while coding and experimenting.

## 1. Service Surprises

Which of the three Azure AI services (OpenAI, Content Safety, Language) surprised you the most? Connect this to something specific you observed during your experiments -- a response you didn't expect, a behavior that seemed too easy or too hard, or a result that made you rethink how the service works.

> The Content Safety service suprised me the most. It's also the most dificult to do well. It has to take into account the nuances of human speech/text patterns and attempt to correctly clasify them based on more rigid rules.

## 2. Lazy Initialization

How would you explain the lazy initialization pattern to a colleague? Why is it used instead of creating clients at the top of the file?

> Lazy initialization keeps the program from making expensive API calls until the precise time they are needed.
> It's used to boost performance and save computational resources.

## 3. Content Safety in the Real World

A resident files this complaint: *"A man was assaulted at this intersection because the street light has been out for months."* This text describes real violence but is a legitimate safety concern. Should the system block it, flag it for human review, or pass it through? What factors would you weigh in making that decision?

> Ideally, the system should be robust enough to distinguish between actual violence and something that is part of a legitimate safety concern.
> In this case, the system should flag it for human review, so a parson can make a true determination.
> If the system blocks it, a legitimate safety concen doesn't make it to the department which can help.
> If the system passes it through, then the safety check is pointless.
