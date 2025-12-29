# Data Visualization Rationale  
## Global Sales Dashboard – Power BI

## Document Purpose
This document explains the rationale behind the selection of each visualization used in the **Global Sales Dashboard**, 
detailing how each chart supports specific business questions, enhances data interpretation, and enables informed decision-making.

The focus is on aligning **data type**, **analytical intent**, and **appropriate visualization**, 
following best practices in Business Intelligence and data visualization.

---

## Adopted Principles
The visualizations were designed based on the following principles:

- Clarity of communication
- Alignment with data types (categorical, numerical, geographic)
- Fast readability for decision-makers
- Avoidance of cognitive overload
- Visual and semantic consistency

---

## 1. KPI – Total Sales

**Business Question:**  
What is the total sales value?

**Visualization Type:**  
Key Performance Indicator (KPI)

**Rationale:**  
KPIs are effective for presenting high-level business metrics, enabling executives to quickly assess overall performance. 
Total sales is a core financial metric and therefore occupies a prominent position in the dashboard.

**Advantages:**
- Immediate readability
- Clear communication of overall performance
- Strong executive appeal

**Limitations:**
- Lacks contextual detail
- Should be complemented by supporting visualizations

---

## 2. Pie Chart – Number of Sales by Category

**Business Question:**  
How many sales were made by product category?

**Visualization Type:**  
Pie Chart

**Rationale:**  
The pie chart was used to represent the proportional contribution of each product category to total sales. 
This choice is appropriate due to the **limited number of categories**, preventing visual clutter and supporting intuitive percentage-based interpretation.

**Advantages:**
- Clear perception of proportions
- Intuitive for non-technical audiences
- Suitable for a small number of categories

**Limitations:**
- Does not scale well with many categories
- Close values can be harder to compare precisely

**Note:**  
For higher category granularity, a bar chart would be more appropriate.

---

## 3. Horizontal Bar Chart – Average Discount by Subcategory

**Business Question:**  
What is the average discount applied by product subcategory?

**Visualization Type:**  
Horizontal Bar Chart

**Rationale:**  
Bar charts are ideal for comparing values across multiple categories. The horizontal orientation improves label readability, 
particularly when dealing with numerous subcategories.

**Advantages:**
- Enables direct comparison
- Supports sorting by value
- High visual accuracy

**Limitations:**
- Requires adequate space in the layout
- Can become cluttered with excessive categories

---

## 4. Map – Average Sales by Country

**Business Question:**  
Which countries have the highest average sales value?

**Visualization Type:**  
Geographic map with proportional bubbles

**Rationale:**  
Geographic visualization enables the identification of spatial patterns and regions with higher commercial relevance. 
Proportional bubbles support relative comparison between countries and assist decision-makers in evaluating regional opportunities.

**Advantages:**
- Strong visual impact
- Rapid identification of geographic patterns
- Effective for exploratory analysis

**Limitations:**
- Not ideal for precise value comparison
- May lead to subjective interpretation if used in isolation

**Note:**  
The map is intended as a complementary visual rather than a standalone quantitative reference.

---

## 5. Stacked Bar Chart – Number of Orders by Country and Priority

**Business Question:**  
How many sales were made by country considering shipping priority?

**Visualization Type:**  
Stacked Bar Chart

**Rationale:**  
This visualization allows simultaneous analysis of total order volume per country and the composition by shipping priority, 
making it particularly useful for operational and logistics analysis.

**Advantages:**
- Combines volume and composition
- Facilitates country-level comparison
- Clear representation of priority distribution

**Limitations:**
- Internal segment comparisons may be less precise
- Requires careful color contrast selection

---

## 6. Interactive Filters (Year, Segment, Country)

**Purpose:**  
Enable dynamic and segmented analysis.

**Rationale:**  
Filters enhance dashboard flexibility, allowing users to explore the data based on specific business contexts without compromising the core analytical structure.

**Advantages:**
- Increased interactivity
- Personalized analysis paths
- Support for multiple business scenarios

---

## Final Considerations
The selected visualizations were defined based on the relationship between **business questions**, **data types**, and **visual clarity**, 
prioritizing usability and decision support. The dashboard design balances executive-level insight with analytical exploration, 
while respecting the limitations of the available dataset.

This rationale reinforces that visualization choices should be driven by communication effectiveness and business value—not aesthetics alone.
