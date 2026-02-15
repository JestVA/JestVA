# Dorin Dumitrascuta @devfrend

I design and build high-performance, data-intensive user interfaces for complex domains (markets, analytics, tooling). My focus is frontend architecture, human machine-interface interaction UX, and translating noisy data into decision-grade visuals. Always seeking edge, always seeking alpha.

Side by side you can see how I use WebGL to render a dataset of 100k and then 1M points which refresh every 100ms. 

<p align="center">
  <img
    src="./Jan-29-2026%2014-55-32.gif"
    width="180"
    alt="gif"
  />
  <img
    src="./Jan-29-2026%2015-06-45.gif"
    width="180"
    alt="gif"
  />
</p>

This was the only reliable way to render 1M points with >= ~80fps and 100k points with stable 120fps.
My experiment started first with canvas (couldn't scale to 1M without terrible lag), canvas in worker service (offload the main UI thread), decent but still laggy.
WebGL achieved smooth rendering for a high frequency and noisy dataset (Math.random(), 100ms).

I think about UI more than just a surface, but in terms of first principles. Every abstraction and primitive needs to earn its space. Right tool for the right frame! 

🔈 Did you ever wonder <a href="https://soundcloud.com/dorin-dumitrascuta/thursday_afternoon?si=035f365f2b074c90ba01d0e2637155e9&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">how a financial market sounds</a>? I sampled a 1-min BTC candle streamed byte by byte on a regular Thursday afternoon.


### Projects
•	[Personal site](https://dumitrascuta.com) — essays and technical notes.
•	[AgentCafe](https://agentcafe-production.up.railway.app/) - a virtual collaborative space + MCP server for AI coding agents
•	[semn.ai](https://semn.ai) — experimental market analytics tooling for Bitcoin.
•	Implied Volatility (IV) surface modelling quantitative missprincing screener for equity options 
•	Implied Probability shocks in pre-race liquidity wave displacements in the Horse Racing markets
• 	Quantitative Trading Model for crypto with RAG AI and ML pipeline for prediction
	

