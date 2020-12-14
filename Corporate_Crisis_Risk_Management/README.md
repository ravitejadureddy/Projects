# Corporate Crisis Analysis

Every year, we see several companies related but not limited to industries such as Information Technology, Banking, Retail,
Social Networking etc., being hit by corporate crisis. Our curiosity to address the question, Are there any measures
that could help reduce the negative effect of corporate crisis on companies growth and help them save their public relations
led us towards doing this project.

Here, our aim was to find significant variables, that are important for companies for handling corporate crisis situation in a better way.
The primary focus was on analyzing public sentiment towards companies during crisis. This is taken care of using twitter 
public tweets on companies during the time when a major issue surrounded the company and led to effect on its public relation.

Here, we have a file named exploratory data analysis, where operations over data such as fetching twitter tweets through hashtags using scrapping, cleansing the tweets, analyzing the polarity of tweets, differentiating the responses before and after the issue, analyzing tweets on level of issue and company etc., are performed. The file project_details gives data required for exploratory data analysis.

During our exploratory data analysis, we tried to fetch urls of news blogs based on news channel hashtags used in the tweets. Through this we tried to find common keywords from issues about company reported in the newsblogs, that could help us differentiate public tweets on twitter that were pointing towards company crisis issue. This couldn't work because most of tweets posted(related to the company issue by public) were filtered out as these tweets didn't contain keywords(related to the issue) that were obtained through newsblogs. So we identified keywords for the each type of issue and filtered tweets of public that were pointed towards crisis of the company.

For our aim of building model for identifying significant variables, we have build regression models that could with it. For building models with more precision, we have considered issues that were related only to racial and data breach as there were many data points related to these issues and very less data points related to other issues.

Of all the input variables such as reaction time, apology in the reply by companies, informative action in the first reply etc., used to knowing the output variable re(time taken in days for the public sentiment on company to reach same level, for crisis before to crisis after), reaction time(time taken by the company to reply to the public after they have hit crisis) seemed very significant. Variable apology_1(apology in the first reply even though issue was not because of company's mistake) also seemed significant. While all other variables seemed less significant.

Conclusion:

A company if affected through crisis, can help secure their public relations in an early stage of crisis through fast first reply to the public regarding the issue and through apologies in these replies(), even through there were no mistakes from company's end for the rise of crisis issues such as data breach, discriminating advertising commercials etc. The actions(through which the company is going to address the crisis scenario) being stated in the first reply from company representatives is least significant for settling up the crisis.  
