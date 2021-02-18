
[![Financial Statement Analysis](https://seofiles.s3.amazonaws.com/seo/media/cache/d7/98/d7986879885f791ec409c90fd871d664.jpg "Financial Statement Analysis")](https://seofiles.s3.amazonaws.com/seo/media/cache/d7/98/d7986879885f791ec409c90fd871d664.jpg "Financial Statement Analysis")

---

# **Problem Statement**

As part of this project we are considering two lists of monthly revenue and monthly expenditure to calculate the profit or loss for the given financial year for a company.  Below are the tasks that are performed on the data
financial metrics:

- profit or loss for each month
- profit or loss after tax for each month (the tax rate is 20%)
- profit margin for each month - equals to profit after tax divided by revenue
- good months - where the profit after tax was greater than the mean for the year
- bad months - where the profit after tax was less than the mean for the year
- the best month - where the profit after tax was max for the year
- the worst month - where the profit after tax was min for the year
---

# **Solution Items**
## **profit or loss for each month**
```
# Calculating Profit for each month 
profit_before_tax = []
for i in range(len(revenue)):
    #print('Profit for month {0} is {1}'.format(i, round(revenue[i] - expenses[i],2))) 
    profit_before_tax.append(round(revenue[i] - expenses[i],2))
# Calculating profit before tax deduction
#print('------------------------------------------------------------------------------------')
print('Profit for the year before tax deduction is: ', profit_before_tax)
print('------------------------------------------------------------------------------------')
```

## **profit or loss after tax for each month**
```
# Calculating profit after tax deduction 
# tax rate is 20 %
profit_after_tax = []
profit_margin = []
profit_mean = 0
for i in range(len(revenue)):
    profit_after_tax.append(round(profit_before_tax[i] *0.8, 2))
    profit_margin.append(round(profit_after_tax[i] / revenue[i], 2))
profit_mean = round(sum(profit_after_tax) / 12, 2)

```

## **Good and Bad months**
```
# Finding good and bad months
good_month = []
bad_month = []
for i in range(len(c)):
    if profit_after_tax[i] >= profit_mean:
        print('{0} is a good month and profit margin is {1} $'.format(month[i], round(profit_after_tax[i] - profit_mean), 2))
    else:
        print('{0} is a bad month and has a loss of {1} $'.format(month[i], round(fabs(profit_after_tax[i] - profit_mean)), 2))
```

## **Best and Worst months**
```
# Finding best and worst months
best_month = max(profit_after_tax)
worst_month = min(profit_after_tax)
for i in range(len(revenue)):
    if profit_after_tax[i] == best_month:
        print('{0} is the best month with a profit of {1} $'.format(month[i], best_month))
    if profit_after_tax[i] == worst_month:
        print('{0} is the worst month with a loss of {1} $'.format(month[i], fabs(worst_month)))
```
---
