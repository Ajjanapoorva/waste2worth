🧩 Week 1 – Design Phase Summary

🧠 Problem Statement

Every day, tons of edible food are wasted in restaurants, households, and food service businesses simply because there’s no efficient system to track and share surplus food. While this perfectly good food goes to waste contributing to resource loss and greenhouse gas emissions, many people in nearby communities still struggle with hunger and food insecurity.
There’s a clear need for a simple, reliable way to connect surplus food sources with NGOs and food banks that can redistribute it to those in need. This project aims to bridge that gap and turn food waste into food support.

💡 Solution Approach

Waste2Worth is a simple, database-driven system that connects people and businesses with extra food to nearby NGOs and food banks that can share it with those in need. It lets restaurants, cafeterias, and households register and log surplus food items with details like name, quantity, and expiry date. The system keeps an updated list of NGOs and food banks, including their locations and contact details, so food can be matched quickly and easily. Every donation and delivery is tracked to keep things transparent and to provide useful insights — like which items are about to expire, how much food each provider donates, and which NGOs receive the most. By streamlining this process, Waste2Worth helps cut down on food waste, supports sustainability, and makes sure good food reaches people instead of ending up in landfills.


🗂️ Dataset Information

Source: Kaggle 
Description: Both datasets together provide structured information about surplus food donors and receivers (NGOs/communities)
Purpose: To enable smart matching of surplus food from donors to suitable receivers (NGOs/food banks) based on location, food condition, and specific requirements, reducing food waste and supporting communities in need.


🧩 Week 2 – Implementation Phase Summary

The system cleans and standardizes donor/receiver data, matches surplus food to nearby NGOs using geolocation logic, and visualizes the results on an interactive map.

🔧 Implementation Steps

Load donor and NGO datasets into Colab.
Clean and standardize the data (IDs, food type, latitude, longitude).
Apply matching logic to pair donors with nearby NGOs.
Generate output showing matched pairs.
Visualize donors, NGOs, and routes on an interactive map.

✅ Results

The system successfully matched donors with the nearest NGOs using geolocation and displayed the outcome on an interactive map. Donors were shown in red, NGOs in blue, and the connection routes in green, proving the matching logic works visually. The model achieved 100% successful matching for all valid location entries, and the output map clearly demonstrated how surplus food can be redirected instead of wasted.
