#### Week 9 Lab Report - Julie Nguyen
# Lab Report 5 - Lab Report 3: Researching Commands

## Researching Commands - `grep` Command

## Finding 4 Interesting Command-Line Options/Alternative Ways To Use `grep`

### 1. `grep -c`
- `-c` counts the amount of times a string pattern appears in a file like in a `.txt` file.
- `-c` is short for the word `count`!
- This is useful because it allows you to see how many times a string pattern/word appears in a file.

- `grep -c` Command Input - Example 1
```
$ grep -c and Algarve-WhatToDo.txt
```
- Output
```
42
```
- Here, the output displays the amount of times the word `and` appears in the `Algarve-WhatToDo.txt` file.

- `grep -c` Command Input - Example 2
```
$ grep -c and Canada-WhereToGo.txt 
```
- Output
```
413
```
- Here, the output displays the amount of times the word `and` appears in the `Canada-WhereToGo.txt` file.

### 2. `grep -v`
- `-v` stands for invert-match, where it returns every other line other than the specified string pattern.
- For example, you can have it return an entire chapter's text without the chapter's title in a `.txt` file for instance.
- This is useful because it allows you to read everything else other than the word/string pattern you do not want to see in the file.

- `grep -v` Command Input - Example 1
```
$ grep -v and Canada-WhereToGo.txt 
```
- Output
```
WHERE TO GO
Where
When
One of the great advantages to Canada’s vast size is that, apart from a couple of major tourist attractions such as Niagara Falls, it’s never overcrowded. Even in high summer there’s still plenty of room for everybody. Nonetheless, it is advisable to make advance bookings for some resort hotels on the Pacific coast, in the Rockies, or around the Great Lakes.
How
ONTARIO
Toronto
Waterfront Area
Heart of Downtown
The Ethnic Neighborhoods
Museums
Black Creek Pioneer Village
Niagara Peninsula
Niagara Falls
Niagara-on-the-Lake
Stratford
Point Pelee National Park
In the spring, the great sport is fishing for smelt during their spawning run, ending the day with a communal fish-fry on the beach. In September, even before the leaves turn, trees go bright orange with the wings of millions of Monarch butterflies on their way to Mexico.
Georgian Bay
Thunder Bay
Ottawa
Parliament Area
Sussex Drive
Museums
Gatineau Park
Eastern Ontario
Upper Canada Village
Kingston
QUEBEC
Montréal
Mount Royal
Old Montréal
Across the rue Notre-Dame, the 19th-century Hôtel de Ville (City Hall) is built in the imposing style of the French Renaissance. It was from the balcony beneath the clock in 1967 that General de Gaulle delivered his incendiary cry of “Vive le Québec libre!,” warming the hearts of local separatists. The general was not intimidated by the statue of Lord Horatio Nelson watching him from the top of Place Jacques-Cartier. Montréal’s oldest monument was somewhat provocatively erected in 1809, just four years after the British admiral’s devastating defeat of the French at Trafalgar.
Downtown
Even if you’re not staying here, the ritzy Ritz-Carlton Hotel makes a fine rendezvous for a restful or bracing cocktail in mid-sightseeing. Opposite the McCord Museum of local history (see page 106), McGill University is Montréal’s internationally renowned English-speaking university.
Montréal’s Neighborhoods
Olympic Park
St. Lawrence River
Museums
Eastern Townships
The Laurentians
The heart of the resort area is within an easy 90-minute to 2-hour drive from the city for a weekend or longer stay. Motorway 15 northwest from Montréal, then Highway 117 take you into forested foothills immediately beyond the metropolis.
Québec City
Whereas Montréal has become increasingly “Americanized,” the provincial capital remains unmistakably, even defiantly Québécois, if not downright “French.” It’s difficult to miss, in this proud cradle of New France, that the town is borrowing a leaf from the book of the modern French republic by calling its provincial parliament the Assemblée Nationale. Only one percent of the population of 664,000 do not speak French. 
Upper Town
Set back behind tall trees off the rue des Jardins, the Anglican Holy Trinity Cathedral of 1804, with its elegant spire, will be familiar to Londoners for its respectful imitation of St. Martin-in-the-Fields. Notice inside the solid old pews of English oak.
Lower Town
Beyond the City Wall
Côte de Charlevoix
At the northern edge of town, turn right after the Montmorency River bridge into a park where a terrace overlooks the impressive Montmorency Falls, plunging 91 m (274 ft) into the river.
Gaspé Peninsula
THE ATLANTIC
Nova Scotia
You’d think the chamber of commerce carved their map as a public relations gimmick, but the province really is shaped like a lobster. In any case, many a gourmet or glutton feels that a Halifax lobster dinner is reason enough to make the trip. But weight watchers can enjoy Nova Scotia, too.
Halifax
Atlantic Coast
Annapolis Valley
You are plunged into the atmosphere of that “moment in time” as soon as you get off the park bus at the Georges des Roches fishing property, a long turf-roofed log cabin outside the fortified town. The men may be laying out dozens of cod to dry on what are known as flakes, the same trestled wooden racks still used in fishing villages all down the coast. At the drawbridge to Porte Dauphine, the main entrance gate bearing a relief of three fleurs-de-lys, the French royal coat of arms, you’ll be stopped by French soldiers to check whether you’re a British spy.
Charlottetown
Blue Heron Drive
Lady Slipper Drive
Kings Byway Drive
New Brunswick
Saint John
Bay of Fundy
Fredericton
St. John’s
Local folklore insists that the name (not to be confused with Saint John, New Brunswick) comes from the saint’s day of John the Baptist, June 24, when John Cabot arrived here in 1497.
On the north side of the hill, Quidi Vidi (pronounced Kiddy Viddy) is a charming little fishing port with excellent seafood restaurants. On the first Wednesday in August, St. John’s Regatta, a race for six-oar rowing boats, is held on Quidi Vidi Lake. Begun in the 1820s, this oldest continuing sporting event in North America is also the occasion of a boisterous carnival.
Avalon Peninsula
BRITISH COLUMBIA
Vancouver
The city’s setting in a magnificent bay embraced by soaring green mountains is one of those blessings that can turn any hard-boiled atheist into a believer. Cynicism dissolves with your first taste of the town’s gentle ambience, created by a clever combination of the comforts of sophisticated modernity with the simpler joys of the wilderness at its back door.
First View
You’ll find the information office of Tourism British Columbia, at 865 Hornby Street, useful for details about the province. For the city, Greater Vancouver Convention & Visitors Bureau is at 200 Burrard Street, Plaza Level.
Downtown
Stanley Park
English Bay
Squamish Highway
Victoria
Reasonably enough, the Parliament grounds include a bronze statue of Queen Victoria. It was she who chose the name of British Columbia — over New Caledonia, New Hanover, New Cornwall, or New Georgia. There is also a cenotaph, which is the focus of the annual mid-September Battle of Britain Parade. You can easily get the impression that this town is only nominally in Canada.
About 20 km (12 miles) from Parksville, look for a signpost to Little Qualicum Falls. The well-marked walk loops around the upper falls tumbling into a ravine, then follows the river rapids along to the lower falls that crash into another rocky gorge. You can extend the hike along the river for a picnic or bracing swim at Cameron Lake.
Okanagan Valley
Rocky Mountains
Mount Revelstoke
The Trans-Canada continues through the jagged mountains of Glacier National Park, which counts over 400 glaciers within its boundaries. Rogers’ Pass was named after the major who found this corridor in 1882, thus enabling the C.P.R. to cut through the avalanche-prone Selkirk Mountains. It was also the toughest obstacle to clear for completion of the Trans-Canada Highway in 1962.
Yoho National Park
Back on the Trans-Canada, the turn-off 6 km (31/2 miles) after Field takes you past the park information center to a steep winding route through the pine forests of the Yoho Valley. Signposted on the right, 13 km (8 miles) into the valley is a short walk to the foot of the spectacular Takakkaw Falls. Takakkaw is an Indian word for “magnificent,” a fair description of the waters spilling out of the outflow of the Daly Glacier. Unlike many waterfalls, this one is at its most spectacular on the hottest summer afternoons, when the glacier ice melts. For a panoramic view of the glacier, take the Highline Trail 1 km (1/2 mile) south of the falls, starting out from the Whiskey Jack Hostel.
Lake Louise
For a view of the whole area, take the cable car from Lake Louise up Mount Whitehorn.
Banff National Park
Icefields Parkway
Inside Jasper National Park, put on good rubber or crepesoled shoes to walk out onto the ice of Athabasca Glacier, part of the Columbia Icefield. You can also venture onto the ice sheet in a snowmobile. Note the rock debris or rubble (moraine in the language of glaciologists) in front of the glacier showing that the Athabasca is retreating — a hundred years ago it reached to the other side of the Parkway. At the Parkway’s Kilometer 200 mark, take Highway 93A to Athabasca Falls. A comfortable boardwalk leads you on an informative nature walk right up to where the mighty river plunges over the narrow gorge.
Alberta
Calgary
Drumheller
Edmonton
Saskatchewan
Regina
Manitoba
Winnipeg
The old French-speaking community of St-Boniface, now a Winnipeg suburb, is on the east side of the Red River. Its Avenue Taché boasts the city’s oldest building, the 1846 convent of the Grey Nuns. It’s now the parish museum, devoted in part to the life of Louis Riel. Next door, you’ll find his simple grave in the cemetery of St-Boniface basilica, rebuilt behind its white stone façade after a recent fire.
Churchill
THE NORTH
The Yukon
Whitehorse
Dawson City
Kluane National Park
Northwest Territories
Yellowknife
Wood Buffalo National Park
Auyuittuq National Park
```
- Here, the output displays every line that does not contain the word/string pattern `and` in the `Canada-WhereToGo.txt` file.

- `grep -v` Command Input - Example 2
```
$ grep -v the Canada-WhereToGo.txt 
```
- Output
```
WHERE TO GO
Where
When
How
ONTARIO
Toronto
Waterfront Area
Heart of Downtown
Queen’s Park and Yorkville
The Ethnic Neighborhoods
Museums
Black Creek Pioneer Village
Niagara Peninsula
Niagara Falls
Stratford
Point Pelee National Park
Lakes Huron and Superior
Georgian Bay
Thunder Bay
Ottawa
Parliament Area
Sussex Drive
Museums
Gatineau Park
Eastern Ontario
Upper Canada Village
Kingston
Thousand Islands
QUEBEC
Montréal
Mount Royal
Old Montréal
Downtown
Montréal’s Neighborhoods
Olympic Park
St. Lawrence River
Museums
The dazzling Village Street, West Indies, by Montréal’s James Wilson Morrice (1865–1924), is a fine work by this most celebrated of Canada’s expatriate painters. A friend of Matisse, he worked principally in Europe and North Africa.
Eastern Townships
The Laurentians
Québec City
Upper Town
Lower Town
Côte de Charlevoix
Gaspé Peninsula
THE ATLANTIC
Nova Scotia
Halifax
Atlantic Coast
You’ll find more deserted coves and beaches around St. Margaret’s Bay as you drive on to Chester, 79 km (49 miles) west of Peggy’s Cove on Mahone Bay. This fashionable resort town was founded in 1759 by Massachusetts fishermen and remains a favorite vacation spot for New Englanders.
Annapolis Valley
Cape Breton Island
Prince Edward Island
Charlottetown
Blue Heron Drive
Lady Slipper Drive
Kings Byway Drive
New Brunswick
Saint John
Bay of Fundy
Fredericton
Newfoundland
St. John’s
Avalon Peninsula
BRITISH COLUMBIA
“Such a land,” said Rudyard Kipling in 1908, “is good for an energetic man. It is also not bad for a loafer.” That’s still true today.
Vancouver
First View
Downtown
The section of Robson Street between Burrard and Bute streets is known as Robsonstrasse. Now it has lost its distinctively German character to become a cosmopolitan restaurant row offering Vietnamese, Japanese, Scandinavian, Italian, and French cuisine. Fresh seafood is a great attraction.
Stanley Park
English Bay
Squamish Highway
Victoria
Vancouver Island
Fraser and Thompson Canyons
Okanagan Valley
THE ROCKIES AND PRAIRIES
Rocky Mountains
Mount Revelstoke
Yoho National Park
Lake Louise
Banff National Park
Icefields Parkway
Alberta
Calgary
Drumheller
Edmonton
Saskatchewan
Regina
Manitoba
Winnipeg
The Winnipeg Art Gallery, in a strikingly designed angular structure at 300 Memorial Boulevard, has an interesting permanent collection of modern Canadian and American artists, Inuit sculpture, and usually first-rate seasonal exhibitions.
Churchill
THE NORTH
The Yukon
Whitehorse
Dawson City
Kluane National Park
Northwest Territories
Yellowknife
Wood Buffalo National Park
Auyuittuq National Park
```
- Here, the output displays every line that does not contain the string pattern `the` in the `Canada-WhereToGo.txt` file. Notice how it still returns the string pattern `The` despite it being the same word but difference in capitalizing the `t`.

### 3. `grep -n`
- `-n` stands for line-number, where it returns the line number that the string pattern is found in the file.
- For example, you can have it return the line-number of an important quote from a `.txt` file.
- This is useful because it allows you to find the line-number of any specific string pattern you are looking for in the file.

- `grep -n` Command Input - Example 1
```
$ grep -n 1848 ch10.txt
```
- Output
```
5:A specter is haunting Europe,” Karl Marx and Frederick Engels wrote in 1848, as the first sentence of The Communist Manifesto. The specter they had in mind eventually became a political movement that came to dominate nearly half the world in the twentieth century. Behind this movement, however, lay an even more powerful idea that Marx had inspired—a Marxist conception of reality. The marketplace of economic relationships is not what it seems to be. Workers enter into seemingly voluntary contracts with employers, but underlying this system of apparent cooperation is a vast system of exploitation. Those who hold capital reap profits off the backs of those whom they hire as their laborers. This generates a dynamic of history that should, according to the theory, eventually produce a revolution by the exploited class of laborers. This theory failed to recognize the just contribution of capital in generating the opportunity to work, and the political incarnation of Marxism turned out to be historically more transient than expected. Nonetheless, the insight remains with us that relationships of employment—indeed all forms of relationship—require more than nominal consent to be legitimate. Behind the appearance of voluntary interaction there lurks the ever-present possibility of unjust exploitation.
```
- Here, the output displays the line0number that the string pattern `1848` is found in Fletcher's `ch10.txt`.

- `grep -n` Command Input - Example 2
```
$ grep -n Exodus ch10.txt
```
- Output
```
40:Freedom of contract enables individuals to express their personhood, but it also facilitates relationships of oppression, including “slavery and involuntary servitude.” After all, it is possible to choose to enter into a contract of slavery. The book of Exodus permits the purchase of a Hebrew slave, but after six years of service “he shall go out free, for nothing.”10 Yet, there are people, the Bible recognizes, who prefer the condition of servitude:
45:There are two distinct grounds on which the law might sensibly prohibit the possibility recognized in Exodus. First, the claim might be that freedom and its blessings represent a great gift that no individual “made in God’s image” should be able to forfeit as though it were a disposable piece of property. Alternatively, the argument might be that in principle people have the right to choose to forego their freedom, but that in reality these choices are always influenced by personal necessities that becloud the choice actually made. This is especially true under market conditions, where the need for sustenance can drive people into relationships that they would not choose in and of themselves. It is clear that even the choice of the Hebrew slave discussed in Exodus can never be shown to be completely free. The legal arrangements also stipulate in the same passage that if during his period of servitude the slave acquired a wife or children, then he must leave them behind when he leaves his master’s service. Some purchased servants might decide to opt for permanent servitude simply because they cannot bear to live without their wives and family. The full text in the quoted passage reads: “I love my master, my wife, and my children, I will not go out free.”12 The cruelty of subjecting him to the choice between freedom and leaving his family obviously means that his choice is not free in any meaningful sense.
```
- Here, the output displays the line-number that the string pattern `Exodus` is found in Fletcher's `ch10.txt`.

### 4. `grep -r`
- `-r` will return recursively all the files in the directory that contains the string pattern.
- For example, you can have it return the file that a specific word/string pattern is in.
- This is useful because it allows you to find the file(s) that contains the string pattern that you are looking for.

- `grep -r` Command Input - Example 1
```
$ grep -r Rudyard
```
- Output
```
Canada-WhereToGo.txt:“Such a land,” said Rudyard Kipling in 1908, “is good for an energetic man. It is also not bad for a loafer.” That’s still true today.
```
- Here, the output displays the file(s) and sentence(s) that contains the string pattern `Rudyard` in the `berlitz2` directory.

- `grep -r` Command Input - Example 2
```
$ grep -r Vietnam
```
- Output
```
Bali-WhereToGo.txt:At Pura Penataran Sasih, a great hollow bronze drum cast in one piece and 11⁄2 m (5 ft) across, stands high up on a platform at the back of the temple. The style is typical of the Dong-son Bronze Age dynasty of Vietnam dating from about 300 b.c., but whether it was brought to Bali or made here is unknown. According to legend, it fell from the sky. A section was broken out of it at some time, and only the geometric patterns are visible from ground level: Decoration not in view includes faces with staring eyes.
Canada-WhereToGo.txt:B.C.’s population (4,000,000) is concentrated around the Strait of Georgia and along the U.S. border, with scarcely any inhabitants at all north of Prince Rupert. The people are still mainly British in origin, most of them Scottish. Other European immigrants are German, Dutch, Greek, Ukrainian, Italian, Scandinavian, and a few French. Native peoples number about 82,000. From across the Pacific, the province has attracted a large Asian community — Chinese, Japanese, and, of more recent arrival, Vietnamese, Pakistanis, and Indians.
Canada-WhereToGo.txt:The section of Robson Street between Burrard and Bute streets is known as Robsonstrasse. Now it has lost its distinctively German character to become a cosmopolitan restaurant row offering Vietnamese, Japanese, Scandinavian, Italian, and French cuisine. Fresh seafood is a great attraction.
China-WhereToGo.txt:Tourists are so numerous in the otherwise relaxed shopping district of Guilin that the pedestrian crossings have signs in English as well as Chinese. Another cosmopolitan influence comes from the area’s many minority peoples: Guilin is part of the Guangxi-Zhuang Autonomous Region, which borders Vietnam. The proliferation of so-called Muslim restaurants is explained by the presence here of thousands of people of the traditionally Muslim Zhuang nationality, China’s largest minority group. 
Paris-WhereToGo.txt:Come back to life on the old streets behind the Panthéon, where the bustling rue Mouffetard and its offshoots are a village within the city. The stalls of the morning market (see page 85) are piled with appetizing produce. Here and in the tiny place de la Contrescarpe you will find a large choice of ethnic restaurants, especially Thai, Vietnamese, and Chinese.
```
- Here, the output displays the file(s) and sentence(s) that contains the string pattern `Vietnam` in the `berlitz2` directory.

#### All of command-line options/alternative ways to use `grep` were found through the terminal's manual in the command `man grep`.
