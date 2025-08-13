# -sim
just testing# Medical addition program in R

cat("Enter first medical value: ")
num1 <- as.numeric(readLines(stdin(), 1))

cat("Enter second medical value: ")
num2 <- as.numeric(readLines(stdin(), 1))

sum_value <- num1 + num2

cat("Total measurement:", sum_value, "\n")

