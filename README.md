# -sim
just testing# Medical addition program in R

cat("Enter first medical value: ")
num1 <- as.numeric(readLines(stdin(), 1))

cat("Enter second medical value: ")
num2 <- as.numeric(readLines(stdin(), 1))

sum_value <- num1 + num2

cat("Total measurement:", sum_value, "\n")

# Install & load ggplot2
if (!require(ggplot2)) install.packages("ggplot2", dependencies = TRUE)
library(ggplot2)

# Ask user for two numbers
cat("Enter first medical value: ")
num1 <- as.numeric(readLines(stdin(), 1))

cat("Enter second medical value: ")
num2 <- as.numeric(readLines(stdin(), 1))

# Calculate sum
sum_value <- num1 + num2
cat("Total measurement:", sum_value, "\n")

# Prepare data for plotting
data <- data.frame(
  Measurement = c("Value 1", "Value 2", "Total"),
  Amount = c(num1, num2, sum_value)
)

# Create ba
