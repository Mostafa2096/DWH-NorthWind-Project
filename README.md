# DWH-NorthWind-Project
# Project Amusement Park 🎢🎡🎠

Welcome to our Data Warehouse (DWH) project! Below, you'll find a thrilling journey through the steps we've taken, complete with amusing icons to guide you along the way.

## 🚀 Project Milestones

### 1. Defining Business Processes
We've delved deep into the heart of our operations, uncovering the secrets that drive our organization's daily adventures.

### 2. Defining Granularity for the Analysis Scope
Establishing the level of detail in our analysis scope, ensuring that every twist and turn in our data is captured with precision.

### 3. Defining Dimensions for Analysis Context
Navigating through the dimensions of our data universe, discovering the realms where insights dwell.

### 4. Defining Facts and Measurements
We've measured the immeasurable, transforming raw data into golden nuggets of insight.

### 5. Data Warehouse Modeling (Defining the Schema)
Blueprints drawn, the architecture of our data kingdom laid bare for all to behold.

### 6. Physical Model Implementation
Bringing our data castle to life in the digital realm, one table at a time, with the magic of PostgreSQL and PGAdmin.

### 7. Data Warehouse Indexing
Equipping our data fortress with the finest indexing spells to ensure lightning-fast access to treasures untold.

### 8. Generating & Populating the Data
Breathing life into our data kingdom with the lifeblood of information, extracted, transformed, and loaded from the NorthWind database.

### 9. Writing SQL Queries to Gain Business Insights
Unleashing the power of SQL sorcery to extract wisdom from the depths of our data lake, illuminating the path to informed decisions.

## 📊 Tables Overview

### 1. Definition of Business Process 📦
- 🛒 The customer orders products from our company, embarking on a journey filled with excitement and anticipation.
- 🎉 Occasional promotions and discounts add a sprinkle of magic to the adventure.

### 2. Definition of Granularity 🔍
- The granularity of our fact table is as fine as a single product per order, capturing every detail of the quest.

### 3. Dimensions 🌐

#### DimCustomer 🧑‍🤝‍🧑
Comprehensive customer profiles await, filled with tales of their adventures and contact details.

#### DimDate 📅
A calendar of events, where every day holds a new story waiting to be told.

#### DimPromotion 🎁
Unlock the secrets of promotions past, present, and future, and their impact on our grand tale.

#### DimShipper 🚚
Navigate the seas of shipping with detailed shipper information at your fingertips.

#### DimSupplier 🏭
Journey to the realms of our suppliers, where treasures of inventory management await discovery.

#### DimProduct 📦
Discover the wonders of our product kingdom, from the humblest trinket to the grandest artifact.

#### DimProductPrice 💰
Uncover the secrets of pricing history, where every change tells a story of strategy and value.

#### DimTerritory 🗺️
Chart the lands of our sales territories, where regional performance meets geographical intrigue.

#### DimEmployee 👩‍💼
Meet the heroes behind the scenes, with detailed employee profiles and their ever-evolving roles.

#### DimEmpTerritory 🌍
Forge alliances between employees and territories, shaping the destiny of our sales empire.

#### DimPayMethodSaleChannel 💳
Navigate the channels of commerce, where payment methods and sales channels intertwine.

### 4. Fact Table 📊

#### Why Only One Fact Table? 🤔
- We've chosen to wield a single fact table, streamlining our quest for performance and efficiency.

#### What is the Grain? 🌾
- Each order fact is as intricate as every product within it, capturing the essence of each transaction.

#### What are the Foreign Keys (FKs)? 🔑
- Foreign keys unlock the doors to contextual insights, adding depth to our measurements.

#### What are the Measurements? 📏
- From shipping durations to profits earned, every metric paints a vivid picture of our adventures.

So, strap in and get ready for an exhilarating journey through the data realms, where insights await at every turn! 🎢✨
