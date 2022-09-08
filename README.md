# Project Proposal

## The Properties-Based-Properties Collaborative Filtering Recommendation Algorithm

Apireak ROEUN, Data Engineer,

Researchand Development Department

Z1 Data Co,. Ltd.

## September, 2022

#### 1. INTRODUCTION
During the last few decades, there have been several online companies that host their products and services on the internet and try to recommend relevant products to customers. In general, Recommender Systems are currently unavoidable in our daily life, they originate from the combination between Recommendation Algorithms and System Engineering. that suggests the relevant items/products to relevant users/customers. All of the big companies like Facebook, YouTube, Amazon, ecommerce, and other online companies they were trying to match their users or customers with their items or products to find out the customer satisfactionon on its products or services. 

Properties based Properties Collaborative Filtering Recommendation Algorithm is an effective algorithm that we can initialize on application. Depending on the context of properties and real-estates, properties based properties CF provides the many solutions such properties’ profiling or scoring, and also creating comparable properties. This kind of algorithm is almost deployed through APIs.  

Therefore, in this proposal is proposing for applying the recommendation algorithm with kind of Properties based Properties Collaborative Filtering Recommendation Algorithm. To make sure that, the users will see the relevant properties they wish to see. 

#### 2. PROJECT OBJECTIVES

We can make a properties recommendation for users on the Z1 application by filtering on criteria or categories of properties. The objective is presented as a main sub-category as the following: (i) To build an Properties-based-Properties Collaborative Filtering Recommendation Algorithm, that can recommend for any users based on properties scores.

#### 3. METHODOLOGY
In this sction, the methodology of the project is discussed. The project methodology comprises of two main sub-sections include: (i) Proposed Fields and (ii) microservice architecture.

3.1 Proposed Fields 

In this section, the data ingestion of the subsection is presented. (i) index: is a column generated from row_number() minus 1 so that the values of this field representing from 0 like the index number. (ii) property_id: the unique numbers of each property. (iii) date: showing the period of the properties. (iv) latlong: is the measurement numbers of latitude and longitude of the land or building. (v) record_type: the types of properties in which is the first prioritized such as land, building, or land and building. (vi) type: the type of properties which is the second priority after record_type such as residential or commercial properties, etc. (vii) current_use: also another types of properties, but it represents the current status of the properties. (viii) land_shape_type: the shape types of the properties. (ix) site_position: a category that represents the comparison between properties and roads. for example: corner lot or end lot, etc. (x) length_range: the range of the properties length. (xi) width_range: the range of the properties width. (xii) is_rent: wheather the properties are opening for rent or not. (xii) is_sale: wheather the properties are opening for sale or not at the moment. (xiii) is_apprasial: wheather the properties are evaluated or not yet. (xiv) address1: is almost about provinces, cities, or Districts. (xv) address2: is almost about districts or communes of the addresses. (xvi) address3: is almost about villages or communes. 

3.2 Microservice Architecture 

In this subsection, the architecture of the project is proposed. In the application, There’s usually a (i) main database as data resource, data ingestion from the resource (ii) queried into (iii) The Algorithm. There is also another (iv) database which gets the recommended properties data from the algorithm. In this stage, the algorithm will generate the prediction result of similar properties into the database. Next, applying with API to make a recommendation for users.