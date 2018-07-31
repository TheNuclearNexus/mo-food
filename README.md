# Mo' Food API
add these tags to your food item:

{mf_food:1b} - tells Mo' Food that this is in fact food 
{mf_eat_time: } - tells Mo' Food how many ticks it should take to eat this
{mf_id: } - allows you to clear the proper food and add any other special effects upon consumption (mf_id:1 is in use)
{mf_parColor: } - color of eating particles (1 - 48)
{mf_satLvl: } - tells Mo' Food how many hunger points to replenish
{mf_not_placeable:1b} - doesn't let the player place the item

function tags:
mf_api/tags/functions/consume.json - runs all functions that clear food from the player upon consumption 
