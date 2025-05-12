---
layout: page
title: RoboBarista - Autonomy of a Franka Arm for Coffee-Making
description: A coffee-making robotic arm engineered to handle liquids with exceptional efficiency, utilizing precise pouring techniques and real-time weight feedback for consistently perfect results. 
img: assets/img/project8.jpg
#redirect: https://github.com/swastikmhptr/Terrorism-Vulnerability-Prediction-model-for-Indian-States
importance: 2
category: masters
---

This work presents the design and implementation of an autonomous coffee-making system using a Franka robotic manipulator arm, aimed at advancing automation in the food and beverage industry. The system is capable of preparing various coffee beverages by autonomously detecting, grasping, and pouring ingredients into a user’s mug according to specified recipes. Key challenges addressed include careful manipulation of ingredient cups to avoid spillage, ensuring accurate pouring to meet quantitative requirements for each recipe, and localizing all obstacles and the output cup to operate in a mobility-constrained environment. To simulate liquid handling in a controlled setting, colored beads were used as a proxy for liquid ingredients. The methodology integrates computer vision for output cup localization, precise grasping strategies, and constrained trajectory planning using MoveIt, with additional real-time feedback from a weighing scale and force-torque sensors to ensure accurate ingredient dispensing. A custom pouring controller was developed to map cup weight to tilt angle and pour-stop thresholds, achieving pour accuracy within 5 grams of the target amount and a pour success rate exceeding 88\%  . The system demonstrated robust perception and motion planning, with failures occurring only rarely. This work provides a framework adaptable to other beverage automation tasks, promoting use of robotics in the food and beverage industry. Future improvements include supporting a broader ingredient set, developing an interactive user interface, and refining motion planning to further increase reliability and versatility.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQJ6CsTVJQpJrw4b6AVeHd_9XPHAIIBys7fk3huJvk3qUDi5-78VVwI5721RjJI5mwxi3Q8t2fFFjz1/pubembed?start=true&loop=true&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

<iframe width="960" height="540" src="https://www.youtube.com/embed/FpSIwTEgfxM" title="YouTube video player" frameborder="0" allowfullscreen></iframe>


The complete research outcome of this project can be found in the paper shown below:

<iframe src="https://drive.google.com/file/d/1pVGMqnUY_H1GTfhfIyl64hvtPYjqsEat/preview" width="960" height="480" allow="autoplay"></iframe>

This project is still in progress, but the complete code will eventually be published in the below mentioned repository:

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
    {% assign second_last_repo_index = site.data.repositories.github_repos.size | minus: 2 %}
    {% assign second_last_repo = site.data.repositories.github_repos[second_last_repo_index] %}
    {% include repository/repo.liquid repository=second_last_repo %}
</div>


