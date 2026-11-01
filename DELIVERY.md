# Buyer Hunt delivery workflow (zero human)
1. Order arrives as a PayPal payment ($49). Description = "Buyer Hunt | <product URL> | <email> | <who>". Watch PayPal payment emails in Nidhi's PayPal-linked inbox (transaction-search API is disabled on the app).
2. Agent opens the product URL and writes 1 line: problem solved + buyer.
3. Generate 10-15 buyer phrasings ("is there a tool that", "looking for an app to", "I'd pay for", "alternative to <competitor>").
4. Run x.search_posts_all, last 14 days, -is:retweet. Keep posts where the AUTHOR has the problem (not vendors). Target 30.
5. For each: URL, date, handle, followers, why it fits, and a unique reply (helpful first, product mention last, <=280 chars).
6. Deliver a Google Sheet or CSV + the top 5 phrases to the buyer's email from nidhi69n@gmail.com within 24h. If fewer than 30: refund pro rata through PayPal (needs Nidhi's OK on each refund).
