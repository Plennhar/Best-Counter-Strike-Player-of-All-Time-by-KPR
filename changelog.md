# 2026.07.09
* Added year 2004 back in.
* Reduced qualification criteria to no longer require the tournaments being played in to be of any combined prize pool.
* Changed the calculation for Performance Score.  It now simply looks at the difference between a player's Adjusted Weighted KPR in any given year, and the mean Adjusted Weighted KPR of that year.

# 2026.04.30
* Removed year 2004 from the rankings due to its dataset being too limited.

# 2026.04.21
* Replaced the z-score-based yearly scoring model with a bounded within-year Performance Score model, where 0 = yearly average and 100 = yearly best.
* Removed the Blom-based field-size correction and the broader standardization framework tied to yearly player-pool size.
* Replaced the linear sum of positive yearly scores with a squared-sum career total, divided by 100, to give more weight to elite peak seasons while still rewarding sustained high-level performance.

# 2026.04.17
* Changed the imputed values from being the median of a given tournament's KPR results, to the mean of a given tournament's KPR results.
