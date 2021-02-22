---
title: |
         CS 474/574 Machine Learning \
         1. HW1
author: |
          Tanner Boyle \
          Dept. of Statistics \
date:   \today
header-includes: |
    \usepackage{amssymb}
    \usefonttheme[onlymath]{serif}
    \usepackage[vlined,algoruled,titlenotnumbered,linesnumbered]{algorithm2e}
    \usepackage{algorithmic}
    \setbeamercolor{math text}{fg=green!50!black}
    \setbeamercolor{normal text in math text}{parent=math text}
    \newcommand*{\vertbar}{\rule[-1ex]{0.5pt}{2.5ex}}
    \newcommand*{\horzbar}{\rule[.5ex]{2.5ex}{0.5pt}}
    \setlength{\leftmargini}{0pt}
---

# Warm up

- Newton's first law of motion:
  - An object in motion will remain in motion unless acted upon by an outside force. An object at rest will remain at rest unless acted upon by an outside force.
  - $\sum F = 0 \iff \frac{dv}{dt} = 0$
- Einstein's mass-energy equation:
  - $E = mc^{2}$
- Time complexity of Quicksort on average in Big-O notation:
  - $\Theta(n log(n))$

---

- Supervised Learning:
  - The general idea of Supervised Learning is that a labeled dataset full of examples is utilized to learn a function that can take inputs map them to a certain output. For example, if we wanted to predict the price of a house in Ames given a dataset that contains many houses with their features and prices.
- Unsupervised Learning:
  - This differs from Supervised Learning in that the dataset is not labeled and the specified algorithm will attempt to make sense of it on its own. For example, if a grocery store wanted to put together customer 'profiles' by looking at combinations of items that are often purchased together.
- Reinforcement Learning:
  - Reinforcement Learning is fairly different from either of the other types of learning that we have talked about above. The main idea is that we let a computer sort out different ideas to optimize the solution to a certain problem. For example, if we wanted to train a computer to play a video game, we could program all of the possible moves that could be taken at any point and then kick off a simulation. Over time, the computer will 'learn' the optimal strategy by optimizing the target (which would be winning the game).

---

# Retail Kiosk Profitability Prediction

- If there are 5 categories of kiosks, the minimal dimensionality of the dataset would be six. There are five categories for the one-hot encoding and I am assuming that our measure of profitability adds only a single dimension.
