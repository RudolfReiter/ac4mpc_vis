## Welcome to the project page of "A Long-Short-Term Mixed-Integer Formulation for Highway Motion Planning"

This work is related to an IEEE journal submission by Rudolf Reiter, Armin Nurkanovic, Daniele Bernardini, Moritz Diehl and Alberto Bemporad.

The following simulations show, how the LSTMP plans and executes lane changes in closed-loop simulations. Each simulation consists of randomized surrounding vehicles with different speeds. Surrounding vehilces break, if they are close to a leading vehicle. The the planner uses a safe short-term trajectory (black) to plan the first lane change and uses transition points in the spatio-temporal space for long-term planning (green). The full planning problem is formualated as MIQP and solved in approximately 50ms.

### Scenario 1:
LSTMP:
<iframe width="1500" height="270"  src="https://www.youtube.com/embed/mjTDH2EOvLA?si=CvwAPcT6aIt0CYcw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

A-star:
<iframe  width="1500" height="270"  src="https://www.youtube.com/embed/O2Nng0nPqAg?si=6_XLSObHxZZizbBn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

MIPDM (N=15):
<iframe  width="1500" height="270"  src="https://www.youtube.com/embed/Gu-LHjxLqlg?si=oMPzSqDrZrGq8-zO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

MIPDM (N=20):
<iframe  width="1500" height="270" src="https://www.youtube.com/embed/cOM4uULTNr8?si=aQcqcx6IzNLnjmu5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


### Scenario 2:
LSTMP:
<iframe  width="1500" height="270"  src="https://www.youtube.com/embed/GlhYKSTqog0?si=olEU7QSo764VBDYy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

A-star:
<iframe  width="1500" height="270"  src="https://www.youtube.com/embed/ymD1YXdINt0?si=a652u8PQ-1GGQSRL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

MIPDM (N=15):
<iframe  width="1500" height="270" src="https://www.youtube.com/embed/ODomLqjXqAw?si=Pr-9ZozTmNY9uYUC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

MIPDM (N=20):
<iframe  width="1500" height="270"  src="https://www.youtube.com/embed/drMFY6f_KVk?si=Sv62XTeLdaS-YX8r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
