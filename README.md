# [Dang Hong Anh] Rakuten Travel Experiences - Demo UI
This is a demo interface based on the official website of Rakuten Travel Experiences (https://experiences.travel.rakuten.co.jp/), with the aim to deliver two key features: a map showing experience locations and a default sorting that prioritizes cultural experiences. Key techniques used in this project include JavaScript, HTML, CSS, basic REST APIs integration with aSQL database, Leaflet.js (1), OpenStreetMap tiles (2), and the use of Lucide icons (3).

## I. Features & Operations:
1. This is the Live Demo link:  https://danghonganh17905.github.io/dha-demo-interface/
2. Main features:
- Show of experiences on grid and on pop-up map according to search inputs;
- Default prioritization of cultural experiences and highlight cultural experiences on pop-up map;
- Pop-up map showing experiences locations and offer basic information on the sidebar;
- Guiding visitors with animation on the “Click to view Experiences on map” button.
3. Operations:
- Search bar:
  + Type either “Tokyo” or “tokyo” to show experiences available in Tokyo (the demo version includes data for Osaka and Fukuoka);
  + Type the name of experiences (“experience 1”, “Experience 1”, “travel pass 1”) to show the experiences;
  *In the search of locations, experiences with the “Cultural Experience” badge will be automatically prioritized.
  *In the search of experiences, even when only one experience is shown, the experience map is adjusted accordingly.
  *The preview of the map on the left sidebar will be adjusted according to search locations and experiences.
- Experiences map:
  - Click the “Click to view Experiences on map” button to open the map in the pop-up.
  - On the pop-up, click on any experience’ or travel pass’ marker to show details in the sidebar.
  *The map is adjusted according to search with a default (before search/no-result search) zoom to view the Japan region.

## II. Back-up Research:
- Rakuten Travel Experiences’ competitive landscape:
  + Rakuten Travel Experiences accounted for 2.4% usage of inbound tourists leaving Japan from Kansai Airport and being surveyed (5)
  + Provision of local and cultural specific experiences in Japan;
  + Provision of Transportation Passes.
- Main target of changes in this demo: Inbound tourists to Japan;
- Information & Indications:
  + In a survey with 2,228 inbound tourists leaving from Kansai Airport, 45% of them booked activities before departure to Japan (5)
  + 45 days before booking, travelers read 141 travel pages on average, 80% using Online Travel Agencies and 61% using search engines (research on the US customers) (6)
    ⇒ Wide opportunity for market penetration and complementary usage of multiple Online Travel Agencies;
    ⇒ Need of visible differentiations with other agencies.
  + 30% of tourists who want to experience anime locations/stages and 33% of tourists who watch sports said that they would pay 50% more to experience related activities (7)
    ⇒ Opportunity to earn premium price on specific experiences.
  + Regional Transportation Pass (such as Osaka Amazing Pass) are less known by inbound tourists. 64.2% of surveyed inbound tourists leaving Kansai Airport did not know about Osaka Amazing Pass. (5)
    ⇒ Opportunity to highlight the option and acquire customers.
- Recommendations:
  + Addition and highlight of “Cultural Experience” Badge to give differentiations to visitors (who have probably searched multiple other Online Travel Agencies), hence encouraging them to explore further;
  + Addition and highlight of “Travel Pass” Badge for convenient search and purchase of Transportation Pass;
  + Provision of experience map, giving convenience for visitors who have mainly used other Agencies or have booked activities on other Agencies to also include Rakuten Travel Experiences’ experiences on their plan;
  + Provision of experience map for visitors to book tours in foreign countries with less difficulties.

## III. Expected Outcomes:
1. Inbound tourists:
   - Increase exploration time of tourists on Rakuten Travel Experiences’ website (or reduce drop rate);
   - Increase first-time purchase (through complementary booking with visitors’ commonly-used other travel agencies and purchase of specific Japanese cultural experiences or travel passes).
2. Existing foreign buyers:
   - Increase exploration time (more convenience and differentiation);
   - Increase purchase value (booking nearby experiences).
3. Japanese users:
   - Increase satisfaction with nearby experience options;
   - Increase exploration and purchase of local and cultural experiences.

## IV. Key Techniques:
- Main usage: JavaScript,
- Basic use of REST APIs;
- Store SQL database on Supapase;
- Integration of OpenFreeMap map tiles using Leaflet.js.

## V. License & Acknowledgement:
(1) Leaflet.js (BSD 2-Claude “Simplified” License)
- In this project, Leaflet.js library is used to make interactions with maps.

(2) OpenStreetMap (Open Database License (ODbL))
- OpenStreetMap is used to provide map tiles and geographic data for the preview and pop-up map.

(3) Lucide Icons
- License: MIT
- Copyright (c) 2013-present Cole Bemis  
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

(4) All images used in this project are either taken free images from Canva or edit on Canva.
*All required License & Acknowledgement are also shown in the index.html file.

## VI. Back-up Research’s references:
(5) Osaka Convention & Tourism Bureau. (2025, October). 訪日外国人旅行者の動向把握にむけた関西空港出口調査 2025年度: 中間報告 [Kansai Airport exit survey for understanding trends among international visitors to Japan, fiscal year 2025: Interim report]. https://s3.ap-northeast-1.amazonaws.com/content.osaka-info.jp/downloads/2025/kix_cyuukan.pdf  
(6) Expedia Group. (2023). The path to purchase: Uncovering how travelers plan and book online. https://partner.expediagroup.com/content/dam/unified/partner/documents/reports/2023-reports/report-path-to-Purchase-2023-final_en-us.pdf  
(7) Development Bank of Japan & Japan Travel and Tourism Foundation. (2026, November 11). アジア・欧米豪 訪日外国人旅行者の意向調査 2026年度版 [Survey on the intentions of international travelers to Japan from Asia, Europe, the United States, and Australia: Fiscal year 2026 edition]. https://www.jtb.or.jp/wp-content/uploads/2026/11/report-DBJ-JTBF-asiaeuro-survey-2026.pdf
