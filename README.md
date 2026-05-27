# Shigou (四郷)

# Shigou is a text-based, atmospheric exploration RPG built in Twine (Harlowe 3). Set in a decaying, snow-buried former coal mining city, the game blends resource management, exploration, and rich historical narrative. As one of the few remaining youths in the city, you must manage your time and stamina to uncover the lost memories (Scraps) of Shigou's golden age before the harsh winter completely erases them.

# 

# Overview

# Genre: Interactive Fiction / Text-Adventure RPG

# 

# Engine: Twine (Harlowe 3.3.x)

# 

# Theme: Post-Industrial Decay, Melancholy, Exploration, Memory

# 

# Core Systems

# Deepening the SimulationStamina \& Recovery: We implemented a "Risk-Reward" cycle. Sleeping restores 25 + 0.1 (Lost Stamina) Stamina. This rewards players for exploring further and pushing their limits.



# Nutritional Cooldown: Eating ramen is twice as efficient as sleeping for Stamina recovery, but is limited to a 4-hour cooldown. This forces players to manage their time strategically rather than "spamming" food to negate the game's difficulty.



# Realistic Movement: Movement speed isn't just a flat number. We introduced a "Non-linear Distance Coefficient." This coefficient is inversely proportional to the travel distance, simulating how fatigue and terrain friction make longer journeys proportionally more difficult, adding a layer of realism to the snowy traversal.

# 

# Anti-Handholding: The game is intentionally designed with minimal explicit guidance. Most locations offer multiple avenues of exploration, encouraging players to get lost in the city and discover its secrets organically.

# 

# The Scrap Economy \& Difficulty: Collecting Scraps is the primary objective, serving as both mechanical buffs and the metric for unlocking the true ending.

# 

# Accessibility vs. Challenge: While there are 30 Scraps in total, 26 are obtainable in a single playthrough. Of those, 22 are simple to acquire without complex prerequisites. Since the ending only requires collecting 50% of the total Scraps (15), the narrative remains highly accessible to players of all levels. However, probability-based and condition-locked Scraps ensure that players who enjoy the thrill of puzzle-solving still have plenty to uncover.

# 

# Buff Balancing \& Reality: The mechanical buffs granted by each Scrap are entirely subjective, scaled according to their acquisition difficulty and my personal valuation of the memory. While the core philosophy aims to depict the harsh reality of a city like Yubari, inevitable inaccuracies and romanticized elements exist to serve these gameplay and narrative constraints.



# World Building \& Mapping:

# The city map is a reconstruction based on Yubari, Hokkaido. I used Mapbox to capture 21 distinct satellite snapshots, which were then stitched together in Photoshop to create a world map.

# 

# Linguistic \& Thematic Choices

# Nomenclature Ambiguity: The naming conventions in the game were designed with intentional cross-linguistic ambiguity. Names like Shigou, Dan, Mai, Shun, and Kaba function perfectly as Japanese romaji, but they can also be read as valid Chinese Pinyin (石沟, 丹, 麦, 瞬, 卡巴).

# 

# Musical \& Visual Influence: The game's overarching melancholy and the conceptualization of the ending were heavily influenced by Susumu Hirasawa's song "Byakkoya no Musume" (The Girl in Byakkoya). This is why the song serves as the unskippable ending anthem. The final image displayed during the end credits is a night view of Sapporo—chosen because the glowing, living city perfectly aligns with the imagery and lyrics of the ending theme, acting as a stark contrast to the frozen ruins of Shigou.

# 

# Location Design Case Studies (Human-Led Design)

# While AI was utilized to enrich atmospheric descriptions and context for minor locations based on real-world data, the core locations and narrative beats were entirely human-designed:

# 

# Old Middle School (OMS):

# 

# Design Rationale: The abandonment and sharing of school campuses reflect the historical reality of shrinking student populations in regional Japan.

# 

# Layout: OMS features a two-building layout (Gym/Auditorium + 4-story Classroom Building) and a sports field, perfectly matching the Mapbox satellite shape. The interior strictly follows standard Japanese educational architecture, including the indispensable club rooms (bukatsu).

# 

# Narrative Anchors: Baseball was a ubiquitous recreational activity for historical Yubari miners, who often shared school fields (hence the Birch Baseball Bat Scrap). The graduation ceremony was the last event held in the auditorium before relocation; leaving the decorations untouched emphasizes a "frozen in time" aesthetic. In the classrooms, the "We Graduated" blackboard art is a direct homage to bittersweet graduation traditions I personally witnessed in Chinese public primary schools. The administrative offices contain old photos and merger documents to ground the history.

# 

# Civic Center:

# 

# Design Rationale: A very common community facility. Here, players can easily find 4 Scraps, plus a special trigger item for a hidden Scrap (as seen in the demo video). All entertainment activities referenced here are based on the historical leisure activities of actual coal miner communities.

# 

# Old Upper District Station:

# 

# Design Rationale: The encounter with the old man is a multi-layered narrative homage. His story and dialogue are completely faithful to an interview with an elderly local resident at the old Yubari Station, captured by a travel vlogger. The dialogue underwent a rigorous double-translation process: Original Japanese -> Chinese translation -> Final English adaptation.

# 

# 🧩 The Scrap Compendium (Easter Eggs \& Neta)

# Almost every Scrap in the game features a specific cultural, historical, or pop-culture reference:

# 

# Historical \& Cultural References

# The Winter Gentian: The Gentian flower is a prominent part of the Mon (crest) of the Minamoto clan, Japan's most illustrious samurai clan. Added as a piece of historical trivia.

# 

# The Red Handkerchief: A nod to the classic Japanese film The Yellow Handkerchief (famously set in Yubari).

# 

# Birch Baseball Bat: Emphasizes baseball's massive cultural dominance in Japan, especially in historical blue-collar and mining towns.

# 

# Worn Ebony Go Bowls, Creased Shogi Board \& Hand-drawn Shigou Chess Rules: Go, Shogi, and Sugoroku (board games) were highly popular pastimes among the working-class miners.

# 

# SSO Junior Team Racing Bib: Based on the real-world Yubari TOTAL SKI ORGANIZE.

# 

# Kimun's Makiri: Highlights the history and craftsmanship of the indigenous Ainu people of Hokkaido.

# 

# Seong-jin's Wooden Goose: Represents the dark history of forced labor during Japan's imperial expansion. While Chinese laborers were considered for the narrative, Korean conscripts were historically much more numerous in Hokkaido's mines, and many remained and settled there after the war, making Seong's story historically authentic.

# 

# Sadao's Harmonica: Represents the everyday, musical life of the coal miners.

# 

# Hospital Grand Opening Photo, 7-Year-Old Graduation Photo, Shigou Middle School Grand Opening Photo, Mine Operation Log Fragment: Pure world-building to ground the city's infrastructure and industrial history.

# 

# Music \& Pop-Culture

# To Love's End: Named after the iconic Inuyasha soundtrack piece (Affections Touching Across Time).

# 

# Deep in Abyss: Named after the Made in Abyss Season 1 opening theme. Thematically tied to the act of mining, descending into the earth, and the drama clubs that miner communities formed.

# 

# Money, Money, Money, Must Be Funny: A direct reference to the classic ABBA song.

# 

# The Red Ribbon \& Caramel Custard: A reference to the Monogatari Series: Off \& Monster Season opening theme, "Caramel Ribbon Cursetard."

# 

# Oh, Buddha—Have You Fallen Asleep?: A meme reference to Ninja Slayer.

# 

# Ah, Alive Again: A reference to the Cookie☆ (KNN) internet meme.

# 

# Heart of Iron: A nod to the grand strategy game Hearts of Iron IV. Fittingly, it grants a +4 Movement Speed buff.

# 

# The Coal Mine Song: A reference to Tanko Bushi, the traditional Japanese folk song about coal mining.

# 

# Lotus Blooming for You: A reference to Susumu Hirasawa's song Lotus (utilizing the lotus imagery present in both Lotus and Lotus-2).

# 

# Miscellaneous

# The Last Movie Ticket: Included simply because the aesthetic of finding a final ticket in an abandoned theater felt incredibly cool.

# 

# Wo Ai Ni: A reflection of how the Chinese phrase "Wo Ai Ni" (I love you) is recognized and used in Japanese pop culture.

# 

# The Cross: Designed for architectural realism and symmetry; if the town has a Buddhist Temple, it should naturally have a Christian Church. Nothing strictly supernatural about it.

# 

# Kaba Bear: Bears are iconic to Hokkaido (though rare in deep winter). "Kaba" also translates to "Birch" (樺), serving dual linguistic purposes.

# 

# La Dernière Classe: A reference to Alphonse Daudet's famous short story, The Last Class, fitting the melancholic theme of a dying school.

# 

# Like a Dream: Chosen simply because the name perfectly captures the atmosphere of the abandoned train station.

# AI Contribution

# This project was developed with Gemini 3.1.

# 

# Narrative \& Core Design: The plot, character arcs, and all major emotional beats were written entirely by the human designer.

# 

# AI as a Polish/Translation Tool: Since my draft writing was in Chinese, AI was utilized to translate and polish the text into natural-sounding, atmospheric English.

# 

# Content Expansion:

# 

# Important Locations: I designed the primary narratives and structural descriptions; AI was then tasked with enriching the atmospheric "environmental storytelling" details.

# 

# Minor Locations: For non-critical points of interest (eg. Fire Department), I provided the narrative direction and cultural context, while AI helped rapidly synthesize historical/technical details based on real-world references.

# 

# How to Play

# Download the shigou.html file and the images/ folder.

# 

# Keep the images/ folder in the same directory as the .html file.

# 

# Open shigou.html in any modern web browser.

# 

# Note on Save/Load: Your progress is stored locally in your browser. Use the Save and Load buttons in your Apartment to ensure your progress is preserved between sessions.

# 

# Debugging/Evaluation

# System Override: In your Apartment, click "Access" on the Desk Lamp and enter the passcode: SHIZUKU. This grants all standard Scraps for testing purposes.

# 

# Easter Eggs: Entering specific names at the Coal Museum Mine Registration unlocks unique hidden Scraps.

# 

# Writing, Design, and Programming: Alex Zhu

# Ending Theme: "Byakkoya no Musume" (白虎野の娘) by Susumu Hirasawa.

