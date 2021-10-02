# Financial-Analysis

#Financial statement analysis task


#Data
revenue <- c(14574.49, 7606.46, 8611.41, 9175.41, 8058.65, 8105.44, 11496.28, 9766.09, 10305.32, 14379.96, 10713.97, 15433.50)
expenses <- c(12051.82, 5695.07, 12319.20, 12089.72, 8658.57, 840.20, 3285.73, 5821.12, 6976.93, 16618.61, 10054.37, 3803.96)

#objectives-
#profit for each month
#profit after tax for each month( tax rate 30%)
#profit margin for each month- equals to profit after tax divided by revenue
#good months- profit after tax greater than mean for year
#bad months -
#best month- profit after tax maximum
#worst month - profit after tax minimum
#study functions- round, mean, max, min

profit<- (expenses - revenue)
profit 

#profit for each month accurate values- 
profit <- (-2522.67-1911.39 3707.79 2914.31 599.92 -7265.24 -8210.55, -3944.97 -3328.39, 2238.65 -659.60
 -11629.54) 
round(profit) 

#profit round off values-
profit_monthly<- ( -2523,-1911, 3708,2914, 600, -7265,  -8211,  -3945,  -3328,  2239, -660, -11630)
profit_monthly
#calculating tax
tax <- (revenue*0.3)
tax

#revenue after tax deduction
revenue_final <- (revenue-tax)
revenue_final

#profit after tax deduction
profit_final <- (expenses- revenue_final)
profit_final

#profit margin <- (profit_final/revenue_final)


#calculate mean profit
mean( profit )

#best month
max(profit_monthly)
max(profit)
#hence 3rd month max profit- best month

#worst month
min(profit)
#hence last month min profit- worst month



