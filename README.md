# Medium Outlets Will Outperform Large Outlets
## Data shows Medium-sized outlets are projected the top performers in sales metrics

**Andrew J Cafiero**: 

### Business problem:

Of the various grocery outlets within the company, those that classify as "medium-sized" will continue to perform better in reference to sales when compared to those that are classified as "Small" and "Large".

### Data:
The data utilized was provided from a third-party source and was cleaned in order to find a more accurate representation of sales figures across the company.

## Methods
- Seeing there was a lot of excess data within the dataset, I chose to drop several of the categories that would not apply to an in-depth look at sales metrics.
- Some of the more applicable categories such as Outlet Size itself had some discrepancies in labeling (ie: 'High' in place of 'Large')
- Looking to see which categories would give the best insight into sales metrics, visualtions of the data were created to help align some of the intersecting factors such as Total Sales figures for each classification of outlet size, and how the listed price of each item impacted the Total sales of each individual outlet.
- Using these graphs as a reference, processing the data through algorithms allowed me to see how much margin existed between the actual sales figures themselves when impacted by some of the various categories present in the dataset.

## Results
When evaluating the information provided from our visualizations, it can be seen that not only do the medium-sized outlets perform better on average compared to small and large counterparts, there are higher instances of specific products selling very well at medium-size stores. 

#### Visual 1 Title
![Outlet Size plot](https://user-images.githubusercontent.com/103779074/170774042-51d732a4-8ce9-46d6-b438-1a1163680c78.png)

Though the margin of difference between medium and large-sized stores is seemingly small, the prominent factor in their impact stems from products doing exceedingly better when in medium-sized locations.

#### Visual 2 Title
![Outlet sales vs MRP](https://user-images.githubusercontent.com/103779074/170774108-3347ff1d-a179-4478-a439-0d214aaafa7e.png)

To give further weight to how crucial specific product sales are when looking at the bigger picture, this visual allows to see that items with lower listed MRP drive the bulk of sales within the company overall.

## Model

The most important metrics found within the model was the root mean squared error that was created thanks to some machine learning. When initiated it could be seen that the RMSE margins of sales in our Linear Regression model, using the same dollar values also used in the data set, were closely correlated; $1140.73 in our Training set but $1088.77 in our Testing set.

## Recommendations:

My recommendation is for the company to seek out which stores are underutilzing the various categories within their own store such as the MRP of certain items, and maybe maximizing the visibility of items that have been shown to perform better in more successful stores.

## Limitations & Next Steps

Some limitations present in this research were indicators such as geographic location and # of people who frequent the stores. This would allow for further breakdown as to how to identify stores that are perhaps doing well in relation to how populated their geographic area is. Some next steps would be to collect said data and also do further research and analysis of how factors like Item Visibility or Item Type impact the sales of stores within the company. Additionally and as stated earlier, taking extended time to fine tune the research already presented would allow the company to have a more definitive figure as to utilizing Store Size as a key feature.


### For further information

For any additional questions, please contact ajcafiero58@gmail.com or via my LinkedIn profile located at https://www.linkedin.com/in/acafiero/
