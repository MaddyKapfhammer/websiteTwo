+++
author = "Madelyn Kapfhammer"
title = "Sometimes the majority isn't always right"
date = "2020-10-22"
description = "Sometimes being a female "
tags = [
    "Computer Science",
    "Group Engineering",
]
+++

In the spring of 2020, my first semester at Allegheny College, I took a software engineering class in the computer science department. In essence, the class was a combination of understanding programming best-practices and creating a functioning tool as a class, emphasis on **as a class**. The professor (who yes, was also my father), gave the class an idea for a tool, the basics of implementation, and then sat back to let the students do the work. While, yes, this does sound a little crazy, I was _excited_ about the project, and stepped up to be a group leader with a few other students in the class.

Our professor proposed a tool that would determine the contribution of an individual to a GitHub project, and also the efficiency of teams working together. Of course, there were ups and downs in the creation of this tool; inevitably, there were students who didn't make _any_ contributions, leaders who weren't assertive, and (possibly the worst) students who _always_ thought they were right... when they weren't.

As much as I enjoyed making goals for our class to complete the tool by the deadline, observing my peers to see what code they were writing, and setting some guidelines for our project, it felt a lot of the time that I was working with only a few other students to make the best tool possible. Working so hard, and only seeing a few other people reciprocate your energy and work-ethic is a little disheartening.

Of course, the disappointment culminated in frustration when developing the algorithm for calculating a "group score". This score had the purpose of determining how well a group of software engineers work together, something that is extremely valuable in industry. A certain group of students in the class was tasked with developing the code for this aspect of our tool, however when the demoed it's functionality, it seemed that the algorithm was hard-coded and only really understood by one person in the group. This raised red-flags for the group of leaders I had been collaborating with, and I offered to generate a new algorithm. It seemed, that despite us raising issues with the group who was working on group score, that they were not continuing to improve their code, and the deadline for our tool was gaining on the class.

Working with another female student, whom I respect immensely, I developed way to generate a group score. Without getting into the details, my contribution dealt with the interquartile range, whereas the other group used mean, standard deviation, and the bell curve. It seemed obvious that the approch my peer and I had implemented was better, it wasn't hardcoded, it was refactored, and it was **simpler**. The people in the other group didn't see it that way, despite not doing _any work_ on their algorithm for many weeks.

It came down to a class vote. My female collaborator and I presented our IQR strategy, and our male counterpart presented his confusing, bell curve strategy. It was clear that I had the better idea, and yet the class (majority males may I add) voted for an algorithm that was hard-coded, monolithic, and hadn't been worked on in weeks.

It was decided that the initial group would implement their algorithm into our tool, one of the final steps to finish by the deadline. With monitoring for days after the vote, the algorithm hadn't been changed to be used in our final version of the tool. With two days to the deadline, I ended up implementing, and merging our IQR strategy for calculating a group score and it worked **almost perfectly**.

Sometimes people have such big egos that they stand by believing that their strategy is the best approach (when it isn't), and most of the time the majority of people will agree with them. These are the cases in computer science, and in life that it is best to **stand up** for what is best. I wish I would have taken a different approach in Software Engineering last year, I could have made the process of creating our class tool so much smoother than it was, however, it showed me that in computer science, often the people in the minority are the ones who really know what's going on. We should listen to them more.

In case you're interested, we did finish our tool, and named it `Cogitate` you can check it out on GitHub [here](https://github.com/GatorCogitate/cogitate_tool/issues)