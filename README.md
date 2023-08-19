# Nycto

Nycto is a general purpose warframe bot centered around rivens and game knowledge. It includes everything from sorties to relics, and warframes to weapons, featuring a total of 33 main commands. Below are descriptions and usage instructions on each command in the bot. If you require assistance inside discord you can use **.help**! This command has all the same information listed here and will allow you to do everything within one application.

This bot has a built in currency, called **Nyctokens**, these can be earned by chatting in servers that the bot is in, and running commands seen below. Occasionally weapon challenges will pop up in the #general channel inside a server if one exists, winning one of those will also give you tokens.   
These tokens are used to unlock access to commands. Currently the requirements are as follows.

wtb - 1,000 Nyctokens    
wtblookup - 1,000 Nyctokens    
lookup - 3,000 Nyctokens   
lastweek - 5,000 Nyctokens    
compare - 7,000 Nyctokens   
inventory - 10,000 Nyctokens    

**You can invite the bot to your server using [This link](https://discord.com/api/oauth2/authorize?client_id=1015703025005895691&permissions=388160&scope=bot)**


General Commands

1. **relic** - This command returns information on the requested relics' items, drop locations and more.
   * Usage: .relic <relic_name> or .relic <item_name>
   * Displays:
     * All items contained in the specified Relic, listed from common to rare (top to bottom).
     * Current lowest online price of each item in the Relic.
     * Ducat Value of each item in the Relic.
     * Top 6 highest drop locations and their corresponding drop chances for each item in the Relic.
   * Extras:
     * You can also search for Relics that contain specific items using their names. For example, .relic titania prime would display all Relics containing the item "Titania Prime."

![image](https://github.com/Clasps/Nycto/assets/20675025/2462e6ad-c2c2-4806-af4d-f47b08eb5a30)
![image](https://github.com/Clasps/Nycto/assets/20675025/cfd6df1e-1aac-4184-8d9f-0edd25a7b7f0)



2. **weapon** - This command gives an abundance of weapon stats (I'm not kidding), this proves to be extremely useful when trying to figure out specifics.
   * Usage: .weapon <weapon_name>
     * Example: .weapon stahlta
   * Displays:
     * Weapon Type and Mastery Requirement.
     * If the weapon itself is tradable (e.g., vaykor hek, quanta vandal).
     * ALOT of weapon stats, including shooting modes and damage per mode, crit values, status chance, base polarities, disposition, and more.
    
![image](https://github.com/Clasps/Nycto/assets/20675025/80807ed5-3060-4adb-8b16-2c93c8e9c543)
![image](https://github.com/Clasps/Nycto/assets/20675025/e55b9bdc-7e89-40c3-96be-94b95eee3e8c)


       
3. **warframe** - This command will display stats about a requested warframe, including abilities.
   * Usage: .warframe <warframe_name>
   * Displays:
     * Aura and Base polarities of the Warframe.
     * Shields, Health, and Energy values at rank 0 and rank 30, along with the armor value.
     * Sprint Speed of the Warframe.
     * Update Name and Date of Introduction for the Warframe.
     * Passive and Ability descriptions of the Warframe.
   * Extras:
     * You can use .warframe without specifying a name to see the list of current prime warframes and their vaulted status.
    
![image](https://github.com/Clasps/Nycto/assets/20675025/5a3e605d-31c3-4f29-bca5-9377533c3136)
![image](https://github.com/Clasps/Nycto/assets/20675025/eaff7bcc-49c2-4efe-b90c-a72e6e0d19ad)


   
4. **fissures** - This command will show current PC fissures.
   * Usage: .fissures
   * Displays:
     * First Page: Lists Exterminate, Capture, and Rescue Fissures.
     * Second Page: Lists all current fissures, with specific icons to indicate mission difficulty (Fast, Medium/Endurance, Slow). Bolded mission types represent Steel Path missions.
    
![image](https://github.com/Clasps/Nycto/assets/20675025/7ddd3e17-21e4-4d2a-96a3-1cf7d28e417f)
![image](https://github.com/Clasps/Nycto/assets/20675025/79440627-f693-4df2-9531-733503c9d3c4)


   
5. **mod** - This command will show stats about a requested mod, and where you can obtain the mod.
   * Usage: .mod <mod_name>
   * Displays:
     * Compatibility, Tradability, and whether the mod is an Augment.
     * Stats for each level of the mod.
     * Update Name and Date of Introduction for the mod.
     * Top 10 most common drop locations/chances for the mod.
   * Extras:
     * You can use the -r flag to specify the rank of the mod. For example, .mod serration -r3 shows the Flawed version of the Serration mod at rank 3.

![image](https://github.com/Clasps/Nycto/assets/20675025/8245dc91-321c-42ca-ad08-f01e5762db7d)
![image](https://github.com/Clasps/Nycto/assets/20675025/ab9107f1-8ff1-4dd0-9c0c-378f21f49b2d)
![image](https://github.com/Clasps/Nycto/assets/20675025/d190cbbc-66fa-4676-a034-1627d1242e4d)



    
6. **compare** - This command compares weapons of the same type together, allowing you to determine which is best fit for your circumstances.
    * Usage: .compare <weapon_name_1>, <weapon_name_2>, <weapon_name_3> (You can compare up to three weapons at a time.)
    * Displays:
      * Comparison between the stats of the specified weapons.
    * Usage Instructions:
      * To use the command, simply separate the names of the weapons you want to compare with a comma (,).
    * Note: This command requires 7,000 Nyctokens to use.
   
![image](https://github.com/Clasps/Nycto/assets/20675025/4f288fd1-a934-441f-97b8-96bbe951b6ab)
![image](https://github.com/Clasps/Nycto/assets/20675025/8db5fc81-e93b-4644-a50a-a013b5ba2f7d)


    
7. **augments** - This command will show all augments for a requested item.
    * Usage: .augments <item_name> 
    * Displays:
      * Augments available for the requested item.
     
![image](https://github.com/Clasps/Nycto/assets/20675025/be2b71a0-7c32-4232-b050-e99cbd215f00)
![image](https://github.com/Clasps/Nycto/assets/20675025/02fab1f6-9a97-4c3c-b775-0a2436412e77)


    
8. **arcane** - This command will show information about a requested arcane.
    * Usage: .arcane <arcane_name>
    * Displays:
      * Level Stats of the Arcane.
      * Rarity of the Arcane.
      * Top 8 (if applicable) drop locations and their corresponding drop chances for the Arcane.
     
![image](https://github.com/Clasps/Nycto/assets/20675025/9dd318e4-8a0f-4229-bc94-7456fb9ca59a)
![image](https://github.com/Clasps/Nycto/assets/20675025/123823ce-22e7-44ec-99e8-4f59d507b794)


  
9. **cycles** - This command will display current worldstate time cycles.
    * Usage: .cycles
    * Displays:
      * Current time of day and time until switch.

![image](https://github.com/Clasps/Nycto/assets/20675025/dd2e4a8d-dbec-4bb6-87e6-5c3fd2191916)

      
10. **companion** - This command will show information about a requested companion.
    * Usage: .companion <companion_name> 
    * Displays:
      * Health and Shields values of the companion at rank 0 and rank 30.
      * Armor value of the companion.

![image](https://github.com/Clasps/Nycto/assets/20675025/003a7196-abd3-4313-be0e-3dcdac4237df)

  
11. **sortie** - This command will show information about the current sortie.
    * Usage: .sortie
    * Displays:
      * Each Sortie mission with its corresponding Modifier.
      * Tilesets, Boss, Faction, and Expiry Timer for each mission.
     
![image](https://github.com/Clasps/Nycto/assets/20675025/db32488a-1eba-45da-8870-e423e7744f1f)

    
12. **baro** - This command will show what baro is selling and where he is located.
    * Usage: .baro
    * Displays:
      * Baro's current inventory, showing the items he has available for trading.
      * The relay where Baro is currently located or will be next.
      * Arrival and Departure times for Baro in the relay.
      * Ducat and Credit amounts for each item available for trading.
     
![image](https://github.com/Clasps/Nycto/assets/20675025/d3270ea1-f8f9-4738-8c59-8c25f5b997c5)
![image](https://github.com/Clasps/Nycto/assets/20675025/7cf54f6b-74f5-4dd3-a5c9-aab363a5cc00)


    
13. **bugreport** - This command allows the user to submit a bug report to me the developer to allow for quicker resolvement of issues.
    * Usage: .bugreport <report_message> 
      * Example: .bugreport hi, I'm reporting a bug to you! This is the bug and how I made it happen, please fix!
    * Usage Instructions:
      * Type the command followed by your bug report message and send it to submit the bug report.
     
![image](https://github.com/Clasps/Nycto/assets/20675025/a98f59bb-2de8-4b76-8c7f-aac86ce0833f)
![image](https://github.com/Clasps/Nycto/assets/20675025/42e6be48-d2b1-4522-8cc7-620ab4257277)


Riven Commands

14. **grade** - This command grades rivens with a 1:1 accuracy with Samodeus, it even displays an image upon a successful grade.
    * Usage: .grade xY xY xY z <weapon_name> 
      * Example: .grade 99.6cd 127.7ms 88cc -97.1punc 8 exergis
    * Displays:
      * Grade of the Riven mod's stats.
      * Riven Name.
      * Riven.Market Import Code.
    * Syntax:
      * Take 2-4 stats of the Riven and represent them with x (value of stat), Y (stat abbreviation using .abbreviations), and z (mod rank).
      * You can also pass any of these if a new weapon is released and the bot is not updated yet. Options are: newshotgun, newrifle, newpistol, newmelee, newarchgun.
        * Example: .grade 58ms 43.2cc 42.7cd -15.4inf 8 newshotgun
    * Extras:
      * You can also grade directly from WF.M by pasting the auction link.
        * Example: .grade https://warframe.market/auction/634f7da471ad400c07ae696f
      * You can use -r and -v to signify the rank of the Riven or variant if the seller lists it incorrectly.
        * Example: .grade https://warframe.market/auction/634f7da471ad400c07ae696f -r0 -vPrime
       
![image](https://github.com/Clasps/Nycto/assets/20675025/b9b0046b-0cfa-49e3-a0f1-2a8ba6709eca)
![image](https://github.com/Clasps/Nycto/assets/20675025/7e007574-990a-46ce-9f4b-5fedb0e1600b)


    
15. **lookup** - This command looks up current listings of rivens on wf.m, saving numerous amounts of time.
    * Usage: .lookup cc cd ms -mag vectis 
    * Displays:
      * Six Rivens with the desired stats, sorted by lowest price.
      * Seller Name, Rerolls, Mastery Rank, and Polarity of the Riven.
      * Auction Link for each Riven.
    * Syntax:
      * Uses the same abbreviations as the grade command. You can use .abbreviations to get the list of stat abbreviations.
        * Example: .lookup cc cd ms -mag vectis
      * You can use -has when requesting a negative to show any negative stats.
        * Example: .lookup cc cd ms -has vectis
    * Extras:
      * You can grade the Riven using the grade command and pasting the link to the auction.
        * Example: .grade https://warframe.market/auction/634f7da471ad400c07ae696f
      * You can also use -r and -v to signify the rank of the Riven or variant if the seller lists it incorrectly.
        * Example: .grade https://warframe.market/auction/634f7da471ad400c07ae696f -r0 -vPrime
       
![image](https://github.com/Clasps/Nycto/assets/20675025/972deec7-8458-46a5-a701-d581cd544ac6)
![image](https://github.com/Clasps/Nycto/assets/20675025/ce27cf19-cd51-48f1-ae26-9ad6476b8763)


  
16. **bestroll** - This command returns the best riven roll for a requested weapon.
    * Usage: .bestroll <weapon_name> 
      * Example: .bestroll phantasma
    * Displays:
      * Best Riven stats per the requested weapon.
      * The information is sourced from the document created by 44bananas#0 and pinned in #riven-hub of the WFCD (Warframe Community Developers) Discord server. You can contact him if there are any issues with the data.
    * Extras:
      * You can also check the best Riven stats for stat sticks by requesting the frame.
        * Example: .bestroll khora
       
![image](https://github.com/Clasps/Nycto/assets/20675025/d3f98deb-11db-4ed2-a5f2-0dc6383b4446)
![image](https://github.com/Clasps/Nycto/assets/20675025/12b2075c-45f1-4602-a71c-76d213dd7c14)


  
17. **veileds** - This command displays the current lowest price of each type of veiled riven on wf.m.
    * Usage: .veileds
    * Displays:
      * Current lowest price of each weapon type's veiled Riven mods.
      * Seller name for each listing.
      * If you see a :red_circle:, that means there are currently no in-game listings on Warframe.Market (wf.m) for that particular veiled Riven mod. All other listings with prices are in-game listings.
     
![image](https://github.com/Clasps/Nycto/assets/20675025/8c6bc858-3877-43f9-9f38-495fe38fc76f)

    
18. **unroll** - This command finds the 4 lowest unroll rivens for a requested riven.
    * Usage: .unroll <weapon_name> 
      * Example: .unroll exergis
    * Displays:
      * The 4 lowest listings of unrolled Riven mods for the requested weapon, based on Warframe.Market (wf.m) data.
      * Polarity of the Riven mods.
      * Mastery Requirement of the Riven mods.
      * Seller status (green - ingame, orange - online, red - offline).
    * Extras:
      * You can also search for online-only listings by adding "online" in your request.
        * Example: .unroll karak online
       
![image](https://github.com/Clasps/Nycto/assets/20675025/e1c5f048-f774-4b04-bbf6-33de78a6f48d)
![image](https://github.com/Clasps/Nycto/assets/20675025/6af9159b-c707-4909-bdb6-a4ed06fe5bd9)


    
19. **range** - This command will display the stat range of each weapons possible riven stats.
    * Usage: .range <weapon_name> X Y 
      * Example: .range okina 3 1
    * Displays:
      * The lowest and highest possible values for a Riven mod of the requested weapon, along with the stat lineup.
    * Syntax:
      * X is the number of positive stats.
      * Y is the number of negative stats.
      * You can use -r to signify the mod rank (optional, defaults to 8).
        * Example: .range spectra vandal 3 1 -r3
       
![image](https://github.com/Clasps/Nycto/assets/20675025/4520f107-cef4-4524-9a7c-d4e44f90c942)
![image](https://github.com/Clasps/Nycto/assets/20675025/073d3f83-e059-40a9-99f1-785f8e7f41ed)


    
20. **variants** - This command will show all dispositions for a weapons family.
    * Usage: .variants <weapon_name>
      * Example: .variants braton
    * Displays:
      * All variants of the requested weapon, sorted by their corresponding dispositions from highest to lowest.

![image](https://github.com/Clasps/Nycto/assets/20675025/8c452e9d-e5d2-40c3-987b-5f2192051bd8)

    
21. **dispo** - This command will show the disposition of a requested weapon, or all weapons with the requested disposition.
    * Usage: .dispo <weapon_name> 
      * Example: .dispo sporothrix
    * Displays:
      * Weapon Disposition for the requested weapon.
    * Extras:
      * You can also use .dispo <disposition_value> to show all weapons with a specific disposition value.
        * Example: .dispo 1.35
       
![image](https://github.com/Clasps/Nycto/assets/20675025/a92c5b4f-a709-4548-96f7-5a6df7322486)
![image](https://github.com/Clasps/Nycto/assets/20675025/015d4773-ebe1-4217-8482-0886cf0808c5)


    
22. **dispohistory** - This command will show the history of a weapons disposition.
    * Usage: .dispohistory <weapon_name> 
      * Example: .dispohistory tenet tetra
    * Displays:  
      * FIRST PAGE: Any update where the weapon's disposition changed, along with the update name and date.
      * SECOND PAGE: Disposition for the weapon in every update.
    * Kitguns:
      * If you wish to view Kitgun dispositions, you can use the following commands:
      * .dispohistory vermisplicer primary
      * .dispohistory vermisplicer secondary
    * The data provided is only from Update 28.2 (July 14th, 2020) and later.
   
![image](https://github.com/Clasps/Nycto/assets/20675025/fadbee73-e50b-44d8-bd58-717b153ede7c)
![image](https://github.com/Clasps/Nycto/assets/20675025/d26da8d3-e4df-4020-b648-228dc303c079)

![image](https://github.com/Clasps/Nycto/assets/20675025/9e8dd7f5-b4cc-40bc-874a-2587fa117d8c)

    
23. **switch** - This command will show the riven stats of your riven on each weapon in a family.
    * Usage: .switch <stats> <weapon_name> 
      * Example: .switch 153.8dmg 89.3ms 119.6sl -90.9imp kuva karak
    * Displays:
      * Swapped Riven stats per variant for the requested weapon.
    * Syntax:
      * Use the name of the weapon of which stats you are currently inputting.
    * Extras:
      * You can also use a riven.market import code.
        * Example: .switch RMIMPORTCODE
       
![image](https://github.com/Clasps/Nycto/assets/20675025/e4bcc8fe-1ae8-436c-9dcb-4ecdc7077cb1)
![image](https://github.com/Clasps/Nycto/assets/20675025/bd1cdffb-08bf-46a1-8b81-08d95d76ae61)

  
24. **unveil** - This command will simulate unveiling a riven for the user.
    * Usage: .unveil
    * Displays:
      * Randomly generated Riven mod with grades.
    * Extras:
      * You can unveil based on the Riven type.
      * Accepted types are (Melee, Rifle, Shotgun, Pistol, Archgun).
        * Example: .unveil rifle
    * Please note that any weapon can roll any IPS (Impact, Puncture, Slash) since there are no IPS matching restrictions.

![image](https://github.com/Clasps/Nycto/assets/20675025/96b665f9-923b-441a-82c0-083421d0c80c)

    
25. **lastweek** - This command will allow the user to look up information on riven trades that occured the week prior.
    * Usage: .lastweek
    * Displays:
      * The top 10 highest value Riven trades of the last week.
      * Weapon popularity ranked from 1 to 100, with higher numbers indicating higher popularity. Popularity is the effective comparison between the weapon and the most popular weapon in its category.
    * Extras:
      * You can use specific keywords to filter the data:
        * .lastweek shotgun: View last week's highest shotgun trades.
        * .lastweek rifle: View last week's highest rifle trades.
        * .lastweek melee: View last week's highest melee trades.
        * .lastweek kitgun: View last week's highest kitgun trades.
        * .lastweek pistol: View last week's highest pistol trades.
        * .lastweek zaw: View last week's highest zaw trades.
        * .lastweek archgun: View last week's highest archgun trades.
      * You can use .lastweek weapon to view the rolled and unrolled trade data of that specific weapon.
        * Example: .lastweek glaive
      * You can also include platform abbreviations to see data specific to that platform:
        * "pc": PC platform.
        * "ps": PlayStation platform.
        * "xbox": Xbox platform.
        * "switch": Nintendo Switch platform.
          * Example: .lastweek shotgun xbox, .lastweek glaive switch

![image](https://github.com/Clasps/Nycto/assets/20675025/13479ce6-eb2b-4504-aeeb-522db3e9eaa3)
![image](https://github.com/Clasps/Nycto/assets/20675025/adaaca8d-7755-4d54-83e4-d0e0cacffac6)
![image](https://github.com/Clasps/Nycto/assets/20675025/e7170606-7139-4270-813e-c91985ee8361)

    

Market Commands

26. **wfm** - This command will allow the user to look up items on Warframe.Market, and return the 4 lowest priced options.
    * Usage: .wfm <item_name> 
      * Example: .wfm saryn prime chassis
    * Displays:
      * The 4 lowest currently online listings of the submitted item.
      * Average prices and volume over the last 48 Hours/90 Days.
      * Ducat value for the item (if applicable).
      * Quantity per user.
    * Extras:
      * You can use -r to signify the rank of the item (optional).
        * Example: .wfm exodia contagion -r3
       
![image](https://github.com/Clasps/Nycto/assets/20675025/621a024b-7dba-4156-a97c-565618669c5b)
![image](https://github.com/Clasps/Nycto/assets/20675025/e40d1ae3-7600-490b-b012-f7655f52e828)

    
27. **lich** - This command will find the 6 cheapest liches with the requested information.
    * Usage: .lich <weapon_name>, <element_name>, <minimum_percentage>
      * Example: .lich hek tox 55
    * Displays:
      * 6 Kuva Liches with the desired weapon and element, sorted by the lowest price.
      * Seller Name, Percentage, Price, Ephemera, and Quirk of the Lich for each listing.
      * Auction Link for each Lich.
    * Syntax:
      * You can use "Kuva hek" or "Hek" interchangeably as the Weapon Name.
        * Example: .lich kuva hek tox 55, .lich ferrox tox 34
    * Extras:
      * You can search for Liches with ephemeras by adding "eph" to your request.
        * Example: .lich chakkhurr elec 30 eph

![image](https://github.com/Clasps/Nycto/assets/20675025/264d8784-ecf2-4654-998f-c7c2c1935d53)
![image](https://github.com/Clasps/Nycto/assets/20675025/74bc639c-93df-4858-92c1-72c12b9e0d10)



Personal Commands

28. **inventory** - This command stores user rivens allowing the user to display their collections, it can even be used as a WTS board to sell some of your rivens.
    * Usage: .inventory
    * Displays:
      * User-submitted Riven inventories.
    * Usage Instructions:
      * Use .inventory X to show the grades of a specific Riven (X = Inventory Number).
        * Example: .inventory 4
      * HOW TO ADD TO INVENTORY:
        * Use .addinv <RivenMarketImportCode> <polarity> -rr<rerolls> -mr<masteryrank>
        * Accepted polarities are: (vazarin, naramon, madurai, d, -, v)
        * If you need your Riven Market import code, you can use the .grade command.
      * HOW TO DELETE FROM INVENTORY:
        * Use .delinv <INVENTORYNUMBER>
          * Example: .delinv3, .delinv 17
      * HOW TO SWAP RIVEN PLACES:
        * Use .swapinv <X> <Y> (X and Y being the inventory numbers you want to swap).
          * Example: .swapinv 5 2
      * HOW TO MOVE RIVEN PLACES:
        * This will move a Riven up, and everything after it down.
        * Use .moveinv <X> <Y> (The above command will take the X-th Riven and move it to spot Y).
          * Example: .moveinv 14 3
      * HOW TO EDIT INVENTORY:
        * Use .editinv <X>
        * This allows you to change the stats if a weapon's disposition changes.
      * You can also use .compinv to create a collage of all the Rivens in your inventory, or .compinv X to make one for any Riven in your inventory.
        * You can include "-a" in your request to sort your collage alphabetically.
          * Example: .compinv -a
     
![image](https://github.com/Clasps/Nycto/assets/20675025/808c0964-1836-4a22-a3e8-a38abfb1aecf)
![image](https://github.com/Clasps/Nycto/assets/20675025/5419c75d-335c-4990-a6ef-723ecf857f6e)
![image](https://github.com/Clasps/Nycto/assets/20675025/77be51f1-a83a-4bde-b2bb-06ac736bb99b)



    
29. **stats** - This command will show the users statistics with the bot.
    * Usage: .stats
    * Displays:
      * User Stats, including Total Commands Used and Favorite Command.
      * Total Nyctokens and coinflip record.
    * Extras:
      * You can check other users' stats by mentioning them in the message.
        * Example: .stats @Nycto#7928
       
![image](https://github.com/Clasps/Nycto/assets/20675025/b3645e50-76e6-4f2c-b578-b4f4d4c790b7)

    
30. **wtb** - This command recreates the ingame trading scene by enabling users to save their WTB riven list, and allowing others to search against it to find users looking to buy their riven.
    * Usage: .wtb
    * Displays:
      * User's WTB Riven list.
    * Syntax:
      * HOW TO ADD WTB:
        * Example: .addwtb cc cd ms -mag vectis
        * NOTE: This only works with one Riven at a time, you cannot add more than one negative.
      * HOW TO DELETE WTB:
        * Example: .delwtb 6
      * Extras:
        * You can check other users' WTB lists by mentioning them in the message.
          * Example: .wtb @Nycto#7928
         
![image](https://github.com/Clasps/Nycto/assets/20675025/9b6bdeee-e0e7-4eb5-a924-913ea3f21705)

  
31. **wtblookup** - This command allows users to search against the wtb database, to find users looking to buy a specific roll. This will mainly be user for selling your own rivens.
    * Usage: .wtblookup <riven_stats>
      * Example: .wtblookup cc cd ms -mag vectis
    * Displays: 
      * Users (same platform) who have the requested Riven in their .wtb list.

![image](https://github.com/Clasps/Nycto/assets/20675025/cfa982e0-da23-4604-84aa-5537d7c4ec91)

    
32. **coinflip** - This command lets users bet their tokens against each other.
    * Usage: .coinflip <user_mention> <amount>
      * Example: .coinflip @Nycto#7928 5000
     
![image](https://github.com/Clasps/Nycto/assets/20675025/4ca908c9-4537-4312-8e26-f1e579a64b1e)

    
33. **leaderboard** - This command will show the top users in different areas of the bot.
    * Usage: .leaderboard
    * Displays:
      * Users with the top 10 total commands run and total Nyctokens.
    * Extras:
      * You can check leaderboards per command!
        * Example: .leaderboard grade

![image](https://github.com/Clasps/Nycto/assets/20675025/cb9baf90-5eb9-46d2-98c7-ae91e6f80d51)


I built this bot with fun in mind, while also keeping it sleek and professional. I always loved when developers put easter eggs in their projects, because it shows that the developers just wanted to have fun making something. Leaving users with a "trophy" rewarding their knowledge of the reference, or their ability to find the hidden egg lets people form a bond with the project, and thats what I want with mine. There are plenty of easter eggs and hidden commands, if you say the right things or do the right things, you might find some.
