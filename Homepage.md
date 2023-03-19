
---
cssclass: dashboard
banner: "![[cro.png]]"
banner_lock: false
banner_y: 0.42601
---

# Work
- 💼 Projects  
	-  [[Secret_Project]]
	- [[Top_Project]]
	- [[Fake Project 3]]

- 💰 Budget review
	- [[Q1 2022]]
	- [[Q2 2022]]
	- [[Q3 2022]]
	- [[Q4 2022]]

- 💆‍♂️ Tasks
	- ✅ `$=dv.pages('').file.tasks.where(t => t.completed).length`
	- 🚧 `$=dv.pages('').file.tasks.where(t => !t.completed).length`
	
- 🗄️ Daily Notes
 `$=dv.list(dv.pages("#diary").sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`

# Private
- 🏈 Sunday Game
	- [[Spicy-Sweet Buffalo Popcorn]]
	- [[Guest list]]
	- [Jalapeno Popper Wantons](https://www.allrecipes.com/recipe/166991/jalapeno-popper-wontons/)
- 👨‍👩‍👦 Objectives
	- [[Family Recipes]]
	- [[Family Calendar]]
	- [[Education Plan]]
	- [[Yearly Budget]]
- 🌅  Bills
	- [[Electricity]]
	- [[Water]]
	- [[Heating]]  
- 🎥 Movies to Watch
	- [Sleepless in Seattle](https://www.imdb.com/title/tt0108160/)
	- [Joe vs the Volcano](https://www.imdb.com/title/tt0099892/)

 # Bookmarks
 - 🏡 Obsidian
	 - [[README]]
	- [Obsidian Task Quick Refference](https://obsidian-tasks-group.github.io/obsidian-tasks/quick-reference/)
	-  [Obisidian core principles](https://tfthacker.medium.com/obsidian-understanding-its-core-design-principles-7f3fafbd6e36)
	  
- 📚 News
	- [CNN](https://www.cnn.com)
	- [Index.hr](https://www.index.hr)

- 🏈 Sport
	- [Gol.hr](https://www.gol.hr)
	
- 📚 IoT
	- [IoT Insights](http://iotinsights.com)
	- [Byte Lab](www.byte-lab.com)


# Vault Info
- 🗄️ Recent file updates
 `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`
- 🔖 Tagged:  favorite 
 `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(4).file.link)`
 - ℹ️ My Manuals
	 - [[README]]
- 〽️ Stats
	-  File Count: `$=dv.pages().length`
	-  Daily Notes: `$=dv.pages('"Diary"').length` \










#favorite #homepage