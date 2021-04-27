# A District Design Approach to Construct Pilgrim Camp Layouts

This paper focuses on a districting problem that arises in the context of Hajj pilgrim camp site
design. The goal of this design approach is to construct a camp layout plan for up to 500,000
pilgrims given a set of basic tent units. We will formulate a bi-objective mathematical planning
model for the problem. It incorporates constraints to ensure that each camp provides access
to a sanitary facility, an entry point to the road network and sufficient space to accommodate
the pilgrim group. The model’s first objective is to spatially distribute the camps in accordance
with a prescribed pilgrim departure schedule. The second objective is to generate regular,
simple and contiguous camp shapes. To attain results for large instances, we develop a two
stage solution procedure. In the first stage, we use a mixed-integer programming approach
to partition the solution space. This allows us to solve multiple districting subproblems in the
second stage independently. Our districting model establishes a contiguous core of layout units
for each camp. Additionally, outer layout units may be partially assigned to adjacent camps.
We illustrate this novel approach by applying it to the real dataset of Hajj season 2018 with
more than 395,000 pilgrims in 282 camps and 3,058 spatial units. We construct a feasible starting
solution in under 12 minutes computation time. Using parallel processing of the subproblems,
we generate partial solutions in 32 cpu seconds on average during the improvement phase.