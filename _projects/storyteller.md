---
layout: page
title: Storyteller
description: A storyboard app that helps filmmakers plan their shot
img: assets/img/projects/Storyteller/Storyteller_thumbnail.png
importance: 2
category: Apps and Tools
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/projects/Storyteller/Storyteller_thumbnail.png" title="Storyteller" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In recent years, we have witnessed the rise of independent filmmakers due to the increasing accessibility of film equipment. Traditionally, the film industry relies on storyboard artists to create sketches that visualize key scenes and actions, serving as a blueprint for a film's look and flow. However, as a passionate independent filmmaker, I experienced firsthand the lack of handy tools for storyboard creation, especially for small-budget or personal projects where hiring a dedicated artist is not practical.

To address this, I led a team of three to develop an iPad app that simplifies storyboard design. Our app empowers filmmakers and videographers to effortlessly create rough sketches to describe their shots and organize them into scenes, making the planning process more intuitive and efficient.

As the project leader, I need to first pitched the concept and stand out among competing ideas to attract talented team members. In the end, I teamed up with two skilled programmers Marcus and Yongjing, who shared my vision. During development, I adopted the Agile methodology, breaking the project into manageable tasks, iterating in short cycles, and ensuring the team stayed on track through effective task delegation and oversight.

In addition to leadership, I served as the core developer, focusing on the app's most technically demanding feature: the shot designer interface. Key contributions include:

- **Onion Skin Overlays**: Incorporated translucent overlays of preceding and following shots for easier comparison between shots.
- **Apple PencilKit Integration**: Enabled seamless communication with Apple Pencil for precise sketching and annotation.
- **Layer Management**:
  - Add, delete, duplicate, reorder, scale, rotate, lock, hide layers.
  - Insert images into layers.
  - Group and ungroup layers for organization.
- **Shots Manipulation**:
  - Add, delete, duplicate shots
  - Rotate and scale shots temporarily for better drawing experience
  - Set custom background color

Among these features, layer management posed the greatest challenge due to its complex interactions between layers and the canvas, particularly when grouping was involved. I implemented an elegant solution using a combination of the Composite and Visitor design patterns, enabling robust and flexible layer interactions.

For more detailed technical reports, please visit the [GitHub Repository](https://github.com/T-Fang/Storyteller).

These features collectively empower filmmakers to create highly detailed and dynamic storyboards directly on their iPads, bridging the gap between professional tools and the needs of independent creators.
