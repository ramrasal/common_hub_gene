- # Specific library
- library(UpSetR)

# Dataset
input <- c(
  Bottleneck = 15,
  Closeness = 15,
  Betweenness = 15,
  EcCentricity = 15,
  "Bottleneck&Closeness" = 11,
  "Bottleneck&Betweenness" = 10,
  "Bottleneck&EcCentricity" = 6,
  "Closeness&Betweenness" = 10,
  "Closeness&EcCentricity" = 10,
  "Betweenness&EcCentricity" = 8,
  "Bottleneck&Closeness&Betweenness" = 10,
  "Bottleneck&Closeness&EcCentricity" = 6,
  "Bottleneck&Closeness&Betweenness&EcCentricity" = 6)

# Plot
upset(fromExpression(input), 
      nintersects = 40, 
      nsets = 6, 
      order.by = "freq", 
      decreasing = T, 
      mb.ratio = c(0.6, 0.4),
      number.angles = 0, 
      text.scale = 1.1, 
      point.size = 2.8, 
      line.size = 1
)
