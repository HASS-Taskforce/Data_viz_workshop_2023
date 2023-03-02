# 1. Data visualisation basics 
## What is data? (Participative activity adapted from ['Future Proof and FAIR Research Data: Open Data Management Best Practices and First Steps'](https://www.fosteropenscience.eu/node/2603))(45 mins)

* Form groups (can be randomly allocated using a survey tool) and discuss:
 - In your discipline, what are research data?
 - How do they look like?  
 - How can you interpret them?
 - Share results and discuss as a group
* Humanities, Arts and Social Sciences (HASS) research produces and work with data  
* These can take many forms (i.e. discussion outcomes)
* HASS research involves **enrichment** of data where layers of interpretation are added to original content: the value of annotations.
* Need to identify original (primary) and secondary data i.e. text anotation on work or corpora.

## The importance of visual representation
* Visual representation is the key activity of data visualisation
* Visuals help researcher to communicate results and/or research journey.
* Comprenhension of results and rationale by broader public. From knowledge to comprenhension.

## Informing Vs communicating: From perception to comprenhension
* Perception, interpretation, comprenhension

![from perception to comprenhension](https://github.com/HASS-Taskforce-University-of-Melbourne/Data_viz_workshop_2023/blob/da7346481c2fe67a05d5e47f8f3183ea0f0513ee/perceiving_comprehending.png)

| Perceiving                                |Interpreting                                         |Comprenhending        |
|-------------------------------------------|-----------------------------------------------------|----------------------|
|Visualisation being used                   |Interesting features, shapes, patterns or connections|What has been learnt? |
|Items represented by marks                 |Expected/unexpected features                         |What feelings have been stirred?                  |
|Range of displayed values                  |Relevant features given the subject                  |What can be done with new knowledge                  |
|Are data and representation *trustworthy*? |                                                     |                  | 

### Perception to comprenhension: A visual journey

Some real data to begin our discussion

[The Box Office Mojo by IMDPro](https://www.boxofficemojo.com/weekend/2023W01/?area=AU&ref_=bo_wey_table_7) an open dabase of movie releases and box office revenue.

![From BOM to Excel with the help of Python](Artboard 1.png)

![Perception](mov_fig_1.png)
* What features are observable?
* Where are the largest, mid-sized and smallest values?
* Where are the most and the last?
* Where is the _average_?


![Interpretation aided by design](mov_fig_2.png)
* Are more features perceivable?


![Drawing interpretations helped by extra knowledge](mov_fig_3.png)
* What features are interesting?
* What features are unexpected?
* What features are important given the context?

![Comprenhending by providing further info](mov_fig_4.png)
* What has been learnt?
* Has the experience had an impact emotionally?
* What does one do with this information?

 ## Visual encoding: marks and attributes
 * Marks represent items of data (lines, points, shapes) *not* their value
 * Attributes visual variations of marks (colour, size, position) that describe the *value* associated with a particular marker.

## The design process 
* There is no perfect visualisation, but many ways to do the same task.

### Principle of proportional ink
 **Attributes must be proportional to the data values represented.**
    ![Breaking the principle](mov_fig_5.png)
     Problems with this figure?
    
    ![Why is the principle important?](mov_fig_6.png)


### Overlapping points
* Arises when data has low resolution: the scale used to measure our data is too large so individual observations are hard to tell appart from each other.
* Data points will have the same value even if they represent different entities or events.

**The data**
The Early English Books Online database ((EEBO)[https://www.proquest.com/eebo]) contains digital samples of almost every work printed in English from 1470 to 1700.
![EEBO sub-sample](EEBO_plot_no_jitter.png)

* Problems with this visualisation?

A first solution: Displacing each point randomly by a little amount so that individual points become visible or _jitter_
![EEBO jitter](EEBO_plot_jitter.png)

Careful! too much jitter can also affect the integrity of the visualisation. 
![EEBO too much jitter](EEBO_plot_too_jitter.png)

### Context to facilitate comprehension

* Each visualisation requires different solutions to work, but there are some minimum requirements to improve communication with audience

**The data**
[A report published in 2011 by The Economist](https://www.economist.com/graphic-detail/2011/12/02/corrosive-corruption) revealed a correlation between corruption and development based on Transparency Interantional Corruption Perception Index and the UN's Human Development Index (HDI). Here we updated this report using data from 2012 to 2017 compiled by [Gapminder](https://www.gapminder.org/data/).

## Legends and axis labels
* Every figure needs a title conveying to the reader what the visualisation is about.
* Legend help readers to identify marks and attributes easily. 
* Axis labels give to reader a sense of time (days, months, years, centuries), magnitude (hundrends, thousands, millions), unit (for physical attributes), or orientation (North, South, East, West).


## Context and annotations
* Help reader going from perception to comprenhension.
* Makes comparisons possible and the identification of extreme cases
* Puts data into a broader context

## Captions and placement of titles
* Where is the visualisation going to be presented: print Vs. display
* 

 ## The grammar of graphics
 
 # 2. Data types and a directory of visualisations
 
 ## Static, interactive and animated visualisations
 ## Structured and unstructured data types (text, numbers, images)
 ## CHRTS: the principal families of chart types for visualising quantitative data
   - Categorical
   - Hierarchical
   - Relational
   - Temporal
   - Spatial


 ## Gallery of visualisations
   - Bars
   - Scatter plots
   - Maps
   - Network diagrams
 
 ## What is the best plot for my data?
 
 # 3. Colour theory and digital colour palettes
 ## Human colour vision and the computer red, green and blue (RGB) system: properties of colour and how they are represented
   - Colour names, RGB and hex notation to define colours
 ## Colour blindness and design principles for inclusive visualisations
 ## Choosing colour palettes to facilitate visual encoding
   - Qualitative, sequential and diverging colour palettes
 
 # 4. Common visualisation pitfalls
 ## Colour use
 ## Unnecessary use of 3-D
 ## Understanding your audience
 
 # 5. Tools for making visualisations
 ## Coding Vs. no-coding solutions
 ## Tools with buttons, menus and a graphical user interface: Excel, Kepler, Gephi
 ## Python or R: Choosing the right tool for the job
