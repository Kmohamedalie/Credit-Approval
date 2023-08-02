# Credit Approval using Xgboost and GridSearch CV
### **Task:** Examples represent positive and negative instances of people who were and were not  granted credit.
### **Dataset available on:** [UCI Machine Learning Credit Approval](https://archive.ics.uci.edu/dataset/27/credit+approval) , [Kaggle](https://www.kaggle.com/datasets/impapan/credit-approval-data-set)

**Developers' Guide:** [Amazon Machine Learning](https://docs.aws.amazon.com/pdfs/machine-learning/latest/dg/machinelearning-dg.pdf#cross-validation)                                             
**Link to the notebook:** [Credit-approval Xgboost](https://github.com/Kmohamedalie/Credit-Approval/tree/master/Notebook)


![image](https://github.com/Kmohamedalie/Credit-Approval/assets/63104472/398e5a9b-360f-4d76-8f33-3d3163961964)


1. Title: Credit Approval

2. Sources: 
    (confidential)
    Submitted by quinlan@cs.su.oz.au

3.  Past Usage:

    See Quinlan,
    * "Simplifying decision trees", Int J Man-Machine Studies 27,
      Dec 1987, pp. 221-234.
    * "C4.5: Programs for Machine Learning", Morgan Kaufmann, Oct 1992
  
4.  Relevant Information:

    This file concerns credit card applications.  All attribute names
    and values have been changed to meaningless symbols to protect
    confidentiality of the data.
  
    This dataset is interesting because there is a good mix of
    attributes -- continuous, nominal with small numbers of
    values, and nominal with larger numbers of values.  There
    are also a few missing values.
  
5.  Number of Instances: 690

6.  Number of Attributes: 15 + class attribute

7.  Attribute Information:

    A1:	b, a. <br>
    A2:	continuous.<br>
    A3:	continuous. <br>
    A4:	u, y, l, t. <br>
    A5:	g, p, gg. <br>
    A6:	c, d, cc, i, j, k, m, r, q, w, x, e, aa, ff. <br>
    A7:	v, h, bb, j, n, z, dd, ff, o. <br>
    A8:	continuous. <br>
    A9:	t, f. <br>
    A10:	t, f. <br> 
    A11:	continuous. <br>
    A12:	t, f. <br>
    A13:	g, p, s. <br>
    A14:	continuous. <br>
    A15:	continuous. <br>
    A16: +,-         (class attribute) <br>

8.  Missing Attribute Values:
    37 cases (5%) have one or more missing values.  The missing
    values from particular attributes are:

    A1:  12
    A2:  12
    A4:   6
    A5:   6
    A6:   9
    A7:   9
    A14: 13

9.  Class Distribution
  
    +: 307 (44.5%) <br>
    -: 383 (55.5%)
