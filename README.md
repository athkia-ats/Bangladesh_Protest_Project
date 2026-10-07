# Hashtags and Uprising in Bangladesh, July 2024

An interactive dashboard on how the 2024 Bangladesh quota reform movement appeared on TikTok and Facebook during the 30 days from 7 July to 5 August 2024, the period that ended with Prime Minister Sheikh Hasina's resignation.

It combines post-level data, a hashtag co-occurrence network and a hand-coded qualitative assessment in a single HTML file.

| Posts in the dashboard | TikTok videos | Facebook posts | Shares and comments |
|---|---|---|---|
| 1,441 | 410 | 1,031 | 2.2M |

## Viewing the dashboard

Open `index.html` in a browser, or host it with GitHub Pages:

1. Put `index.html` in the root of the repository.
2. In the repository's **Settings**, open **Pages** and deploy from the main branch.

The page loads Chart.js and its fonts from public CDNs, so it needs an internet connection. All data is embedded in the file.

Each page has its own address ending, so you can link straight to it: `#context`, `#map`, `#eng`, `#net`, `#qual`, `#pub`.

## What the dashboard contains

| Page | Contents |
|---|---|
| Context | A playable day-by-day timeline pairing key events with each day's posts, engagement, leading hashtags and most shared post; summaries of hashtag and engagement patterns; notes about the data. |
| Division map | Bangladesh's eight divisions shaded by how often post captions name a place in each, with a button per division and a detail panel. |
| Posts and engagement | Platform and custom date filters; daily posts; moving average, cumulative and reach trends; hashtag-by-day heatmap; top hashtags; most shared posts. |
| Hashtag network | Interactive co-occurrence networks for Facebook (1,189 hashtags, 12,372 links, 13 communities) and TikTok (881 hashtags, 8,412 links, 21 communities). |
| Qualitative assessment | Method, summary of findings, sortable and filterable tables for intra-actions and interactions, and the 18-code codebook. |
| Publications | The three outputs listed below. |

## Data and cleaning

| Platform | Raw rows | Unique posts | In 7 Jul to 5 Aug | Kept | How it was cleaned |
|---|---|---|---|---|---|
| TikTok | 2,998 | 2,709 | 447 | 410 | Duplicates merged; every post in the window read by hand and unrelated ones removed. |
| Facebook | 1,114 | 1,042 | 1,042 | 1,031 | Duplicates merged; 11 unrelated posts removed by keyword check, not a full manual read. |

Posts were collected by searching protest hashtags, so the figures describe this sample and not all activity on either platform. Engagement figures are totals at the time of collection.

## Main observations

- **Posting follows the protest's stages.** 47 posts on 7 to 14 July, 312 during the crackdown of 15 to 20 July, 143 during the pause of 21 to 28 July, and 939 (65% of all posts) from 29 July to 5 August.
- **The hashtags shift from reform to resignation.** #stepdownhasina is the most used protest hashtag (473 posts) and rises from 10% of posts up to 20 July to 40% from 29 July.
- **Engagement is concentrated at the end, and on TikTok per post.** The final stage holds 47% of shares and comments. A TikTok video averages 3,315 shares and comments against 802 for a Facebook post, although Facebook has 2.5 times as many posts.
- **Dhaka dominates the places named.** 484 posts (34%) name a place; Dhaka division is named in 285, Chattogram in 73 and Rajshahi in 37.
- **The platforms were used differently.** In the coded sample (120 posts, 6,000 comments), Facebook posts lean towards conflict (36.7%) and propagation (35.0%), while TikTok posts lean towards propagation (38.3%) and solidarity (31.7%). Facebook comments are led by calls for justice (23.7%); TikTok comments by encouragement (32.7%) and emoji-style responses (19.6%).

## Qualitative method in brief

Posts were collected with the 42 hashtags identified by Subat and Fichman (2025), through searches between 1 and 20 October 2025. The wider corpus held 11,311 Facebook posts with 268,817 comments and 418 TikTok posts with 384,548 comments. The two most engaged posts per day on each platform, and 50 comments under each, were coded by two researchers. Intercoder agreement was 81.1% for posts and 84.2% for comments.

## Limitations

- All dates and times are in UTC, so a post made in the early hours in Bangladesh (UTC+6) falls on the previous calendar day.
- The map shows places that posts talk about, not where they were posted from, and its division outlines are approximate.
- The hashtag network was built separately from the cleaned post data, so its counts may differ slightly from the other pages.
- The qualitative results are not yet broken down by date.

## Publications

1. Subat, A., & Fichman, P. (2026). The hashtag revolution: Political trolling during the 2024 Gen Z revolution of Bangladesh. *Online political trolling*. New York: Bloomsbury Libraries Unlimited. [Click here](https://books.google.ru/books?hl=en&lr=&id=clEDEgAAQBAJ&oi=fnd&pg=PT6&ots=QMKV5Nl9qE&sig=mUkCeer00LNO5HlqRvh8ObFeU2I&redir_esc=y)
2. Subat, A., & Fichman, P. (2026). #StepDownHasina lead the discursive dynamics of the July 2024 quota protest in Bangladesh: Hashtag activism and collective action on Facebook and TikTok. *IC2S2*, July 28–31, 2026.
3. Subat, A., & Fichman, P. (2025). How do hashtags impact history? The use of social media in the 2024 Bangladeshi Gen Z revolution. *AMCIS 2025 Proceedings*, August, 10. [Click here](https://www.researchgate.net/profile/Athkia-Subat/publication/399667653_How_do_hashtags_impact_history_The_use_of_social_media_in_the_2024_Bangladeshi_Gen_Z_revolution/links/6964755121a46d6f701febbd/How-do-hashtags-impact-history-The-use-of-social-media-in-the-2024-Bangladeshi-Gen-Z-revolution.pdf)

## Sources and credits

- Background on the protest: Chughtai, A., & Ali, M. (2024, August 7). [How Bangladesh's 'Gen Z' protests brought down PM Sheikh Hasina](https://www.aljazeera.com/news/longform/2024/8/7/how-bangladeshs-gen-z-protests-brought-down-pm-sheikh-hasina). Al Jazeera.
- Division boundaries: geoBoundaries (CC BY 4.0; Bangladesh Bureau of Statistics / OCHA), via the `bd-geojson` package.
- Charts: Chart.js.

## Contact

Athkia Subat, Indiana University Bloomington
