### Org
https://opensandiego.org/

public data
https://www.cde.ca.gov/ds/sd/sd/filessp.asp

### WHY:
Multiple schools in a district can be grouped together in order to receive subsidies for lunches.
This creates an optimization problem for districts because they want to optimize for dollars saved and there are too many combinations of schools to be grouped together in a district.

### WHAT:
$4.75 per lunch
$1.74 per breakfast

### Variables:
We will refer to Poverty Percentage as PP below
% Meals Subsidized = MS

if:
    PP >= 40% and PP <= 62.5%
then:
    %MS = PP x 0.016
elif:
    PP >= 62.5%
then:
    % MS = 100%

        
