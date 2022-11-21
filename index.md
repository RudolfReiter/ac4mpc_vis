## Welcome to the project page of "A Hierarchical Pproach for Strategic Motion Planning in Autonomous Racing"

This work is related to an ECC 2023 submission by Rudolf Reiter, Jasper Hoffmann, Joschka Boedecker and Moritz Diehl.

An approach is presented for safe trajectory planning, where a strategic task related to autonomous racing is learned within a simulation environment. The following videos show evaluations of the trained HILEPP-II policy in different scenarios related to autonomous racing tasks. Opponent vehicles are simualted with an obstacle avoiding MPC formulations for autonomous racing, which not explicitly considers strategic driving (PPP)

## Scenario 1: Blocking
The ego vehilce starts first and has to block three stronger opponents. "Stronger" relates to parameters such as vehicle mass, accelerations limits and available braking force.
<<iframe width="560" height="315" src="https://www.youtube.com/embed/Pp5qHcdNGQw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Scenario 3: Mixed
The ego vehicle starts between a stronger following and a weaker leading vehicle and has to safely overtake as well as block the following opponent in order to achieve a good rank for as long as possible.
<iframe width="560" height="315" src="https://www.youtube.com/embed/muco3XlAByM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



