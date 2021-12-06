## Combating Sex Trafficking: Examining the Spatial Patterns in Urban Hotels in the U.S.

![bg.png]({{site.baseurl}}/bg.png)

### Background
Human trafficking is designated as “the recruitment, transportation, transfer, harboring, or receipt of persons” for improper purposes including forced labor and sexual exploitation using force, kidnapping, fraud or coercion (United Nations, 2019). 

![htmap.png]({{site.baseurl}}/htmap.png)

### Motivation
<strong>Sex trafficking</strong> is human trafficking for the purpose of sexual exploitation, including sexual slavery, child sex tourism, commercial sexual exploitation of children, and prostitution.

![usmap.png]({{site.baseurl}}/usmap.png)

1. In 2018, the Polaris survey with over a hundred selected trafficking victims, 79% of them had contact with the hotel sector while subject to sexual exploitation.
2. According to all the U.S. federal cases from Human Trafficking Institute, over 80% of the of cases indicates that a commercial sex act took place in a hotel. 
With the growth of the internet, traffickers use online advertisements, such as backpage.com or the social media, like Facebook, to solicit customers for conducting sex trafficking.
3. According to the cases, over 84% of the cases that traffickers used online platforms to market the victims and to arrange sex trade with their customers.
With this new way of finding customers, a hotel became a convenient transient locale for the sex trade as customers can meet the victims of sex trafficking often after arranging the appointment online. Therefore, hotels/motels become the hotspots in this kind of illicit supply chain.

Geographical Distribution of Identified Hotels in Sex Trafficking Cases
![hotelmap.png]({{site.baseurl}}//hotelmap.png)

Number of the Identified Hotels with the Corresponding Star Ratings



### Research Questions
How could we identify sex trafficking crimes and prevent them effectively in the academic field of Social and Connected & Community (S&CC)?


1. How do we find the relationship between the patterns of geographic and social boundaries of this crime automatically based on demographic and socio-economic characteristics?

2. What are the significant patterns that we can use to predict and verify the boundaries we have?


### Problem Description

- Sex trafficking is spatially concentrated within the urban environment
 : Criminological theories emphasize the physical and social environment in facilitating crime
  -> Research on influence of situational and social-demographic neighborhood variables is critical

- Opportunity and social disorganization theories explain sex trafficking clusters
 -> Identify neighborhood characteristics associated with sex trafficking activity and its’ spatial dynamics
 
- Spatial patterns observed can guide prevention and disruption efforts

### Data
1. Identified hotel from Federal Civil Case (PACER)
2. Facility Dataset from Hotel.com and Google APIs
3. Demographics & Socio-economic characteristics from U.S. Census and NUMBEO.com (Crime Index)
4. U.S. Primary & Secondary Roads from U.S. Census

![ERD]({{site.baseurl}}//Entity%20Relationship%20Diagram.jpg)

### Method
Analytics Framework: 
![AFrame.png]({{site.baseurl}}/AFrame.png)


- Hotel Patterns
Ownership Status:the ownership status of the hotel or motel (privately owned, part of a chain, a franchise)
Star Rating of the Hotels

- Highway Patterns 
Miles between the identified hotels and the Major Highway Ramps


### Prelimiary Analysis

- Statistic by States
![]({{site.baseurl}}//table.png)

- Dependent Variables
![]({{site.baseurl}}//Dvariable.png)


- Control Variables

![ConVariable.png]({{site.baseurl}}/ConVariable.png)


- Correlation Diagram

![Corre.png]({{site.baseurl}}/Corre.png)


### Results


{% include viz1.html %}

{% include viz2.html %}


### Future Work
Spatial Autocorrelation Analysis

- [Global Spatial Autocorrelation](https://geographicdata.science/book/notebooks/06_spatial_autocorrelation.html):Makes possible statements about the degree of clustering in the dataset

- [Local Spatial Autocorrelation](https://geographicdata.science/book/notebooks/07_local_autocorrelation.html?fbclid=IwAR26zjrUFassWu4N6qeIHpbisp1OsRvboh_KQhSrtK_8Jlz-iOVSbsSi5Mg):Focuses on deviations from the global trend at much more focused levels than the entire maps

![moranI.png]({{site.baseurl}}/moranI.png)


The possible output is choropleth maps and maron plot, which is computed by Moran’s family Index and the other two indexes, which will also be compared.
