## Combating Sex Trafficking: Examining the Spatial Patterns of Hotels in the U.S. Urban Areas

### background
Human trafficking is designated as “the recruitment, transportation, transfer, harboring, or receipt of persons” for improper purposes including forced labor and sexual exploitation using force, kidnapping, fraud or coercion (United Nations, 2019). 

![bg.png]({{site.baseurl}}/bg.png)

### Motivation
<strong>Sex trafficking</strong> is human trafficking for the purpose of sexual exploitation, including sexual slavery, child sex tourism, commercial sexual exploitation of children, and prostitution.

![usmap.png]({{site.baseurl}}/usmap.png)

1. In 2018, the Polaris survey with over a hundred selected trafficking victims, 79% of them had contact with the hotel sector while subject to sexual exploitation.
2. According to all the U.S. federal cases from Human Trafficking Institute, over 80% of the of cases indicates that a commercial sex act took place in a hotel. 
With the growth of the internet, traffickers use online advertisements, such as backpage.com or the social media, like Facebook, to solicit customers for conducting sex trafficking.
3. According to the cases, over 84% of the cases that traffickers used online platforms to market the victims and to arrange sex trade with their customers.
With this new way of finding customers, a hotel became a convenient transient locale for the sex trade as customers can meet the victims of sex trafficking often after arranging the appointment online. Therefore, hotels/motels become the hotspots in this kind of illicit supply chain.

### Research Questions
1. How do we find the relationship between the patterns of geographic and social boundaries of this crime automatically based on demographic and socio-economic characteristics?

2. What are the significant patterns that we can use to predict and verify the boundaries we have?

### Problem Description

![htmap.png]({{site.baseurl}}/htmap.png)


- <strong>Sex trafficking is spatially concentrated within the urban environment</strong>
 : Criminological theories emphasize the physical and social environment in facilitating crime
  -> Research on influence of situational and social-demographic neighborhood variables is critical

- <strong>Opportunity and social disorganization theories explain sex trafficking clusters</strong>
 -> Identify neighborhood characteristics associated with sex trafficking activity and its’ spatial dynamics
 
- <strong>Spatial patterns observed can guide prevention and disruption efforts</strong>

### Data
1. Identified hotel from Federal Civil Case (PACER)
2. Facility Dataset from Hotel.com and Google APIs
3. Demographics & Socio-economic characteristics from U.S. Census and NUMBEO.com (Crime Index)

![ERD.png]({{site.baseurl}}/ERD.png)

<hr>
### Research Methods
- Spatial Autocorrelation Analysis
  : Global Spatial Autocorrelation: Makes possible statements about the degree of clustering in the dataset
- Point Pattern Analysis: Focuses on deviations from the global trend at much more focused levels than the entire maps
  : Concerned with the visualization, description, statistical characterization, and modeling of point patterns, trying to understand the generating process that gives rise and explains the observed data
   1. What does the pattern look like?
   2. What is the nature of the distribution of points?
   3. Is there any structure in the way locations are arranged over space? That is, are events clustered? or are they dispersed?
   4. Why do events occur in those places and not in others?

![mIndex.png]({{site.baseurl}}/mIndex.png)


- Proposed Workflow

![workflow.png]({{site.baseurl}}//workflow.png){:height="300" width="1000"}



### Finding

![hotelmap.png]({{site.baseurl}}//hotelmap.png)

### Resources

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/avecjini/jekyll/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
