MSD panels 1, 2 and 3 Explant Sup
================
Claire Levy
August 12, 2016

Experiment overview
-------------------

These data are from running MSD analysis of supernatents from selected vaginal explant samples from seven donors. The explants were infected with HSV2 strains 186, SD90 or Mock infected by Lamar Fleming and Gabriella Fenkart and supernatents were collected at 3 timepoints post infection: 3hrs, 8hrs and 24hrs.

We used 3 different MSD panels containing a total of 20 analytes analyzed for 46 samples (see caveat). Based on results from running test samples, we decided to dilute all the supernants 1:5 with MSD's diluent 43 before running the plates. All samples (except 1, see caveats) were run in duplicate.

Caveats
-------

Due to limited sample volume, we had to make the following omissions:

Panel 2: Only 1 rep for sample 324-T2-V1

Panel 3: Did not run samples 324-T2-V1 or 324-T2-V2.

Due to a possible pipetting error, we were not able to use the data from the standards that we ran for panel 1. Instead, we used the standards from a different run of the same panel to calculate concentrations for the experimental samples (see explant\_sup\_README for details).

Checking Standard Recovery and Curves
-------------------------------------

Here are plots of the % recovery (extrapolated concentration/ known concentration x 100) for the standards that were either within or above the detection range, with lines at the "good recovery" limits of 80 and 120% recovery.

The R<sup>2</sup> values for goodness-of-fit for the standard curves were all &gt;0.99

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/standards-1.png)

Caveats about Standards
-----------------------

-   Standards with values *below the detection range* (&lt;2.5x the standard deviation of the lowest standard) give unreliable concentrations, so I did not include those in the plots.

-   When standards are *below the curve fit* (outside the range of the standard curve), the software does not calculate concentrations so you can't get a percent recovery.

-   Most of the Standards that fell into either of these categories were from STD-07 or STD-08 except for two that were STD-06:

<table style="width:53%;">
<colgroup>
<col width="12%" />
<col width="40%" />
</colgroup>
<thead>
<tr class="header">
<th align="center">Sample</th>
<th align="center">Number of Samples Below Fit Curve Range/Detection Range</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="center">STD-06</td>
<td align="center">2</td>
</tr>
<tr class="even">
<td align="center">STD-07</td>
<td align="center">8</td>
</tr>
<tr class="odd">
<td align="center">STD-08</td>
<td align="center">62</td>
</tr>
</tbody>
</table>

Explant Supernatents: Detection Range
-------------------------------------

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/checking%20detection%20range-1.png)

Plots of analyte concentrations
-------------------------------

Black points show the means.

Caveats
-------

Samples omitted from the plots include:

-   Concentrations below the fit curve range. Values cannot be extrapolated when the data was *below* the fit curve range. However,the MSD software can extrapolate values that are *above* the fit curve range if the curve is linear at the top.

-   Samples for which there was only data for a Mock sample and neither of the virus conditions.

Also note: Some of the samples had one rep that was below detection and another that was in range. For these samples I used the remaining "in range" rep as the "average" for that sample.

    ## [[1]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-1.png)

    ## 
    ## [[2]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-2.png)

    ## 
    ## [[3]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-3.png)

    ## 
    ## [[4]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-4.png)

    ## 
    ## [[5]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-5.png)

    ## 
    ## [[6]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-6.png)

    ## 
    ## [[7]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-7.png)

    ## 
    ## [[8]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-8.png)

    ## 
    ## [[9]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-9.png)

    ## 
    ## [[10]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-10.png)

    ## 
    ## [[11]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-11.png)

    ## 
    ## [[12]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-12.png)

    ## 
    ## [[13]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-13.png)

    ## 
    ## [[14]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-14.png)

    ## 
    ## [[15]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-15.png)

    ## 
    ## [[16]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-16.png)

    ## 
    ## [[17]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-17.png)

    ## 
    ## [[18]]

![](MSD_panels_1_2_3_explant_sup_analysis_files/figure-markdown_github/samples%20plots-18.png)
