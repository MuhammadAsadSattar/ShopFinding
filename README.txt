-------------------------------- ####### Shop Finding and Navigation System ####### -----------------------------
Description:
A Python program called the Shop Finding and Navigation System is made to help customers identify stores based on their categories, access store information, and arrange stores according to user ratings in each category.
Files: 
The Shop Finding and Navigation System is built on top of this fundamental Python script. The 'ShopHashTable' class, which manages the hash table used to store shop data, is one of its features. Additionally, this script provides example shop data, which makes testing and display easier.
Dependencies:
The Shop Finding and Navigation System don’t rely on any additional third-party Python 3.x dependencies or libraries in addition to the Python standard library. It is a standalone Python application that simply makes use of the language's pre-built modules and functions. As a result, installing any external Python dependencies is not required in order to run the application.
The following Python libraries are used by the Shop Finding and Navigation System:
1. networkx: Used to build, manage, and carry out operations on the directed graph that represents the relationships between shops.
2. Matplotlib: Used to show and visualize the directed graph.
How to Run:
1.	Download the repository to your computer by using the command git clone https://github.com/MuhammadAsadSattar/ShopFinding.git
2. Go to the project directory using the command: cd shopfinding
3. Start the software.
4. To use the Shop Finding and Navigation System, follow the on-screen instructions.
 
Features:
- Shop Data Management: The system effectively organizes data pertaining to different stores in a shopping district. Each store is identifiable by a special shop number, which also includes information about the store's name, category, location, and rating.
- Hash Table: To swiftly organize and access shop data, the system makes use of a hash table. It allows for quick search based on categories by storing shop categories as keys and references to the related shops as values.
- Instant Shop Search: Users may quickly look up stores by selecting a category. The hash table is used by the system to quickly collect and show information about stores that fit the chosen category.
- Real-Time Updates: As new shops are added, old shop data is edited, or shops are withdrawn, the hash table is immediately updated. This guarantees that search results are always precise and current.
- Shop Ratings Management: Using a max-heap data structure, the system has a rating management capability. Based on their ratings, users may see and sort the stores within each category.

Usage: Use the category search feature to find the stores you're looking for quickly.
- View comprehensive store details, such as the name, address, and star rating.
-Utilizing the effective max-heap data structure, sort stores by ratings within each category.

The Shop Finding and Navigation System, which enables users to manage shop data, search for shops, and examine top-rated businesses within particular categories, is covered in this usage guide's fundamental features and functions.

Sample Data: 
Test data is used to evaluate if a program is being executed correctly. It is simple to alter and add to the sample store data that is given when you test the system with data from your own shop.

Author:
Name: Asad Sattar
asadsattar1092@gmail.com
