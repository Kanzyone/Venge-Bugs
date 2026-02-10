# Bug Checklist

This section contains a structured checklist of known and reported issues observed across different areas of Venge.io. The purpose of this list is to provide a clear and organized overview of recurring technical problems, grouped by system and gameplay components.

Each entry represents a documented issue identified through in-game observation and community reporting. Bugs are categorized by area (such as <b>Main UI</b>, <b>In-Game systems</b>, <b>Heroes</b>, <b>Weapons</b>, <b>Maps</b>, <b>Social Hub</b>, and <b>Map Editor</b>) and marked with indicators that reflect their current status and relative priority.

This checklist is intended to function as a continuously evolving reference. It allows readers to quickly understand which issues are currently active, which have been resolved, and which may require further verification. By presenting this information in a consistent format, the list supports easier tracking, comparison and long term documentation of technical problems across updates.

The goal is not only to record individual bugs, but to maintain a structured archive that reflects the overall technical state of the game environment over time.

<br>

<h2>Bug Status Overview</h2>

The table below provides a summarized overview of the current state of the documented bug dataset. It presents the overall distribution of issues by priority and status, allowing to quickly understand the scale, severity, and general condition of reported problems across the game.

<br>

<table>
  <tr>
    <th>Metric</th>
    <th>Value</th>
  </tr>

  <tr>
    <td>Total Documented Bugs</td>
    <td>228+</td>
  </tr>

  <tr>
    <td>High Priority</td>
    <td>71</td>
  </tr>

  <tr>
    <td>Medium Priority</td>
    <td>106</td>
  </tr>

  <tr>
    <td>Low Priority</td>
    <td>51</td>
  </tr>

  <tr>
    <td>Confirmed Fixed</td>
    <td>40</td>
  </tr>
 
  <tr>
    <td>Active / Pending</td>
    <td>188</td>
  </tr>
  
  <tr>
    <td>Last Update</td>
    <td>8 March 2024</td>
  </tr>
</table>

<br>

<h2>Bug Listings by Category</h2>

The following sections present the documented issues organized by system category. Each table contains individual bug entries with their identification number, current status, priority level and a short description.

These categorized lists are intended to provide a more detailed and structured view of the issues summarized in the overview above, allowing for easier navigation and tracking across different parts of the game.


<br>

<strong id="mainui">Main UI</strong>

Covers issues related to the main interface outside of gameplay, including menus, shop, inventory, login systems, quests, notifications and general user interaction elements.

<table>
  <tr> 
    <th>ID</th> 
    <th>Status</th> 
    <th>Priority</th> 
    <th>Description</th> 
  </tr>

  <!-- 🔴 HIGH PRIORITY -->
  <tr><td>MUI#H001</td><td align="center">🔳</td><td align="center">🔴</td><td>After each match, an advertisement attempts to play but fails to load. This also causes the mouse cursor to lock and disappear on the main UI.</td></tr>
  <tr><td>MUI#H002</td><td align="center">🔳</td><td align="center">🔴</td><td>Clan chat displays sender names as "Guest" instead of actual usernames.</td></tr>
  <tr><td>MUI#H003</td><td align="center">🔳</td><td align="center">🔴</td><td>Language setting changes have no effect even after refresh.</td></tr>
  <tr><td>MUI#H004</td><td align="center">🔳</td><td align="center">🔴</td><td>Newly created clans cannot be deleted because there is no delete button for owners.</td></tr>
  <tr><td>MUI#H005</td><td align="center">🔳</td><td align="center">🔴</td><td>Watching ads for VGs when opening crates does not add any VGs to the account.</td></tr>
  <tr><td>MUI#H006</td><td align="center">🔳</td><td align="center">🔴</td><td>New accounts get logged out randomly, especially after closing and reopening the browser.</td></tr>
  <tr><td>MUI#H007</td><td align="center">🔳</td><td align="center">🔴</td><td>Custom matches expire if the creator does not join within ~10 seconds.</td></tr>
  <tr><td>MUI#H008</td><td align="center">🔳</td><td align="center">🔴</td><td>Play button sometimes gets stuck with an infinite loading spinner.</td></tr>
  <tr><td>MUI#H009</td><td align="center">🔳</td><td align="center">🔴</td><td>"An error occurred" alert appears after successfully completing quests.</td></tr>

  <!-- 🟡 MEDIUM PRIORITY -->
  <tr><td>MUI#M001</td><td align="center">🔳</td><td align="center">🟡</td><td>Multiple dances can be selected at the same time in Shop inventory.</td></tr>
  <tr><td>MUI#M002</td><td align="center">🔳</td><td align="center">🟡</td><td>No online/offline indicator in the new Friends and Messages system.</td></tr>
  <tr><td>MUI#M003</td><td align="center">🔳</td><td align="center">🟡</td><td>Emojis shown before usernames remain even after the emoji is sold.</td></tr>
  <tr><td>MUI#M004</td><td align="center">🔳</td><td align="center">🟡</td><td>Inbox does not update in real time: must reopen to see new messages.</td></tr>
  <tr><td>MUI#M005</td><td align="center">🔳</td><td align="center">🟡</td><td>Unfavoriting an item triggers a blank alert popup.</td></tr>
  <tr><td>MUI#M006</td><td align="center">🔳</td><td align="center">🟡</td><td>Quests may give inconsistent rewards and Kulu’s quest can appear multiple times.</td></tr>
  <tr><td>MUI#M007</td><td align="center">🔳</td><td align="center">🟡</td><td>Free skin notification causes visible performance lag while active.</td></tr>
  <tr><td>MUI#M008</td><td align="center">🔳</td><td align="center">🟡</td><td>Quest claim button in Profile: Quests does not respond.</td></tr>
  <tr><td>MUI#M009</td><td align="center">🔳</td><td align="center">🟡</td><td>Ad reward notifications appear too frequently instead of after cooldown.</td></tr>
  <tr><td>MUI#M010</td><td align="center">🔳</td><td align="center">🟡</td><td>Free skin popup stays visible throughout matches and does not disappear.</td></tr>
  <tr><td>MUI#M011</td><td align="center">🔳</td><td align="center">🟡</td><td>"Already claimed reward" alert repeatedly appears after refresh.</td></tr>
  <tr><td>MUI#M012</td><td align="center">🔳</td><td align="center">🟡</td><td>Irrelevant system alerts appear after page refresh.</td></tr>
  <tr><td>MUI#M013</td><td align="center">🔳</td><td align="center">🟡</td><td>LMG cannot be unlocked from loadout even when requirements are met.</td></tr>

  <!-- 🟢 LOW PRIORITY -->
  <tr><td>MUI#L001</td><td align="center">🔳</td><td align="center">🟢</td><td>Main UI character model no longer plays idle animations.</td></tr>
  <tr><td>MUI#L002</td><td align="center">🔳</td><td align="center">🟢</td><td>Equipped skins sometimes do not visually apply after navigating menus.</td></tr>
  <tr><td>MUI#L003</td><td align="center">🔳</td><td align="center">🟢</td><td>No lock icons displayed for locked M4 and AK47 weapons.</td></tr>
  <tr><td>MUI#L004</td><td align="center">🔳</td><td align="center">🟢</td><td>Register button logs in users instead of creating a new account.</td></tr>
  <tr><td>MUI#L005</td><td align="center">🔳</td><td align="center">🟢</td><td>Friends list shows account age instead of last online time.</td></tr>
  <tr><td>MUI#L006</td><td align="center">🔳</td><td align="center">🟢</td><td>Logging into one sub domain does not log the user into others.</td></tr>
  <tr><td>MUI#L007</td><td align="center">🔳</td><td align="center">🟢</td><td>Kulu’s quest appears as a normal quest even after being unlocked.</td></tr>
  <tr><td>MUI#L008</td><td align="center">🔳</td><td align="center">🟢</td><td>Multi quick sell does not sell multiple copies even when quantity is entered.</td></tr>

  <!-- FIXED -->
  <tr><td>MUI#F001</td><td align="center">Fixed</td><td align="center">✅</td><td>-Ad reward popup exceeding daily limit.</td></tr>
  <tr><td>MUI#F002</td><td align="center">Fixed</td><td align="center">✅</td><td>-Skin equip delay in inventory.</td></tr>
  <tr><td>MUI#F003</td><td align="center">Fixed</td><td align="center">✅</td><td>-Resolution range mismatch between menus.</td></tr>
  <tr><td>MUI#F004</td><td align="center">Fixed</td><td align="center">✅</td><td>-Crate unlock sound playing without enough VGs.</td></tr>
  <tr><td>MUI#F005</td><td align="center">Fixed</td><td align="center">✅</td><td>-Favorites updating slowly.</td></tr>
  <tr><td>MUI#F006</td><td align="center">Fixed</td><td align="center">✅</td><td>-In-game inventory not scrollable.</td></tr>
  <tr><td>MUI#F007</td><td align="center">Fixed</td><td align="center">✅</td><td>-Blocking users in inbox not working.</td></tr>
  <tr><td>MUI#F008</td><td align="center">Fixed</td><td align="center">✅</td><td>-Daily rewards not giving skins.</td></tr>
  <tr><td>MUI#F009</td><td align="center">Fixed</td><td align="center">✅</td><td>-Daily rewards claimable without watching ads.</td></tr>
  <tr><td>MUI#F010</td><td align="center">Fixed</td><td align="center">✅</td><td>-Lighting from previous match affecting main UI.</td></tr>
  <tr><td>MUI#F011</td><td align="center">Fixed</td><td align="center">✅</td><td>-Password change requiring email change.</td></tr>
  <tr><td>MUI#F012</td><td align="center">Fixed</td><td align="center">✅</td><td>-Clan info update not saving.</td></tr>

</table>





<br>

<strong>In-game</strong>

Includes bugs that occur during active gameplay such as HUD problems, animations, audio, performance issues, mechanics and player interactions.

<table>
  <tr> 
    <th>ID</th> 
    <th>Status</th> 
    <th>Priority</th> 
    <th>Description</th> 
  </tr>

<!-- 🔴 HIGH PRIORITY -->
<tr><td>ING#H001</td><td align="center">🔳</td><td align="center">🔴</td><td>Reducing in-game resolution also lowers HUD and crosshair resolution, making UI text blurry and crosshair unclear.</td></tr>
<tr><td>ING#H002</td><td align="center">🔳</td><td align="center">🔴</td><td>Players sometimes get stuck at the instancing spawn point below the map and never appear on the actual terrain.</td></tr>
<tr><td>ING#H003</td><td align="center">🔳</td><td align="center">🔴</td><td>In-game leaderboard/scoreboard does not update in real time; players who leave remain listed until refresh.</td></tr>
<tr><td>ING#H004</td><td align="center">🔳</td><td align="center">🔴</td><td>Only one hacker can be vote-kicked per match even if multiple hackers are present.</td></tr>
<tr><td>ING#H005</td><td align="center">🔳</td><td align="center">🔴</td><td>Switching weapons in-game sometimes triggers an advertisement to play unexpectedly.</td></tr>
<tr><td>ING#H006</td><td align="center">🔳</td><td align="center">🔴</td><td>Players joining matches (especially guest lobbies) often spawn into games with only ~20–30 seconds remaining instead of a reasonable minimum time.</td></tr>

<!-- 🟡 MEDIUM PRIORITY -->
<tr><td>ING#M007</td><td align="center">🔳</td><td align="center">🟡</td><td>Direct URLs such as "/?map=MapName" and "/Spectate:CODE" no longer function.</td></tr>
<tr><td>ING#M008</td><td align="center">🔳</td><td align="center">🟡</td><td>"Hide Announcements" setting does not hide the in-game free skin notification popup.</td></tr>
<tr><td>ING#M009</td><td align="center">🔳</td><td align="center">🟡</td><td>Potions are not visible in matches until the player uses them once.</td></tr>
<tr><td>ING#M010</td><td align="center">🔳</td><td align="center">🟡</td><td>Animated texture skins (e.g., Blaze Scar, OLED Tec-9) sometimes play choppy or laggy animations.</td></tr>
<tr><td>ING#M011</td><td align="center">🔳</td><td align="center">🟡</td><td>Lighting does not properly affect weapons and hands in official maps; models appear flat regardless of player rotation.</td></tr>
<tr><td>ING#M012</td><td align="center">🔳</td><td align="center">🟡</td><td>Terrain lighting looks incorrect on bright skybox maps; shadows appear missing or too weak.</td></tr>
<tr><td>ING#M013</td><td align="center">🔳</td><td align="center">🟡</td><td>When a new enemy spawns and you aim at them immediately, they sometimes disappear and relocate to another spawn point.</td></tr>

<!-- 🟢 LOW PRIORITY -->
<tr><td>ING#L014</td><td align="center">🔳</td><td align="center">🟢</td><td>Charms can clip into weapon models when moving, jumping, or turning at certain angles.</td></tr>

<!-- FIXED -->
<tr><td></td></tr>
<tr><td>Fixed List</td></tr> 
<tr><td></td></tr>
<tr><td>ING#F015</td><td align="center">Fixed</td><td align="center">✅</td><td>-Enemy HP bars sometimes disappeared in the next match after voting for a new map.</td></tr>
<tr><td>ING#F016</td><td align="center">Fixed</td><td align="center">✅</td><td>-Reflectivity issues where ground, rocks, and characters appeared overly reflective.</td></tr>


</table>

<br>

<strong>Heroes</strong>

Focuses on character specific issues, including abilities, animations, cooldowns, visual effects and hero related mechanics.

<table border="1">
    <tr>
        <th>ID</th>
        <th>Status</th>
        <th>Priority</th>
        <th>Hero</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Veri 1</td>
        <td>Veri 2</td>
        <td>Veri 3</td>
        <td>Veri 4</td>
        <td>Veri 5</td>
    </tr>
    <tr>
        <td>Veri 5</td>
        <td>Veri 6</td>
        <td>Veri 7</td>
        <td>Veri 8</td>
       <td>Veri 9</td>
    </tr>
</table>

<br>

<strong>Weapons</strong>

Contains problems related to weapon behavior such as firing mechanics, reload timing, positioning, textures and damage registration.

<table border="1">
    <tr>
        <th>ID</th>
        <th>Status</th>
        <th>Priority</th>
        <th>Weapon</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Veri 1</td>
        <td>Veri 2</td>
        <td>Veri 3</td>
        <td>Veri 4</td>
        <td>Veri 5</td>
    </tr>
    <tr>
        <td>Veri 5</td>
        <td>Veri 6</td>
        <td>Veri 7</td>
        <td>Veri 8</td>
       <td>Veri 9</td>
    </tr>
</table>

<br>

<strong>Maps</strong>

Covers environment related issues including terrain bugs, collision problems, lighting inconsistencies, exploit spots and map specific gameplay errors.

<table border="1">
    <tr>
        <th>ID</th>
        <th>Status</th>
        <th>Priority</th>
        <th>Map</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Veri 1</td>
        <td>Veri 2</td>
        <td>Veri 3</td>
        <td>Veri 4</td>
        <td>Veri 5</td>
    </tr>
    <tr>
        <td>Veri 5</td>
        <td>Veri 6</td>
        <td>Veri 7</td>
        <td>Veri 8</td>
       <td>Veri 9</td>
    </tr>
</table>

<br>

<strong>Social Hub</strong>

Includes bugs related to player profiles, inventory, marketplace, clans, leaderboards and social interaction systems.

<table border="1">
    <tr>
        <th>ID</th>
        <th>Status</th>
        <th>Priority</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Veri 1</td>
        <td>Veri 2</td>
        <td>Veri 3</td>
        <td>Veri 4</td>
    </tr>
    <tr>
        <td>Veri 5</td>
        <td>Veri 6</td>
        <td>Veri 7</td>
        <td>Veri 8</td>
    </tr>
</table>

<br>

<strong>Map Editor</strong>

Focuses on issues within the map creation tool such as object placement, collision handling, saving/loading errors and editor mechanics.
<table border="1">
    <tr>
        <th>ID</th>
        <th>Status</th>
        <th>Priority</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Veri 1</td>
        <td>Veri 2</td>
        <td>Veri 3</td>
        <td>Veri 4</td>
    </tr>
    <tr>
        <td>Veri 5</td>
        <td>Veri 6</td>
        <td>Veri 7</td>
        <td>Veri 8</td>
    </tr>
</table>

<br>

<strong>Client</strong>

Reserved for technical issues related to the game client itself, such as system-level behavior, performance or platform specific problems.
<table border="1">
    <tr>
        <th>ID</th>
        <th>Status</th>
        <th>Priority</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>Veri 1</td>
        <td>Veri 2</td>
        <td>Veri 3</td>
        <td>Veri 4</td>
    </tr>
    <tr>
        <td>Veri 5</td>
        <td>Veri 6</td>
        <td>Veri 7</td>
        <td>Veri 8</td>
    </tr>
</table>

<br>

