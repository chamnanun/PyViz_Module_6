# PyViz_Module_6
# HW Assignment - PyViz

## Questions:

1) What’s the overall trend in housing units over the period that you’re analyzing?

    According to the bar chart above, housing prices in San Francisco reflects a gradual increases year-over-year between the periods of 2010 and 2016. While the chart may indicates some stability, the year-over-year comparison does actually increase directionally when you look at the actual means.


2) What is the lowest gross rent reported for the years included in the DataFrame?

    According to the table, the lowest gross rent occurred in 2010 with a mean gross rent of $1,239.

3) Did any year experience a drop in the average sale price per square foot compared to the previous year?

    No. The line chart above indicates that sale price per square foot rose sizeably between 2010 through 2016.

4) If so, did the gross rent increase or decrease during that year?

    Sale price per square foot increases outpaced gross rent. The line chart above reflects the notable variation in the mean with the slope of sale price growing more rapidly than gross rents.

5) For the Anza Vista neighborhood, is the average sale price per square foot for 2016 more or less than the price that’s listed for 2012?

    The Anza Vista neighborhood experience a decline in square foot in 2016 as compared to 2010.

6) Which neighborhood has the highest gross rent, and which has the highest sale price per square foot?

    The highest gross rent is attributed to Westwood Park as represented to by the darker shades of the color blue.

7) How does the trend in rental income growth compare to the trend in sales prices? Does this same trend hold true for all the neighborhoods across San Francisco?

    No. Rental income growth has not grown as the same rapid ascent as the sales per square foot.

8) What insights can you share with your company about the potential one-click, buy-and-rent strategy that they're pursuing? Do neighborhoods exist that you would suggest for investment, and why?

    This would not be an avenue I would advise to pursue, especially given the uncertainity in today's commercial and residential real estate market. Companies such as Zillow tried the one stop online buying approach a couple years ago. However, Zillow has since taken significant losses and has even terminated their online buying presence and as result downsized their teams. If you are not an investor residing in the area and have no local experience, I wouldn't be an advocate for one click buying or investing as the local knowledge on property characteristics and trends are extremely important to understand when deploying liquid funds for hard assets. 
    
    For example within the commercial real estate space,  take a look at the office space today with hybrid work environments. Many companies are terminating their commercial leases.  Most notably, office properties are at a all time high for overall vacancies. Within the investing space, this data does not provide length of time the existing tenant/resident has historically been in the property or their intentions to renew. Additionally, it doesn't provide maturity dates of leases to understand whether the leases are either long-term or short-term.  These factors combined would preclude me from not wanting to pursue this channel.  


### Source Code Citing:

Received assitance from BCS Support surrounding Question #5. Clarity was needed on the source code involving widgits and the "groupby" function for neighborhoods. Specifically as it relates to the following code below: 

prices_by_year_by_neighborhood = sfo_data_df.groupby(['year', 'neighborhood']).mean()
