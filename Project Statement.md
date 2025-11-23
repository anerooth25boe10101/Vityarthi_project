**Project** **Statement:** **The** **Passion** **Discovery** **Journal**

**1.** **Problem** **Statement**

In today's world, young people are exposed to countless hobbies, career
paths, and distractions. This abundance of choice often leads to
"analysis paralysis"—a state where individuals are unsure of where to
direct their energy. We often struggle to differentiate between a
ﬂeeting interest (a hobby) and a sustainable life path (a passion). The
core problem this project addresses is the **lack** **of** **objective**
**data** when making personal life decisions.

**2.** **Proposed** **Solution**

The **Passion** **Discovery** **Journal** is a Python-based software
tool designed to bridge the gap between qualitative feelings and
quantitative data. Instead of relying on vague intuition, the user
inputs daily activities into a command-line interface (CLI). The
software uses a weighted scoring algorithm to track these activities
over time, providing a clear, data-driven picture of what truly engages
the user.

**3.** **Methodology** **&** **Algorithm**

The solution does not rely on complex AI, but rather on foundational
psychological metrics. Every activity is scored out of **40** **points**
based on four pillars:

> **1.** **Enjoyment** **(0-10):** Pure subjective pleasure.
>
> **2.** **Focus** **(0-10):** The ability to enter a "Flow State"
> (losing track of time).
>
> **3.** **Energy** **(0-10):** Post-activity state (energized vs.
> drained).
>
> **4.** **Curiosity** **(0-10):** The desire to learn more
> (persistence).

The formula used is:

Total Score = Enjoyment + Focus + Energy + Curiosity

**4.** **Key** **Features**

> **·** **Data** **Entry:**A robust input loop that validates user data.
>
> **·** **VisualAnalytics:**A text-based graphing engine to visualize
> relative scores in the terminal.
>
> **·** **Battle** **Mode** **Logic:**A comparison algorithm that sorts
> all entries and pits the top two against each other in a hypothetical
> "life-choice" scenario, forcing the user to make a deﬁnitive choice.

**5.** **Technology** **Stack**

> **·** **Language:** Python 3.x
>
> **·** **Libraries:** Standard Library only (random) to ensure
> portability and ease of use.
>
> **·** **Interface:** Command Line Interface (CLI) for distraction-free
> journaling.

**6.** **Conclusion**

This project demonstrates that code can be used not just for automation
or calculation, but for introspection. By organizing personal data, the
Passion Discovery Journal helps users identify the activities that
provide them with the most meaning, potentially guiding future career or
educational choices.
