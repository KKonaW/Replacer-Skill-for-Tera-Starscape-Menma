Compatible with Skill-Prediction, Ping Remover and NGSP

------
/8 channel or ! Command | effect description
--- | ---
rs | Turn module on/off
reload | reload the modified skills.js file content

-To add more skills go to folder class to find skill IDs or here 

https://raw.githubusercontent.com/neowutran/TeraDpsMeterData/master/skills/skills-EU-EN.tsv

Job = Class ID 
Warrior  0 / Lancer 1 / Slayer 2 / Berserker 3 / Sorcerer 4 / Archer 5 / Priest 6 / Mystic 7 / Reaper 8 / Gunner 9 / Brawler 10 / Ninja 11 / Valkyrie 12
Group = First digits of the skill ID for exaplample / group 1 = 10000 and group 40 = 400000
// 00 normal skill / 10 target skill / 30 buffed skill
{ job: 2, group: 1, enabled: true, to: 11200, instance: true, replace: true},

-To Enable or Disble skills go to "skill.js" and add or remove /* at the start of the skill and close it with */ 



for example


![1](https://user-images.githubusercontent.com/35492207/115976332-cc98c580-a521-11eb-8638-46619ae621b1.png)
