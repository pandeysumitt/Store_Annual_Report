# Store_Annual_Report 
An interactive sales analytics dashboard built in Microsoft Excel using Pivot Tables and Pivot Charts, providing a full-year view of store performance across channels, regions, demographics, and product categories.

# File Structure

 ├── Vrinda_Store_Annual_Report.xlsx   # Main Excel workbook
├── dashboard_preview.png             # Dashboard screenshot
└── README.md                         # Project documentation

#  Dashboard Sections

| Chart | Description |
|-------|-------------|
| **Orders Vs Sales** | Monthly combo chart comparing total revenue (bar) and order count (line) across Jan–Dec |
| **Sales: Men Vs Women** | Pie chart showing gender-based purchase split — Women 64%, Men 36% |
| **Order Status** | Pie chart of fulfillment outcomes — Delivered 92%, Returned 3%, Refunded 2%, Cancelled 3% |
| **Sales: Top 5 States** | Horizontal bar chart ranking Maharashtra, Karnataka, Uttar Pradesh, Telangana, and Tamil Nadu by revenue |
| **Orders: Age Vs Gender** | Clustered bar chart showing order distribution across Adults, Seniors, and Teenagers by gender |
| **Orders: Channels** | Pie chart of sales channel share — Amazon 35.48%, Myntra 23.36%, Flipkart 21.59%, Meesho 4.50%, Ajio 6.22%, Nalli 4.78%, Others 4.06% |

# Key Insights

* 📦 92% of all orders were successfully delivered
* 👩 Women account for 64% of total purchases
* 📍 Maharashtra is the top-performing state with ₹29.9L in sales
* 🛒 Amazon leads all sales channels at 35.48% share
* 📅 March recorded the highest order volume and revenue
* 👨‍👩‍👧 Adults are the dominant customer age group across both genders

# Tools & Techniques Used

* Microsoft Excel – Dashboard design and layout
* Pivot Tables – Data aggregation and summarization
* Pivot Charts – Visual representations (bar, line, pie charts)
* Slicers – Interactive filters for Category, Channel, and Month
* Data Sheets – Separate sheets for each analysis (Sales Vs Orders, Men Vs Women, Order Status, Sales State, Age & Gender, Channels).

# 🗂️ Workbook Sheets
| Sheet Name | Purpose |
|------------|---------|
| `Report` | Main interactive dashboard |
| `Sales Vs Orders` | Source pivot for monthly trend chart |
| `Men Vs Women` | Source pivot for gender analysis |
| `Order Status` | Source pivot for fulfillment status |
| `Sales State` | Source pivot for top states |
| `Age n Gender` | Source pivot for demographic analysis |
| `Channels` | Source pivot for platform-wise orders |
| `Vrinda Store ...` | Raw data sheet |

# How to Use

1. Download the .xlsx file and open it in Microsoft Excel (2016 or later recommended)
2. Use the Slicers on the left panel to filter by:
   * Category (Blouse, Bottom, Ethnic Dress, Kurta, etc.)
   * Channel (Amazon, Flipkart, Meesho, Myntra, etc.)
   * Month (Jan through Dec)
3. All charts update dynamically based on slicer selections
4. Navigate to individual sheets for detailed pivot data

# Requirements
* Microsoft Excel 2016 or later
* Excel for Microsoft 365 for best slicer and chart rendering


# 🙋 Author
Sumit Pandey
Feel free to connect or raise an issue if you have suggestions!

# 📄 License
This project is for educational and portfolio purposes.
