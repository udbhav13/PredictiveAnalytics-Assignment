Predictive Modelling - Part2
================
Vikrant Vaidya
8/10/2019

VISUAL STROY TELLING - FLIGHTS AT ABIA

We are going to take a look at the ABIA data from the eyes and interest
of a frequent flyer staying in Austin. As a frequent flyer I would want
to know -

1)  What percentage of flights in and out of Austin are delayed ?
2)  What is the average amount of times by which flights in and out of
    Austin get delayed?
3)  What are the Origin(flights to Austin) and Destination(flights from
    Austin) with the most cancellation blues?
4)  What causes these cancellations ?
5)  What are the airline carriers one should expect most delays with?
6)  Which are the best Origin/Dest to expect pre-time arrival/departures
    to/from Austin ?
7)  Which airports do I expect to spend the maximum time Taxing In and
    Out?
8)  What are the times of the day I should expect the maximum arrival
    and departure delays in/out of Austin?
9)  Are these trends better/worse on some days of the week? Whether I
    could beat this?

But first, PIPING GROUPING AND SUMMARISING the data.

1)  What percentage of flights in and out of Austin are delayed ?

DEPARTURES
![](Question_2_3_files/figure-gfm/unnamed-chunk-3-1.png)<!-- -->

![](Question_2_3_files/figure-gfm/unnamed-chunk-4-1.png)<!-- -->

![](Question_2_3_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->

ARRIVALS
![](Question_2_3_files/figure-gfm/unnamed-chunk-6-1.png)<!-- -->

![](Question_2_3_files/figure-gfm/unnamed-chunk-7-1.png)<!-- -->

![](Question_2_3_files/figure-gfm/unnamed-chunk-8-1.png)<!-- -->

2)  What is the average amount of times by which flights in and out of
    Austin get delayed?

![](Question_2_3_files/figure-gfm/unnamed-chunk-9-1.png)<!-- -->

![](Question_2_3_files/figure-gfm/unnamed-chunk-10-1.png)<!-- -->

![](Question_2_3_files/figure-gfm/unnamed-chunk-11-1.png)<!-- -->

3)  What are the Origin(flights to Austin) and Destination(flights from
    Austin) with the most cancellation blues?

4)  How are these split by the Cancellation Codes?
    ![](Question_2_3_files/figure-gfm/unnamed-chunk-12-1.png)<!-- -->
    ![](Question_2_3_files/figure-gfm/unnamed-chunk-13-1.png)<!-- -->

5)  What are the airline carriers one should expect most delays with?

![](Question_2_3_files/figure-gfm/unnamed-chunk-14-1.png)<!-- -->

6)  Which are the best Origin/Dest to expect pre-time arrival/departures
    to/from Austin ?

![](Question_2_3_files/figure-gfm/unnamed-chunk-15-1.png)<!-- -->

7)  Which airports do I expect to spend the maximum time Taxing In and
    Out?
    ![](Question_2_3_files/figure-gfm/unnamed-chunk-16-1.png)<!-- -->

8)  What are the times of the day I should expect the maximum arrival
    and departure delays in/out of Austin?
    ![](Question_2_3_files/figure-gfm/unnamed-chunk-17-1.png)<!-- -->

9)  Are these trends better/worse on some days of the week? Whether I
    could beat this?
    ![](Question_2_3_files/figure-gfm/unnamed-chunk-18-1.png)<!-- -->

![](Question_2_3_files/figure-gfm/unnamed-chunk-19-1.png)<!-- -->

\#PORTFOLIO MODELLING

PORTFOLIO 1. My Portfolio 1 consists of EFT’s that have more of a global
outlook like.

1.  VT - global reach ETF
2.  ACWX - has a global reach minus the United States
3.  FXI - China focussed ETF

<!-- end list -->

    ## The VAR for this portfolio is  97919.78

PORTFOLIO 2. My portfolio 2 is a safe retirement centric ETF portfolio.
Long time hold with guaranteed yields.

1)  VYM - retirement centric high dividend yield
2)  VGLT - safe ETF with returns on long term
3)  BOND - 3.4% safe yield return
4)  PGX - 5.7% safe dividend returns, risk averse

<!-- end list -->

    ## The VAR for this portfolio is  99969.67

PORTFOLIO 3. My portfolio 3 is a diverse mix porfolio. High risk centric
but higher returns on success too.

1)  VGT - is a tech based ETF with some shares on Amazon too
2)  XLY - is a big $12 Billion consumer fund
3)  XBI - is a high risk ETF with money in a lot of medical startups
4)  VNQ - is a real estate based ETF

<!-- end list -->

    ## The VAR for this portfolio is  97553.1
