#line graph
library(readxl)
library(ggplot2)
data <- read_excel("nasa-1.xlsx")
ggplot(data, aes(x = time, y = mean_MODISA_L3m_SST_8d_4km_R2019_0_sst)) +
  geom_line(color = "blue") +
  labs(
    title = "Sea Surface Temperature Over Time",
    x = "Date",
    y = "Mean SST (?C)"
  ) +
  theme_minimal()




