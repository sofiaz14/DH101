# Environmental Impact Report

## The Artifact
<iframe
	src="../Assets/week12-ai-carbon-infographic.html"
	title="AI Carbon Footprint Interactive Infographic"
	style="display: block; width: min(1300px, calc(100vw - 4rem)); max-width: none; height: 1400px; margin: 0 auto; border: 1px solid #d0d0d0; border-radius: 8px;"
	loading="lazy">
</iframe>

[Open the interactive infographic in a new tab](../Assets/week12-ai-carbon-infographic.html)

## Process Notes
✦ How did you make this? I researched AI's carbon footprint using academic, government, and industry sources, then organized the data into an interactive infographic with comparisons and a personal footprint calculator.
✦ What tools did you use? I used Claude AI to help turn the data I collected into an interactive infographic.
✦ What decisions did you make? I chose to focus on carbon emissions, use comparisons like flights and trees to make the numbers easier to understand, and include a calculator so users could connect AI use to environmental impact.

## Reflection
For this project, I focused on Track A, visualizing the carbon footprint of AI training and everyday use. My primary sources were academic papers, government data, and industry research reports. The two most important academic sources were Emma Strubell et al.'s 2019 paper "Energy and Policy Considerations for Deep Learning in NLP," which provided the foundational estimate of 552 metric tons of CO2 for training a large language model, and David Patterson et al.'s 2021 paper "Carbon Emissions and Large Neural Network Training" from Google and UC Berkeley, which supplied estimates for image generation costs. For context and comparison data, I relied on the EPA's greenhouse gas emissions figures for average US household output, the ICAO Carbon Emissions Calculator for flight emissions, and the USDA Forest Service for tree carbon absorption rates. The per-query ChatGPT estimate of 4.55g CO2 came from a Goldman Sachs research report widely cited in 2023.
The most significant challenge in this research was that major AI companies like OpenAI, Google, and Meta do not publicly disclose the exact energy consumption or carbon emissions of their model training runs. This means nearly all available numbers are based on third party academic estimates rather than official company data. OpenAI has never released an official carbon figure for GPT-3 or GPT-4, so the 552 ton figure is an extrapolation based on comparable model architectures. This makes precise comparison difficult and means the actual numbers could be higher or lower than reported. On the other hand, the most striking finding was the sheer scale of emissions from a single training run. Before this project, I assumed AI's environmental cost was relatively minor compared to things like car travel or home energy use. Discovering that one training run is roughly equivalent to 560 transatlantic flights completely changed how I think about the infrastructure behind everyday AI tools. The data made something that felt intangible, like cloud computing, feel very physical and costly.

## Artist's Statement
When I started this project, I knew AI used energy. What I did not know was the scale. Learning that training a single AI model can emit the equivalent of 560 transatlantic flights stopped me in my tracks. That is not an abstract statistic; it is a physical, measurable cost incurred every time a new model is built, often invisibly to the people using it. What concerns me most is that no single part of AI's environmental impact stands out as the worst because it is all of it together. The carbon from training runs, the water consumed by cooling systems, the mountains of e-waste from hardware that becomes obsolete within a few years. Each problem on its own is already so serious. But when combined, they paint a picture of an industry growing faster than its accountability.
For my visualization, I chose an interactive infographic because I wanted people to feel the numbers rather than just read them. The personal calculator at the bottom was important to me because I did not want to make individuals feel guilty, but to make the connection between everyday use and planetary cost feel real and tangible rather than distant. The answer I ask myself, and you have asked the class, is "can AI be sustainable? My answer is maybe, but it would require changes far beyond what any individual user can make. One idea gaining attention is locating data centers in space, where solar energy is abundant. Elon Musk and others have floated concepts like this. The problem is that data centers are massive structures requiring enormous cooling infrastructure, and cooling in the vacuum of space presents serious unsolved engineering challenges. It is an interesting vision, but right now it remains far from practical. After doing this project, I feel conflicted. I use AI regularly and find real value in it. But I can no longer use it without thinking about what is running underneath. That awareness feels like the honest place to land.

## Attribution & AI Use
- Tools used: Claude (input all the data I found and told it to make me an interactive infographic)
- Sources: Patterson, David, et al. "Carbon Emissions and Large Neural Network Training." arXiv, 2021, arxiv.org/abs/2104.10350.
	Strubell, Emma, et al. "Energy and Policy Considerations for Deep Learning in NLP." Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics, 2019, arxiv.org/abs/1906.02629.
	United States, Environmental Protection Agency. "Greenhouse Gas Emissions." EPA, www.epa.gov/ghgemissions. Accessed 20 Apr. 2026.
	International Civil Aviation Organization. "ICAO Carbon Emissions Calculator." ICAO, www.icao.int/environmental-protection/Carbonoffset/Pages/default.aspx. Accessed 20 Apr. 2026.
	United States, Department of Agriculture Forest Service. "How Trees Fight Climate Change." USDA, www.fs.usda.gov. Accessed 20 Apr. 2026.
	Goldman Sachs. "Generative AI: Too Much Spend, Too Little Benefit?" Goldman Sachs Briefings, 2023,
	www.goldmansachs.com/insights/pages/gs-research/generative-ai-too-much-spend-too-little-benefit/report.pdf.
