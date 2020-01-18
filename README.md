# Mutual Fund Risk Disclosure


1.	Over 54 million American households save for retirement through investments in mutual funds (think TIAA CREF & Fidelity). The potential to build a robust dataset of mutual fund risk disclosures and the relevance of mutual fund disclosures to individual and national retirement security, make this area ripe for further research with implications in corporate/investment law, finance and data science fields, among others.

2.	All publicly traded open-ended mutual funds disclose principal and non-principal investment risks of investing in the fund, including the risks to which the fund’s portfolio, as a whole, is subject and the circumstances reasonably likely to affect adversely the fund’s net asset value, yield, and total return.
a.	Filings are publicly available through SEC website/Edgar filings and searchable.  Additional mutual fund data is available through WRDS/CRSP data services (available through GSU) and includes industry segment, performance, fund flows, holdings, etc.

3.	Mutual Fund disclosures are largely modeled after the disclosure regime imposed on operating companies (think Home Depot).  Company-level risk disclosures are focused on firm specific risks, whereas mutual fund risks are largely derived from market, asset class/investment strategy, interest rate, counter-party, and other risks—in other words, mutual fund risks are not largely firm specific.  The difference in risk disclosure has been theorized by corporate law scholar Henry Hu.   

4.	Corporate risk disclosures have been empirically studied, recently incorporating text mining and data science methodologies creating an interesting methodological play book and set of risk disclosure search and coding terms.   Areas of inquiry include whether disclosures are unique vs. boilerplate, the informativeness or signaling of the risk (how the market responds), and the correlation of unique risk disclosures to financial performance metrics.  Others have looked at the relationship between company risk disclosures and future litigation outcomes.  

5.	Preliminarily, research inquires may include:
a.	Using empirical assessment to observe how mutual fund risk disclosures are used (to inform investors, and if so, which ones? To avoid litigation?  To conform to the crowd?)
b.	Are mutual fund risk disclosures subject to herding?  Do funds use boilerplate language or provide unique disclosures?  Are patterns observable within mutual fund segments (i.e., growth vs. income funds or index), or fund families?  
c.	Are mutual fund risk disclosures shaped by periodic SEC guidance on disclosures (i.e., separate SEC Guidance on derivative risk disclosures and interest rates.)?  Are disclosure patterns observable after the guidance is issued?
d.	Can we confirm the Henry Hu framework about what mutual funds should be disclosing—asset class, asset allocation and asset decision making theory?  Do some funds follow this intuition in their disclosures and if so, are there observable benefits in terms of performance, fund flow, etc.?
e.	How does the market interpret mutual fund disclosures?  Are there observable correlations with fund performance, flow, etc.?  
f.	Utilize a more traditional data science approach where the information speaks for itself—we build the dataset and analyze it using several different techniques—cluster, decision tree, regression to identify the trends/determinative features.
g.	Additional questions to be developed in light of specific team interests, dataset availability, and parameters established by existing literature.
