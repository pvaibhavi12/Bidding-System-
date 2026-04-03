# Bidding-System
This project is a Bidding System built using MySQL, HTML, CSS and Python (Flask) to manage and simulate an auction-style environment. It allows users to place bids on items, track highest bids, and maintain structured records of users, products, and transactions.

The system demonstrates database design concepts such as relationships, constraints, indexing, and efficient querying.

🚀 Features
User registration and management
Item/Product listing for bidding
Real-time bid tracking (highest bid logic)
Bid history maintenance
Auction status management (open/closed)
Data integrity using constraints and relationships
🛠️ Tech Stack
Database: MySQL
Language (optional if used): MYSQL 
🗂️ Database Schema

Key tables included in the system:

Users
user_id (PK)
name
email
password
Items
item_id (PK)
item_name
description
starting_price
auction_end_time
Bids
bid_id (PK)
user_id (FK)
item_id (FK)
bid_amount
bid_time
🔗 Relationships
One user can place multiple bids
One item can have multiple bids
Each bid is linked to a specific user and item
⚙️ How It Works
Users register and log in
Admin or users list items for auction
Users place bids on items
System updates the highest bid dynamically
Auction closes after the specified time
Highest bidder wins the item
