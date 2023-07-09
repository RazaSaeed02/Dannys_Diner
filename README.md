# Dannys_Diner

#### An analysis for a local diner about customer visiting patterns, how much money they spent, and which menu items were their favourite.

### Tools Used
- SQL (Structured Query Language)
- Jupyter Notebook

### Questions Answered
1. What is the total amount each customer spent at the restaurant?
2. How many days has each customer visited the restaurant?
3. What menu item did each customer order first?
4. What is the most purchased item on the menu and how many times was it purchased by all customers?
5. Which menu item was the most popular for each customer?
6. After a customer became a member, which menu item did they order first?
7. What was the last item a customer ordered before they became a member?
8. What is the total number of items ordered and amount spent for each member before they became a member?
9. If each $1 spent equates to 10 points and sushi has a 2x points multiplier — how many points would each customer have?
10. In the first week after a customer becomes a member (including their join date) they earn 2x points on all items (not just sushi). How many points do customer A and B have at the end of January?

### Bonus Questions
1. Create a table with the columns customer_id, order_date, product_name, and price. Add a new column called member. The value of member should be 'N' if the order took place before a customer became a member and 'Y' if the order took place after the customer became a member.
2. Take the table you created in Bonus Question # 1. Add a new column called ranking. The value of ranking should be null if the order took place before a customer became a member. If the order took place after the customer became a member, then add a rank to each order. For example, the first order that took place after a customer became a member should be 1. If two orders took place on the same day, they should have the same ranking.
