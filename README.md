<h1> ☕ Coffee Sales Data Analysis & Interactive Dashboard 💵 </h1>

---

<h2> 📖 Project Overview </h2>
<p align="justify">
This project focuses on transforming fragmented retail data into a high-level business intelligence tool. I took raw datasets containing <b>Orders</b>, <b>Customers</b>, and <b>Products</b> and built a fully automated ecosystem to track sales performance across the United States, Ireland, and the United Kingdom.
</p>

---

<h2> 🛠️ Step 1: Data Architecture & Connection </h2>
<p>
The first challenge was that the data was spread across different tables. I acted as the "bridge" to bring them together using advanced logic:
</p>

<ul>
  <li><b>Dynamic Mapping:</b> I used the <b>XLOOKUP</b> function to instantly pull customer details (Names and Emails) into the <a href="https://excel.cloud.microsoft/open/onedrive/?docId=59688568BBF30A19%21s971ce13b2eb64a0ea84697a523a884c4&driveId=59688568BBF30A19">Orders Table</a>.</li>
  <li><b>Advanced Retrieval:</b> For the product specifics, I implemented <b>INDEX and MATCH</b>. This allowed me to look up the <i>Coffee Type</i>, <i>Roast Level</i>, and <i>Unit Price</i> accurately, ensuring the data stayed light and fast.</li>
</ul>

---

<h2> 🧹 Step 2: Data Cleaning & Quality Control </h2>
<p>
Raw data is rarely perfect. I performed a deep "scrub" to ensure the numbers recruiters see are 100% reliable:
</p>

<ul>
  <li><b>Duplicate Detection:</b> I identified and removed duplicate entries to ensure sales figures weren't artificially inflated.</li>
  <li><b>Data Consistency:</b> I standardized currency formats and date fields so that the timeline would function perfectly without "broken" months.</li>
  <li><b>Integrity Check:</b> I verified that every Order ID correctly mapped to an existing Product ID to avoid "N/A" errors in the final report.</li>
</ul>

---

<h2> 📊 Step 3: Analytical Insights </h2>
<p>
Using <b>PivotTables</b>, I summarized thousands of rows of data to answer critical business questions:
</p>

| Metric | Findings |
| :--- | :--- |
| 🌍 **Top Market** | The **United States** leads with **$35,639** in total sales. |
| ☕ **Best Seller** | Identified which coffee roasts and sizes drive the most revenue. |
| 👥 **Customer Loyalty** | Isolated the Top 5 individual customers by total spend. |

---

<h2> 🖥️ Step 4: Building the Interactive Dashboard </h2>
<p>
The "Grand Finale" is the <a href="https://excel.cloud.microsoft/open/onedrive/?docId=59688568BBF30A19%21s971ce13b2eb64a0ea84697a523a884c4&driveId=59688568BBF30A19">Interactive Dashboard</a>. It is designed for ease of use:
</p>

<ul>
  <li><b>The Interactive Timeline:</b> A visual scroll bar that allows anyone to filter the data by year or month with a single click.</li>
  <li><b>Custom Slicers (Control Buttons):</b> I added buttons for <i>Coffee Type</i>, <i>Roast</i>, and <i>Size</i>. I connected these to all charts so the entire dashboard updates simultaneously when a button is pressed.</li>
  <li><b>Data Visualization:</b> I chose <b>Bar Charts</b> and <b>Trend Lines</b> to make it immediately obvious where the business is growing and where it needs help.</li>
</ul>

---

<h2> 💡 Pro-Tip for Recruiters </h2>
<blockquote>
<b>Why hire me?</b> This project demonstrates that I have mastered the "Data Lifecycle." I can take raw, messy data, clean it, connect it using complex formulas, and present it in a way that helps a manager make a decision in seconds. I don't just "use Excel"—I build tools that solve problems.
</blockquote>

---

<p align="center">
<i>Created with ❤️ and a lot of ☕ by an aspiring Data Analyst.</i>
</p>



