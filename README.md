# 🏛️ Wayback Tweets

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://waybacktweets.streamlit.app) [![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/claromes/waybacktweets?include_prereleases)](https://github.com/claromes/waybacktweets/releases) [![License](https://img.shields.io/github/license/claromes/waybacktweets)](https://github.com/claromes/waybacktweets/blob/main/LICENSE.md)


Tool that displays, via [Wayback CDX Server API](https://github.com/internetarchive/wayback/tree/master/wayback-cdx-server), multiple archived tweets on Wayback Machine to avoid opening each link manually. The app is a prototype written in Python with Streamlit and hosted at Streamlit Cloud.

Users can define the number of tweets displayed per page and apply filters based on specific years. There is also an option to filter and view only deleted tweets.

*Thanks Tristan Lee for the idea.*

## Community

>"Original way to find deleted tweets." — [Henk Van Ess](https://twitter.com/henkvaness/status/1693298101765701676)

>"This is an excellent tool to use now that most Twitter API-based tools have gone down with changes to the pricing structure over at X." — [The OSINT Newsletter - Issue #22](https://osintnewsletter.com/p/22#%C2%A7osint-community)

>"One of the keys to using the Wayback Machine effectively is knowing what it can and can’t archive. It can, and has, archived many, many Twitter accounts... Utilize fun tools such as Wayback Tweets to do so more effectively." — [Ari Ben Am](https://memeticwarfareweekly.substack.com/p/mww-paradise-by-the-telegram-dashboard)

>"Want to see archived tweets on Wayback Machine in bulk? You can use Wayback Tweets." — [Daily OSINT](https://twitter.com/DailyOsint/status/1695065018662855102)

>"Untuk mempermudah penelusuran arsip, gunakan Wayback Tweets." — [GIJN Indonesia](https://twitter.com/gijnIndonesia/status/1685912219408805888)

>"A tool to quickly view tweets saved on archive.org." — [Irina_Tech_Tips Newsletter #3](https://irinatechtips.substack.com/p/irina_tech_tips-newsletter-3-2023#%C2%A7wayback-tweets)

## Docs

- [Roadmap](docs/ROADMAP.md)
- [Changelog](docs/CHANGELOG.md)

## Development

### Requirement

- Python 3.8+

### Installation

$ `git clone git@github.com:claromes/waybacktweets.git`

$ `cd waybacktweets`

$ `pip install -r requirements.txt`

$ `streamlit run app.py`

Streamlit will be served at http://localhost:8501

## Contributing

PRs are welcome. Check the roadmap or add a new feature.

> [!NOTE]
> If the application is down, please check the [Streamlit Cloud Status](https://www.streamlitstatus.com/).