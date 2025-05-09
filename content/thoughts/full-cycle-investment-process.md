---
title: "Full-Cycle Investment Process"
description: "Embarking on a journey to deconstruct, understand, and build a robust, data-driven, full-cycle investment process. This post outlines the 'why' and the 'how'."
date: 2023-03-01
draft: false
tags: ["Process", "Investment", "Finance"]
weight: 100
cover:
    image: "/thoughts/full-cycle-investment-process/cover.jpg"
    alt: "Blueprint of a vault."
    caption: ""
---

# My Full-Cycle Investment Process

## Introduction: The Quest for a Repeatable Edge

Financial markets have been a passion of mine since my first undergraduate finance course in 2012. The complexity of economies, companies, and human psychology that drives market movements is endlessly fascinating. However, fascination alone doesn't secure financial well-being. I've never liked the idea of traditional "long-only" 60/40 portfolios that get decimated during market corrections, and the increasing turmoil in global financial markets and geo politics in general has amplified my concerns for my own financial future, but also in light of the transformative rise of AI and its potential impact on job security.

All of this has crystallized into a clear message: it's the perfect time to dedicate focused energy to a passion that has direct, real-world implications for myself and my family. My objective is to move beyond passive observation and create a robust, adaptable investment framework.

My goal is to build a system that is:

*   **Top-Down Macro Driven:** Understanding the big-picture economic environment first.
*   **Quantitatively Grounded:** Leveraging data and systematic signals.
*   **Fundamentally Informed:** Incorporating bottom-up analysis where it adds value.
*   **Rules-Based & Disciplined:** Minimizing emotional decision-making.

This project is inspired by the methodologies of successful full-cycle investors, notably the framework detailed in Keith McCullough's "Master The Market." My aim is to deeply understand the underlying mechanics, adapt them to my own perspectives, and innovate on them to create a more effective and personalized system.

This initial post serves as a roadmap, outlining the key phases and components I intend to explore and build.

## Project Outline: Deconstructing and Rebuilding

My approach will be systematic, breaking down the investment process into its core components. Here’s a high-level look at the planned phases:

1.  **Phase 1: The GIP Model & Economic Quads**
    *   **Objective:** Define and model the "Growth, Inflation, Policy" (GIP) framework to understand the prevailing macroeconomic regime.
    *   **Key Activities:**
        *   Identifying key economic data series for tracking Growth and Inflation.
        *   Developing methodologies to measure their *rate of change* – the crucial driver of the model.
        *   Establishing clear, data-driven rules for "Quad" determination (e.g., Quad 1: Growth Accelerating, Inflation Slowing).
        *   Researching historical policy responses and market behaviors associated with each Quad.
        *   **Initial Validation:** Backtesting this Quad determination process against historical data to verify its alignment with the source material's principles before proceeding.

2.  **Phase 2: Asset Allocation & Factor Selection**
    *   **Objective:** Map economic Quads to theoretically optimal asset class, sector, and style factor exposures.
    *   **Key Activities:**
        *   Conducting historical backtests to analyze the performance of various assets, sectors, and style factors within each identified Quad. This serves as a crucial validation step, comparing my findings against the expected outcomes suggested by the reference framework.
        *   Building a decision matrix or a quantitative model to guide asset allocation based on the currently identified or forecasted Quad.

3.  **Phase 3: Execution - The Risk Range™ Signaling System**
    *   **Objective:** Develop a tactical system for identifying probable trading ranges and generating entry/exit signals for specific assets, based on price, volume, and volatility.
    *   **Key Activities:**
        *   Investigating the quantitative interpretation of Price, Volume, and Volatility inputs.
        *   Modeling "Trade," "Trend," and "Tail" duration signals to capture different market periodicities.
        *   Defining objective criteria for bullish and bearish formations based on these signals.

4.  **Phase 4: Integrating Bottom-Up Fundamental Analysis**
    *   **Objective:** Explore methodologies for layering in fundamental, company-specific research as a potential refinement within the broader macro-dictated themes.
    *   **Key Activities:**
        *   Identifying qualitative and quantitative criteria for selecting individual securities that align with favored sectors and styles identified in Phase 2.

5.  **Phase 5: Portfolio Construction & Risk Management Rules**
    *   **Objective:** Define a comprehensive and explicit set of rules for building and managing the investment portfolio.
    *   **Key Activities:**
        *   Establishing dynamic position sizing rules (e.g., MIN/MAX allocations) based on asset class characteristics, particularly volatility.
        *   Detailing a systematic, incremental approach to entering and exiting positions to manage risk and cost.
        *   Defining clear stop-loss and profit-taking strategies based on the risk management framework.

6.  **Phase 6: System Implementation & Rigorous Backtesting**
    *   **Objective:** Translate the complete, defined process into a coded system and rigorously test its historical efficacy and robustness.
    *   **Key Activities:**
        *   Finalizing and implementing the chosen tech stack.
        *   Developing robust data acquisition, cleaning, and management pipelines.
        *   Coding the full logic for Quad determination, asset selection, signaling, and portfolio management.
        *   Conducting comprehensive backtesting, including sensitivity analysis, out-of-sample testing, and detailed performance metric analysis.

## Preliminary Tech Stack Considerations

While this may evolve as the project progresses, my initial thoughts on the technology to power this endeavor include:

*   **Programming Language:** Python (leveraging its rich ecosystem for data science and finance: Pandas, NumPy, SciPy, Matplotlib, Scikit-learn).
*   **Data Sources:** APIs from financial data providers (e.g., Alpha Vantage, IEX Cloud, Quandl, Polygon.io, Yahoo Finance), FRED (for macroeconomic data).
*   **Backtesting Engine:** Exploring options such as `Zipline`, `Backtrader`, or potentially developing a custom framework tailored to this specific process.
*   **Database:** SQLite or PostgreSQL for efficient storage and retrieval of historical data, signals, and backtest results.
*   **Version Control:** Git.
*   **Blog/Documentation:** Hugo website.

## My Process & How to Follow Along

I'll be documenting this journey through two main sections on my website:

*   **"Thoughts":** This section will serve as my development blog. Here, I'll outline my approach for each upcoming step, discuss conceptual challenges, share research findings, and lay out the theoretical groundwork prior diving into implementation.
*   **"Projects":** This is where the implementation will happen. Each phase or significant component of the investment process will become a distinct project, detailing the technical work, code implementation, and practical application of the concepts discussed in "Thoughts."

This is an iterative process. I fully anticipate a journey filled with learning, refinement, and undoubtedly a few mistakes and dead ends. All of which I intend to share transparently.

---

**References:**

*   McCullough, Keith. *Master The Market: A Hedge Fund Manager's Guide to Process and Profit*.

---