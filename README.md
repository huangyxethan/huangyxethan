### Hi, I'm Yixiang (Ethan) Huang

MS Financial Mathematics candidate in the Machine Learning and AI concentration at the University of Chicago, focused on equity and equity derivatives alpha research and systematic trading.

I graduate in December 2026 and am seeking full-time Quantitative Research opportunities starting in 2027.

My work spans the quantitative research pipeline: machine learning and deep learning for signal generation, portfolio optimization and risk management for strategy construction, and rigorous backtesting and model evaluation for validation. I also have training in derivative pricing, from stochastic calculus and risk-neutral valuation to Monte Carlo simulation and volatility modeling.

#### Research areas

- Derivative pricing and hedging: autocallables, options, and futures
- Equity alpha research with machine learning and deep learning, including tick-level data
- Systematic strategies: futures (CTA), sector and ETF rotation, and factor research
- Portfolio construction, risk analytics, and performance attribution

#### Selected work

| Project | What it does | Stack |
|---|---|---|
| [investment-research-agent](https://github.com/huangyxethan/investment-research-agent) | NL2SQL research assistant for Chinese public mutual funds: generates SQL from a question, validates it with a deterministic AST guard, runs it, then narrates and charts the result; ships with an evaluation suite | Python, Streamlit, PostgreSQL + pgvector, sqlglot, Plotly, Claude / DeepSeek |
| [commodity-multi-agent-trading](https://github.com/nalin2002/commodity-multi-agent-trading) · team project | Four-agent LangGraph trading desk for WTI, Gold and Corn futures (news analyst, market analyst, risk manager, trader) with a daily 2024 backtest. My part: the News Analyst's expanding-window, recency-bucketed retrieval over a GDELT / NewsAPI / RSS cache, extending the news and market agents from WTI to three commodities, and the daily backtest cadence | Python, LangGraph, OpenAI, GDELT / BigQuery, pandas |
| [news-regime-discovery](https://github.com/huangyxethan/news-regime-discovery) | Can financial news improve market regime detection beyond price features? 18 unsupervised pipelines (price-only, news-only, hybrid) over 6,262 S&P 500 trading days, 2000-2025, using firm-level and macro RavenPack news; evaluated on statistical fit, clustering quality, temporal stability and per-regime financial behaviour. News lifts silhouette by 35% over the price-only HMM baseline | Python, scikit-learn, hmmlearn, FinBERT, BERTopic, LDA, pandas |
| [snowball-delta-hedging](https://github.com/huangyxethan/snowball-delta-hedging) | Autocallable (snowball) pricing and delta-hedging research framework: Monte Carlo and Crank-Nicolson PDE engines sharing one terms object, a daily index backtest that rolls a ladder of virtual snowballs and hedges their aggregate delta in CSI 500 futures, and a minute-level execution layer whose NAV difference to the index decomposes exactly into quantity, price and fee terms. Runs end-to-end on synthetic data | Python, NumPy, SciPy, pandas, PyArrow |

#### Background

- Quantitative research, trading, and risk internships at CITIC Securities, Guotai Haitong Securities Asset Management, CICC, and GF Securities Asset Management
- B.S. in Statistics, Central University of Finance and Economics

#### Links

- Website: [huangyxethan.github.io](https://huangyxethan.github.io)
- LinkedIn: [in/yixianghuang](https://www.linkedin.com/in/yixianghuang/)
- Email: huangyxethan@gmail.com
