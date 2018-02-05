# module4

> freq <- c(0.6,0.3,0.4,0.4,0.2,0.6,0.3,0.4,0.9,0.2)
> bloodp <- c(103,87,32,42,59,109,78,205,135,176)
> first <- c(bad,bad,bad,bad,good,good,good,good,na,bad)
Error: object 'bad' not found
> first <- c(1,1,1,1,0,0,0,0,NA,1)
> second <- c(0,0,1,1,0,0,1,1,1,1)
> finaldecision <- c(0,1,0,1,0,1,0,1,1,1)
> boxplot(freq,bloodp,first,second,finaldecision)
> boxplot(freq)
> boxplot(bloodp)
> boxplot (first,second,finaldecision)
> boxplot(first)
> boxplot(first)
> boxplot(finaldecision~bloodp)
> boxplot(finaldecision~bloodp,xlab="Blood Pressure",ylab="Final Decision")
> hist(freq,bloodp,first,second,finaldecision)
Error in hist.default(freq, bloodp, first, second, finaldecision) : 
  'probability' is an alias for '!freq', however they differ.
> hist(finaldecision~bloodp,xlab="Blood Pressure", ylab="Final Decision")
Error in hist.default(finaldecision ~ bloodp, xlab = "Blood Pressure",  : 
  'x' must be numeric
> hist(bloodp)
> hist(freq)
> hist(first)
> boxplot(second)
> hist(second)
> boxplot(finaldecision)
> hist(finaldecision)
> Medical Data <- cbind(freq,bloodp,first,second,finaldecision)
Error: unexpected symbol in "Medical Data"
> Medical_Data <-cbind(freq,bloodp,first,second,finaldecision)
> Medical_Data.df
Error: object 'Medical_Data.df' not found
> Medical_Data.df <- data.frame(freq,bloodp,first,second,finaldecision)
> ls()
[1] "bloodp"          "finaldecision"   "first"           "freq"            "Medical_Data"    "Medical_Data.df" "second"         
> Medical_Data.df
   freq bloodp first second finaldecision
1   0.6    103     1      0             0
2   0.3     87     1      0             1
3   0.4     32     1      1             0
4   0.4     42     1      1             1
5   0.2     59     0      0             0
6   0.6    109     0      0             1
7   0.3     78     0      1             0
8   0.4    205     0      1             1
9   0.9    135    NA      1             1
10  0.2    176     1      1             1
> 
