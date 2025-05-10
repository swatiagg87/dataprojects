**Project Objective**\
The goal of this project is to analyze survey data from drivers to
identify key demographic, behavioral, and contextual variables that
influence coupon acceptance behavior.\
\
**Data Cleaning & Preprocessing**

-   The variable **`car`**, which contained over **99% missing values**,
    was removed due to its irrelevance to coupon acceptance behavior.

-   **74 duplicate records** were identified and removed to ensure data
    integrity.

-   Categorical variables such as `CoffeeHouse`, `Restaurant20To50`,
    `CarryAway`, `RestaurantLessThan20`, and `Bar` had **1--2% missing
    values**. Imputation using the mode (most frequent value) was
    considered but ultimately not performed, as the low missing rate and
    categorical nature of the variables were not expected to materially
    affect the analysis.\
    \
    **Bar Coupon Analysis**

```{=html}
<!-- -->
```
-   The **acceptance rate for bar coupons** is **41%**, which is
    **significantly lower than the overall coupon acceptance rate of
    57%**.

-   Further segmentation reveals:

    -   Drivers who visit bars **more than three times per month**
        exhibit **significantly higher acceptance rates**.

    -   Even **occasional bar-goers (≥1 visit/month)** have an elevated
        propensity to redeem coupons compared to non-visitors.

    -   **Drivers aged 25--30** are more likely to accept bar coupons,
        suggesting age as a potential influencing factor.

    -   **Absence of children** correlates with higher acceptance
        likelihood.

    -   **Occupation in farming** shows a positive relationship with
        coupon redemption.

    -   **Having a partner** also positively impacts acceptance
        probability.\
        \
        **Carry-Out & Takeaway Coupon Insights**\
        Given that the **Carry-Out & Takeaway** category exhibits the
        **highest acceptance rate**, further exploratory analysis was
        conducted for this segment. Key findings include:

```{=html}
<!-- -->
```
-   Redemption rates are **higher during sunny weather conditions**.

-   Usage peaks around **2 PM**, indicating a lunchtime preference.

-   There is an **increase in redemption likelihood as the coupon
    expiration date approaches**.

-   **Age** does not significantly affect carryout coupon
    usage---acceptance is **uniform across age groups**.

-   **Widowed women** are more likely to redeem these coupons than
    individuals of other marital statuses.

-   **Men** have higher redemption rates than women for carryout
    coupons.

-   Certain occupations, such as **Building & Grounds Maintenance**,
    **Protective Services**, **Health Care Support**, and **Construction
    & Extraction**, are associated with higher carryout coupon
    acceptance.

-   **High school graduates** demonstrate higher acceptance than those
    with other education levels.

-   Drivers accompanied by a **friend** as a passenger are more likely
    to redeem carryout coupons.\
    \
    **Next Steps & Recommendations**

```{=html}
<!-- -->
```
-   Conduct a **quantitative uplift analysis** to measure the marginal
    increase in coupon acceptance associated with each identified
    predictor across coupon categories.

-   Develop a **targeted coupon distribution strategy** that balances
    overall offer volume with acceptance rate optimization.

-   Although **Coffee House coupons** have broader distribution, their
    acceptance rate is lower than that of **Carry-Out & Takeaway**.
    Consider adjusting distribution efforts based on **demographic
    targeting** to improve efficiency and engagement.

-   Implement **segmentation models** to personalize coupon offers and
    avoid underrepresentation of specific coupon types or customer
    segments.
