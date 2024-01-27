USE THIS IF YOUR UNSURE ON HOW TO CONFIGURE THE SCRIPT

if grouprank >= 25 
TeamName = "Corporate Team"

So what the >= stands for is the min rank to be on that team, getting the group rank ID is pretty simple.

1. Configure Group Page
2. Click on the role/rank you want to be the min
3. Search for the RANKID tab.

elseif grouprank >= 14 then
		TeamName = "Executive Team"

Same thing, but this time it's elseif not if what this basically means that it stands for ALSO in lua code terms.

If you want to have more teams then provided in the SCRIPT follow these steps.

1. Create a TEAM in the provided Team's Folder
2. Name the team to whatever and choose a different colour from any of the other teams (if two or more teams have the same colour, only one team will load in)
3. Copy  elseif grouprank >= 14       then under another elseif chunk
         TeamName = "Executive Team"
4. Config it to your liking
