# Mining-data
Repo for Data Mining Class

## kNN Notes

ML takes features and makes a label for it.

Using those features and labels a computer is able to learn.

Manhattan Distance: Uses grid limiting movement to vertical or horizontal

Euclidean Distance: Lil' Pythagoras regardless of dimensionality

Minkowski Distance: Stupid, but useful formula

​	Takes generals of the first two and applies them for any situation

Just using kNN sometime one of your features can dominate because of the scale. This requires scaling to equalize all features to go from 0-1. Makes features uniform.

### minmax scaling

x = x - xmin / xmax - xmin

This will bring recommendations in line with expectations.

**Sometime k is more than 1 bringing in more alike nearest neighbors**

performs extremely well while being fairly simple.

Used in search engines, genome sequencing, DNA/RNA binning