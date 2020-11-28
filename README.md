# **Amazon_Vine_Analysis**

## **Overview of Project**

I am a data expert at BigMarket, a start-up that helps businesses optimize their marketing efforts. Our client, $ellby, is releasing a large catalog of products on a leading retail website and would like to know how their product reviews compare to their competitors. Additionally, they want to launch a loyalty program that gives complimentary products to select reviewers. Before moving forward, $ellby wants to make sure the return is worth the investment.

I partnered with Jennifer, an account manager at BigMarket to analyze the data and provide a recommendation to the client.

$ellby uses Spark to handle their datasets so we also used it for the project especially since Spark:

    * Runs in stand-alone mode or in the cloud

    * Can be 100xs faster than Hadoop

    * Works with data spread across a cluster or group of computers working together

    * Retains as much memory as HDFS

    * Uses lazy evaluation

To translate the reviews from regular text to machine- readable, we built a Natural Language Processing (NLP) pipeline to break the process into smaller tasks. We explored storage options and got to a place where we could move our Extract, Transform and Load (ETL) process to the cloud and eventually automation.

The client requested full transparency so they can maintain the project in the future. We decided to use Google Colaboratory, a cloud-based notebook to share our work.

*Purpose of Analysis*

After completing our initial $ellby project, I was tasked with analyzing Amazon Reviews of musical instruments left by members of the paid Amazon Vine Program and non-vine members.

### **Results**

Total Reviews 14,537

    o Vine Members 60

    o Non-Vine 14,447

Total Five Star Reviews 8,246

     o Vine Members 34

      o Non-Vine 8,212

Percentage of Five Star Vine Member Reviews 56%

Percentage of Five Start Non-Vine Reviews 57%

#### **Summary**

The analysis shows overall Non-Vine members were more likely to leave a review and the paid review program may not be worth the investment. In fact, the majority of five-star reviews came from Non-Vine members and there was an insignificant different between the five-start review percentages of each group. To further test this theory, we could analyze the lowest star review breakdown. 

If the company would like to have an incentive program, it is recommended the goal should be to simply get buyers to leave a review by randomly awarding prizes. If there is a reason to skew the reviews to be favorable/positive, more prizes can be given to five-star reviews. 
