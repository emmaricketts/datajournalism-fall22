# Make your own dataset

[Assignment 2 dataset.xlsx ](https://github.com/emmaricketts/datajournalism-fall22/blob/1bb09ff85fb1c130c2ff502d8cadce3928e2e667/Assignment%202%20dataset.xlsx)

# Story research

My original intention - to research asset managers that have disclosed voluntary TCFD-aligned reports in advance of US SEC requirements - did not work out as there is a lack of data available. Instead, I have decided to have a look at countries' nationally determined contributions (NDCs).

NDCs are a foundational aspect of the Paris Agreement. It works on a five-year cycle of increasingly ambitious climate action. Each party must prepare a plan to reduce emissions and adapt to climate change, and communicate it to the UNFCCC by 2020 and every five years thereafter. Biennial progress reports are also required.

With COP27 approaching in a month, NDCs show that the world is not on track to meet the Paris Agreement's goals. Based on many parties' NDCs - and/or the fact many countries don't have policies that put them on track to meet them - we will not limit global temperature increase to well below 2 degrees Celsius, while pursuing efforts to limit the increase to 1.5 degrees.

Some news reports that have covered this issue include:
- Middle East Institute: *[COP27: A time to address the “triple inequality”](https://www.mei.edu/publications/cop27-time-address-triple-inequality)* - "the latest U.N. Environment Program (UNEP) Emissions Gap Report shows that updated national climate pledges would reduce projected 2030 emissions by only 7.5% as compared with previous unconditional NDCs, whereas a 30% reduction is needed to limit warming to 2°C, and 55% is required to meet the Paris Agreement goal of limiting warming to 1.5°C"
- Eurek Alert: *[UNEP Emissions Gap report: Updated climate commitments ahead of COP26 summit fall far short, but net zero pledges provide hope](https://www.eurekalert.org/news-releases/932645)*
- Carbon Brief: *[UNEP: Current climate commitments are ‘weak promises, not yet delivered](https://www.carbonbrief.org/unep-current-climate-commitments-are-weak-promises-not-yet-delivered/)*
- Bloomberg: [The World Is Too Busy to Do Its Climate Summit Homework](https://www.bloomberg.com/news/articles/2022-09-26/what-are-national-plans-to-fight-climate-change-ahead-of-cop27) - “The gist of what Glasgow said was we’re not yet on track,” said David Waskow, director of the World Resources Institute’s International Climate Initiative. While there’s been “modest movement,” he said, “there were missed opportunities, and clearly we need to galvanize much stronger action.”
- The National News: *[With a month left before Cop27, is the Middle East on track with its climate goals?](https://www.thenationalnews.com/opinion/comment/2022/10/07/with-a-month-left-before-cop27-is-the-middle-east-on-track-with-its-climate-goals/)* - "The Glasgow Climate Pact in 2021 assessed that, if all NDC targets pledged in Paris were implemented, we would still head towards 2.4°C of global warming, with a worst-case scenario of 2.8°C if not all pledges are implemented, and a best-case scenario of 1.8 °C if all new actions in Glasgow are implemented"
- Brookings: *[Success of the Paris Agreement hinges on the credibility of national climate goals](https://www.brookings.edu/blog/planetpolicy/2022/09/30/success-of-the-paris-agreement-hinges-on-the-credibility-of-national-climate-goals/)*
- Climate Change News: *[Gap to 1.5C yawns, as most governments miss UN deadline to improve climate plans](https://www.climatechangenews.com/2022/09/26/gap-to-1-5c-yawns-as-most-governments-miss-un-deadline-to-improve-climate-plans/)*


There are also some studies on this topic:
- Climate Change Performance Index: 2022 results - *[Monitoring Climate Mitigation Efforts of 60 Countries plus the EU – covering 92% of the Global Greenhouse Gas Emissions](https://ccpi.org/wp-content/uploads/CCPI-2022-Results_2021-11-10_A4-1.pdf)*
- UNEP 2021 *[Emissions Gap Report](https://www.unep.org/resources/emissions-gap-report-2021)*
- *[United in Science 2022](https://library.wmo.int/doc_num.php?explnum_id=11308):* "A continuation of the new or updated unconditional NDCs andother pledges is estimated to limit warming to 2.7 °C by the end of the century with a 66% probability. If conditional pledges are also fully implemented, these estimates are lowered to 2.5 °C. ... Only when the full implementation of all net-zero pledges and announcements to date are taken into account, in addition to the updated unconditional and conditional NDCs, do warming projections get closer to the Paris Agreement goal. Under this scenario, warming over the twenty-first century is projected to be limited to 2.1 °C."

I have not found a simple, easy-to-follow news reports that cover some of the key differences between current NDCs and the Paris Agreement goals, including identifying which parties' NDCs are particularly insuficcient. I would like to try and fill that gap.

I have identified the following data sets as a starting point.
- *[IGES NDC Database](https://www.iges.or.jp/en/pub/iges-indc-ndc-database/en)* - this dataset compiles the main features of NDCs, including mitigation targets (and which gases/sectors they cover), financial needs, technocology needs, and adaptation pledges.

Strengths: The Institute for Global Environmental Strategies is a public-interest incorporated foundation, initially established under the Japanese government. It appears to be well-researched and resourced, and

Limitation: this dataset is updated until October 2021. 29 parties have filed updates since then, according to the [NDC registry](https://unfccc.int/NDCREG), so it will take some work to ensure the data is correct for these countries.

- *[Climate Action Tracker net zero target evaluations](https://climateactiontracker.org/global/cat-net-zero-target-evaluations/)* - this identifies net zero targets in G20 counties, including their scope, legal status and review methods, etc.

Strengths: CAT is an independent body of scientific analysis. It is funded by various organisations and governments, and is relied upon widely. This data will be useful to compare actual national policies to the countries' NDCs. The data is up to date to 21 September 2022.

Limitations: this dataset does not include all parties to the Paris Agreement, and does't have information for many of them.

- *[NDC Explorer](https://klimalog.idos-research.de/ndc/#NDCExplorer/worldMap?NewAndUpdatedNDC??income???catIncome)* - raw data for first NDCs submitted by 2020, as well as new/updated NDCs.

Strengths: from the German Development Institute, a well-respected, global think-tank. It is The [graphics](https://klimalog.idos-research.de/ndc/#NDCExplorer/worldMap?NewAndUpdatedNDC??climatechangemitigation???cat1) created by the producers of the data are useful to analyse and see what trends have been identified. This can be informative contextually, in a way that a spreadsheet of data may not be.

Limitations: updated until February 2022. 17 parties have filed updates since then. Original NDCs and updated NDCs are not in the same spreadsheet.
