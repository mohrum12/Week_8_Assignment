# Week_8_Assignment  Auto MPG (UCI)
Explore how basic vehicle characteristics relate to performance using the classic Auto MPG dataset, focusing on cylinder mix and the relationship between weight and horsepower overall and by origin.

1. Distribution of Cylinders
The fleet is dominated by 4-cylinder cars, with smaller groups of 6- and 8-cylinder vehicles; 3- and 5-cylinder models are rare.
Interpretation: manufacturers increased production of lighter, more efficient 4-cylinder cars during the period represented by this dataset, while 6/8 cylinders align with larger, heavier models.

2. Horsepower vs. Weight
A strong positive relationship: heavier cars generally require higher horsepower.
The spread widens at higher weights ≈ 3,800–5,000 lbs, reflecting different tuning choices some high-power variants vs. economy-tuned versions.

3. Horsepower vs. Weight by Origin
USA: broadest weight range and the steepest slope, indicating a strong horsepower increase with added weight; many vehicles sit in the high-weight, high-horsepower region.
Europe: lighter on average; positive slope but lower overall horsepower at a given weight compared to USA.
Asia: lightest cluster with a clear positive slope; for the same weight, horsepower is typically lower than USA but comparable to or slightly below Europe, consistent with efficiency-oriented designs of the era.

# What the plots show
Cylinders. The fleet is dominated by 4-cylinder cars; 6- and 8-cylinder models form smaller clusters, and 3/5-cylinder are rare. This mix reflects the period’s push toward lighter, more efficient vehicles, while 6/8 cylinders align with heavier models.

Horsepower vs. Weight. There’s a strong positive association: as weight rises, horsepower rises. The cloud widens at higher weights (≈3,800–5,000 lbs), showing multiple design choices.

# By origin.

USA: broadest weight range and the steepest slope—horsepower climbs quickly with weight; many heavy/high-power models.

Europe: generally lighter; lower horsepower at a given weight than USA; still a clear positive slope.

Asia: lightest cluster; positive slope with lower horsepower at the same weight than USA (and roughly similar to or below Europe), consistent with efficiency-oriented designs.

Implications. Weight is the anchor variable; cylinders and displacement co-move with weight, explaining why MPG typically declines as weight/horsepower increase. Because these predictors are collinear, simple models need regularization or careful feature selection.
