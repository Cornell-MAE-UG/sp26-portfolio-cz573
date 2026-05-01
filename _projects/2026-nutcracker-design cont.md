---
layout: project
title: Nutcracker Design Cont
description: Additional Problem from Assignment 12 
technologies: [None]
image: /assets/images/Nutcracker2.jpg
---
1. Find (The problem statement and objective)
    Problem statement: The location of maximum elastic deflection in handles; a beam design s.t. vertical elastic deflection is less than 2% of its length

2. Given (Constraints and input parameters)
    A linear actuator of 2-40 inch stroke and force of 330 lbs.

3. Approach to problem (Calculations, assumptions, thought process)
    First, I drew out a free body diagram of the simple lever nut cracker containing two applied forces on the handles and two normal forces from the macadamia nut. Then, I defined the dimensions I knew and labeled dimensions I did not know with variables. I sliced two times to determine M(x) equations resulting from the applied and normal forces. Then, I used EIy'' = M(x), integrating. To find max elastic deflection, I found x when y'=0. Then, I found a design of an I beam, solving for y and determining whether this design worked.

4. Diagram of nut cracker design
    This diagram is the image linked.
    ![Photo of work]({{ "/assets/images/Nutcracker2.jpg" | relative_url }}){: .inline-image-l}

5. Reflection
    The actuator I chose is relatively strong; as such, there will be some deflection. However, the design of the aluminum I beam that I chose is also strong, making the deflection relatively small, less than 2% of the length.