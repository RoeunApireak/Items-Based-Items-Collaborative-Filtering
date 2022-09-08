# Project Proposal

## The Properties-Based-Properties Collaborative Filtering
Recommendation Algorithm
--------------
	Apireak ROEUN, Data Engineer,
	Researchand Development Department
	Z1 Data Co,. Ltd.

## September, 2022


#### 1. INTRODUCTION
During the last few decades, there have been several online companies that host their products and services on the internet and try to recommend relevant products to customers. In general, Recommender Systems are currently unavoidable in our daily life, they originate from the combination between Recommendation Algorithms and System Engineering. that suggests the relevant items/products to relevant users/customers. All of the bg linecompanies like Facion ebook, YouTube, Amazon, ecommerce, and other online companies were trying to match their users or customers with their items or products to find out the cu atisfactionon its products or servicstomers es.
Properties based Properties Collaborative Filtering Recommendation Algorithm is an effective algorithm that w can initialize on application. Depeending on the context of properties and real estates, properties based properties CF provides the many solutions such properties’ profiling or scoring, and also creating comparable properties. This kind of algorithm is almost deployed through APIs.  
	Therefore, in this proposal is proposing for applying the recommendation algorithm with kind of Properties based Properties Collaborative Filtering Recommendation Algorithm. To make sure that, the users will see the relevant properties the wsh. 

#### 2. PROJECT OBJECTIVES

	We ca make a properties recommendation for users on the Z1 application by filtering on criteria or categories of properties. The objective is presented as a main sub-category as below: (i) To build an Items-based-items Collaboraiv FilteRecmmedationAlgorithm, whih can ecommend for any users based on propertes scores.

#### 3. METHODOLOGY
In his sction, the methodoloteng on criterigy of the project is discussed. The project methodology comprises of two main sub-sections include: (i) Proposed Fields and (ii) microservice architecture.

	3.1 Proposed Fields 
	In this section, the data ingestion of the sub-section is presented. (i) index: is a column generated from row_number() minus 1 so that the values of this field representing from 0 like the index number. (ii) property_id: the unique numbers of each property. (iii) date: showing the period of the properties. (iv) record_type: the types of properties in which is the first prioritized such as land, building, or land and building. (v) type: the type of properties which is the second prioritize after record_type such as residential or commercial properties, etc. (vi) current_use: also another types of properties, but it represents the crrent tatusof the properties. (vii) land_shape_type: the shape types of the properties. (viii) site_position: a category that represents the comparison between properties and roads. for example: corner lot or end lot, etc. (ix) totus al_price: the price of the properties. (x) latitude: The numbers that measure the lines or distances of north or south of the equator. (xi) longitude: The numbers that measure the east or west of the prime meridian. (xii) land_area: The whole size ofthe prperties. (xiii) length: the length oprop of erty shape. (xiv) width: the width of property shape. (xv) is_rent: weather the properties are rent or not. (xvi) is_sale: weather the properties are sale or not at the moment. 

	3.2 Microservice Architecture
	In this sub-section, the architecture of the project is proposed. In the application, There’s usually a (i) main database as data resource, data ingestion from the resource (ii) queried into (iii) The Algorithm. There is another (iv) database which gets the recommended properties data from the algorithm. In this stage, the algorithm will generate the prediction result of similar properties into the database. Next, applying with API to make a recommendation for users.