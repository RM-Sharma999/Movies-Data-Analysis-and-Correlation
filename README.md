# Movies Data Analysis and Correlation

## Overview
This project involves **Exploratory Data Analysis (EDA)** and **data cleaning** of The Movies Dataset from Kaggle. The primary goal is to **uncover correlations between key attributes**, exploring relationships between **budget, gross revenue, production companies**, and much more.

---

## About the Dataset

- **Source**: Kaggle (The Movie Dataset)
- **Entries**: ~5,000 movies
- **Features**:
  - `movie name`: Title of the movie
  - `rating`: MPAA rating (PG, PG-13, R, etc.)
  - `genre`: Movie genre(s) such as Action, Drama, etc.
  - `year of release`: Year the movie was released
  - `IMDb score`: IMDb rating on a scale of 1–10
  - `viewer votes`: Number of votes received by viewers
  - `director`: Name of the director
  - `writer`: Name of the writer(s)
  - `star`: Lead actor/actress
  - `country`: Country of production
  - `budget`: Budget of the movie
  - `gross revenue`: Worldwide box office gross
  - `production company`: Studio or company behind the movie
  - `runtime`: Duration of the movie in minutes

---

## Visualizations & Insights

### 1. Gross Revenue vs Budget
This scatter plot illustrates the **relationship between a movie’s budget and its gross revenue**. A clear **positive trend** is visible—films with higher budgets generally tend to earn more. However, notable **outliers** exist, where some low-budget movies achieve massive success, while certain high-budget films underperform. This indicates that although higher investment can increase revenue potential, **box office success depends on multiple factors**, including content quality, release timing, and audience engagement.
![](https://i.imgur.com/4ooOd0c.png)

### 2. Gross Revenue vs IMDb Score
This plot compares a film’s **IMDb rating** with its **gross revenue**. Although there is a slight upward trend, the **correlation is weak**, showing that **critical acclaim does not always translate into box office success**. Several films with average ratings generate high revenue due to factors such as **franchise value, marketing, and star power**, while some highly rated films achieve only modest commercial performance. This visualization highlights the clear distinction between **popularity and perceived quality**.
![](https://i.imgur.com/gZvF87k.png)

### 3. Correlation Matrix for Numerical Features
This heatmap presents the **correlation** between key numerical attributes such as **budget, gross revenue, votes, IMDb score, and runtime**.

**Notable Insights**:
- **Gross revenue** shows a strong correlation with **budget** and **number of votes**, indicating that well-funded and widely watched films often perform better financially.
- **IMDb score** is moderately correlated with **votes**, but shows a weaker relationship with **gross revenue**, reinforcing earlier observations.
- **Runtime** and other features display **weaker correlations**, suggesting a less direct influence on success.

This matrix helps identify which factors are most aligned with **financial performance** and **audience popularity**.

![](https://i.imgur.com/F8pdckB.png)

### 4. Top 15 Production Companies by Gross Revenue  
This bar chart shows the **top 15 production companies** by **total worldwide gross revenue**, where industry leaders such as **Warner Bros., Universal Pictures, and Walt Disney** dominate, reflecting their ability to consistently produce **high-grossing films** through **strong brand value, large-scale marketing, and successful franchises**, highlighting their **major influence on the global film industry**.
![](https://i.imgur.com/DxuDSl4.png)

### 5. Top 15 Companies by Gross Revenue Per Year
This multi-year bar chart illustrates how the **top-grossing production companies** perform **year by year**, providing a clear **time-series perspective** of studio success. It highlights how industry leaders **rise and fall over time**—for example, some years are dominated by **Disney** due to major **Marvel or Pixar releases**, while in other years **Universal** or **Warner Bros**. take the lead. This visualization shows how **release schedules, franchise cycles, mergers, and shifting audience trends** influence which studios dominate the global box office.
![](https://i.imgur.com/Bk6ljkr.png)

---

## Recommendations

- **Balance Budget and Expectations**  
  While high-budget films often generate higher revenue, the analysis shows that some **lower-budget films can outperform expectations**. The focus should be on **effective budget allocation** rather than sheer scale.

- **Prioritize Audience Engagement**  
  Viewer votes show a **strong correlation with gross earnings**. Building anticipation and maintaining audience interaction across platforms can significantly improve box office outcomes.

- **Don’t Rely Solely on Ratings**  
  A **high IMDb score doesn’t guarantee commercial success**. Combine quality with **accessibility, strong marketing, and wide distribution** to increase revenue potential.

- **Leverage High-Performing Production Companies**  
  Certain companies consistently dominate in gross revenue. Emerging companies can study their **release patterns, marketing strategies, and partnerships** to improve performance.

- **Analyze Yearly Trends**  
  The yearly breakdown of top-performing companies reveals **shifts in industry leadership**. Staying adaptive and analyzing yearly market trends can help identify the **right timing and strategy** for releases.

---

## Conclusion

This project explored key factors influencing a movie’s **commercial success** using data analysis and visual storytelling. By examining relationships between **budget, gross revenue, IMDb scores, votes, production companies**, and more, we uncovered several valuable insights.

Notably, **higher budgets** and **strong audience engagement (measured by votes)** are often linked to greater box office returns. However, **critical ratings alone do not guarantee commercial success**—highlighting the importance of balancing quality with strategic marketing and wide reach.

The analysis also reveals the impact of **production companies** on revenue outcomes and shows how **yearly trends** reflect shifting market dynamics. These insights can support filmmakers, producers, and analysts in making **data-driven decisions** to improve performance and reduce financial risk in future projects.





Production companies play a significant role in revenue outcomes, and yearly trends show how market dynamics evolve over time. These insights can help guide decision-making for filmmakers, producers, and industry analysts aiming to optimize performance and reduce risk in future projects.
