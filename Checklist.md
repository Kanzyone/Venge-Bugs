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
  <tr><td>MUI#H001</td><td align="center">-</td><td align="center">🔴</td><td>After each match, an advertisement attempts to play but fails to load. This also causes the mouse cursor to lock and disappear on the main UI.</td></tr>
  <tr><td>MUI#H002</td><td align="center">-</td><td align="center">🔴</td><td>Clan chat displays sender names as "Guest" instead of actual usernames.</td></tr>
  <tr><td>MUI#H003</td><td align="center">-</td><td align="center">🔴</td><td>Language setting changes have no effect even after refresh.</td></tr>
  <tr><td>MUI#H004</td><td align="center">-</td><td align="center">🔴</td><td>Newly created clans cannot be deleted because there is no delete button for owners.</td></tr>
  <tr><td>MUI#H005</td><td align="center">-</td><td align="center">🔴</td><td>Watching ads for VGs when opening crates does not add any VGs to the account.</td></tr>
  <tr><td>MUI#H006</td><td align="center">-</td><td align="center">🔴</td><td>New accounts get logged out randomly, especially after closing and reopening the browser.</td></tr>
  <tr><td>MUI#H007</td><td align="center">-</td><td align="center">🔴</td><td>Custom matches expire if the creator does not join within ~10 seconds.</td></tr>
  <tr><td>MUI#H008</td><td align="center">-</td><td align="center">🔴</td><td>Play button sometimes gets stuck with an infinite loading spinner.</td></tr>
  <tr><td>MUI#H009</td><td align="center">-</td><td align="center">🔴</td><td>"An error occurred" alert appears after successfully completing quests.</td></tr>

  <!-- 🟡 MEDIUM PRIORITY -->
  <tr><td>MUI#M001</td><td align="center">-</td><td align="center">🟡</td><td>Multiple dances can be selected at the same time in Shop inventory.</td></tr>
  <tr><td>MUI#M002</td><td align="center">-</td><td align="center">🟡</td><td>No online/offline indicator in the new Friends and Messages system.</td></tr>
  <tr><td>MUI#M003</td><td align="center">-</td><td align="center">🟡</td><td>Emojis shown before usernames remain even after the emoji is sold.</td></tr>
  <tr><td>MUI#M004</td><td align="center">-</td><td align="center">🟡</td><td>Inbox does not update in real time: must reopen to see new messages.</td></tr>
  <tr><td>MUI#M005</td><td align="center">-</td><td align="center">🟡</td><td>Unfavoriting an item triggers a blank alert popup.</td></tr>
  <tr><td>MUI#M006</td><td align="center">-</td><td align="center">🟡</td><td>Quests may give inconsistent rewards and Kulu’s quest can appear multiple times.</td></tr>
  <tr><td>MUI#M007</td><td align="center">-</td><td align="center">🟡</td><td>Free skin notification causes visible performance lag while active.</td></tr>
  <tr><td>MUI#M008</td><td align="center">-</td><td align="center">🟡</td><td>Quest claim button in Profile: Quests does not respond.</td></tr>
  <tr><td>MUI#M009</td><td align="center">-</td><td align="center">🟡</td><td>Ad reward notifications appear too frequently instead of after cooldown.</td></tr>
  <tr><td>MUI#M010</td><td align="center">-</td><td align="center">🟡</td><td>Free skin popup stays visible throughout matches and does not disappear.</td></tr>
  <tr><td>MUI#M011</td><td align="center">-</td><td align="center">🟡</td><td>"Already claimed reward" alert repeatedly appears after refresh.</td></tr>
  <tr><td>MUI#M012</td><td align="center">-</td><td align="center">🟡</td><td>Irrelevant system alerts appear after page refresh.</td></tr>
  <tr><td>MUI#M013</td><td align="center">-</td><td align="center">🟡</td><td>LMG cannot be unlocked from loadout even when requirements are met.</td></tr>

  <!-- 🟢 LOW PRIORITY -->
  <tr><td>MUI#L001</td><td align="center">-</td><td align="center">🟢</td><td>Main UI character model no longer plays idle animations.</td></tr>
  <tr><td>MUI#L002</td><td align="center">-</td><td align="center">🟢</td><td>Equipped skins sometimes do not visually apply after navigating menus.</td></tr>
  <tr><td>MUI#L003</td><td align="center">-</td><td align="center">🟢</td><td>No lock icons displayed for locked M4 and AK47 weapons.</td></tr>
  <tr><td>MUI#L004</td><td align="center">-</td><td align="center">🟢</td><td>Register button logs in users instead of creating a new account.</td></tr>
  <tr><td>MUI#L005</td><td align="center">-</td><td align="center">🟢</td><td>Friends list shows account age instead of last online time.</td></tr>
  <tr><td>MUI#L006</td><td align="center">-</td><td align="center">🟢</td><td>Logging into one sub domain does not log the user into others.</td></tr>
  <tr><td>MUI#L007</td><td align="center">-</td><td align="center">🟢</td><td>Kulu’s quest appears as a normal quest even after being unlocked.</td></tr>
  <tr><td>MUI#L008</td><td align="center">-</td><td align="center">🟢</td><td>Multi quick sell does not sell multiple copies even when quantity is entered.</td></tr>

  <!-- FIXED -->
<tr><td></td></tr>
<tr><td>Fixed List</td></tr> 
<tr><td></td></tr>
  <tr><td>MUI#H001</td><td align="center">Fixed</td><td align="center">✅</td><td>-Ad reward popup exceeding daily limit.</td></tr>
  <tr><td>MUI#L002</td><td align="center">Fixed</td><td align="center">✅</td><td>-Skin equip delay in inventory.</td></tr>
  <tr><td>MUI#M003</td><td align="center">Fixed</td><td align="center">✅</td><td>-Resolution range mismatch between menus.</td></tr>
  <tr><td>MUI#M004</td><td align="center">Fixed</td><td align="center">✅</td><td>-Crate unlock sound playing without enough VGs.</td></tr>
  <tr><td>MUI#H005</td><td align="center">Fixed</td><td align="center">✅</td><td>-Favorites updating slowly.</td></tr>
  <tr><td>MUI#H006</td><td align="center">Fixed</td><td align="center">✅</td><td>-In-game inventory not scrollable.</td></tr>
  <tr><td>MUI#L007</td><td align="center">Fixed</td><td align="center">✅</td><td>-Blocking users in inbox not working.</td></tr>
  <tr><td>MUI#H008</td><td align="center">Fixed</td><td align="center">✅</td><td>-Daily rewards not giving skins.</td></tr>
  <tr><td>MUI#L009</td><td align="center">Fixed</td><td align="center">✅</td><td>-Daily rewards claimable without watching ads.</td></tr>
  <tr><td>MUI#M010</td><td align="center">Fixed</td><td align="center">✅</td><td>-Lighting from previous match affecting main UI.</td></tr>
  <tr><td>MUI#M011</td><td align="center">Fixed</td><td align="center">✅</td><td>-Password change requiring email change.</td></tr>
  <tr><td>MUI#M012</td><td align="center">Fixed</td><td align="center">✅</td><td>-Clan info update not saving.</td></tr>

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
<tr><td>ING#H001</td><td align="center">-</td><td align="center">🔴</td><td>Reducing in-game resolution also lowers HUD and crosshair resolution, making UI text blurry and crosshair unclear.</td></tr>
<tr><td>ING#H002</td><td align="center">-</td><td align="center">🔴</td><td>Players sometimes get stuck at the instancing spawn point below the map and never appear on the actual terrain.</td></tr>
<tr><td>ING#H003</td><td align="center">-</td><td align="center">🔴</td><td>In-game leaderboard/scoreboard does not update in real time; players who leave remain listed until refresh.</td></tr>
<tr><td>ING#H004</td><td align="center">-</td><td align="center">🔴</td><td>Only one hacker can be vote-kicked per match even if multiple hackers are present.</td></tr>
<tr><td>ING#H005</td><td align="center">-</td><td align="center">🔴</td><td>Switching weapons in-game sometimes triggers an advertisement to play unexpectedly.</td></tr>
<tr><td>ING#H006</td><td align="center">-</td><td align="center">🔴</td><td>Players joining matches (especially guest lobbies) often spawn into games with only ~20–30 seconds remaining instead of a reasonable minimum time.</td></tr>
<tr><td>ING#H007</td><td align="center">-</td><td align="center">🔴</td><td>Abilities and grenades can damage teammates in TDM mode (e.g., Mistle), causing unintended friendly-fire effects.</td></tr>
<tr><td>ING#H008</td><td align="center">-</td><td align="center">🔴</td><td>After watching an in-game advertisement, the master volume sometimes increases to an extremely high level automatically.</td></tr>
<tr><td>ING#H009</td><td align="center">-</td><td align="center">🔴</td><td>Noticeable FPS drops and ping spikes occur when the player is physically closer to enemies.</td></tr>
<tr><td>ING#H010</td><td align="center">-</td><td align="center">🔴</td><td>The Y key ad-reward shortcut activates even while typing in chat; it should be disabled when chat input is focused.</td></tr>
<tr><td>ING#H011</td><td align="center">-</td><td align="center">🔴</td><td>Black screen sometimes appears after matchmaking completes, preventing the match from loading properly.</td></tr>
<tr><td>ING#H012</td><td align="center">-</td><td align="center">🔴</td><td>Clicking a clan member’s name in the in-game report menu does not open their profile due to clan tag formatting.</td></tr>
<tr><td>ING#H013</td><td align="center">-</td><td align="center">🔴</td><td>Logging out of the account does not fully log the player out in-game unless the page is manually refreshed.</td></tr>
<tr><td>ING#H013</td><td align="center">-</td><td align="center">🔴</td><td>Several in-game character voice lines do not play, although subtitles still appear on screen.</td></tr>
<tr><td>ING#H014</td><td align="center">-</td><td align="center">🔴</td><td>Knife rank icon in GunGame does not appear on the in-game leaderboard.</td></tr>
<tr><td>ING#H015</td><td align="center">-</td><td align="center">🔴</td><td>After Sierra loading screen appears, the screen sometimes turns completely black with only the chatbox visible.</td></tr>
<tr><td>ING#H016</td><td align="center">-</td><td align="center">🔴</td><td>Chat messages now stay visible for too long (~30s) and reappear when opening chat again instead of clearing properly.</td></tr>
<tr><td>ING#H017</td><td align="center">-</td><td align="center">🔴</td><td>After dying once, the advert banner and respawn loader can remain stuck on screen for the rest of the match.</td></tr>
<tr><td>ING#H018</td><td align="center">-</td><td align="center">🔴</td><td>Guest users are forced to use Shin as the default character; sometimes they get Lilium abilities with Shin cooldown timers.</td></tr>
<tr><td>ING#H019</td><td align="center">-</td><td align="center">🔴</td><td>No button to switch weapons on mobile; players can only change weapons after dying.</td></tr>
<tr><td>ING#H020</td><td align="center">-</td><td align="center">🔴</td><td>FPS progressively drops the longer you keep playing consecutive matches (possible memory/performance leak).</td></tr>
<tr><td>ING#H021</td><td align="center">-</td><td align="center">🔴</td><td>API updates lag or fail; account-related data (current clan, market listings, etc.) updates very late or not at all.</td></tr>
<tr><td>ING#H022</td><td align="center">-</td><td align="center">🔴</td><td>Many in-game assets are still JSON and not converted to GLB, causing performance and consistency issues.</td></tr>
<tr><td>ING#H023</td><td align="center">-</td><td align="center">🔴</td><td>Map selection resets to "All" every time you leave a match.</td></tr>
<tr><td>ING#H024</td><td align="center">-</td><td align="center">🔴</td><td>Same account can join the same lobby multiple times, enabling stat boosting.</td></tr>
<tr><td>ING#H025</td><td align="center">-</td><td align="center">🔴</td><td>When a player is killed and another joins at the same moment, a non-collidable duplicate character model stands up for a few seconds.</td></tr>
<tr><td>ING#H026</td><td align="center">-</td><td align="center">🔴</td><td>Colliding with a pre-spawned player can launch the character out of the map due to unstable collision physics.</td></tr>
<tr><td>ING#H027</td><td align="center">-</td><td align="center">🔴</td><td>Mobile devices can only load/play Sierra; other maps fail to start.</td></tr>
<tr><td>ING#H028</td><td align="center">-</td><td align="center">🔴</td><td>Anticheat frequently false-kicks legitimate players and reacts slowly to actual hackers.</td></tr>

<!-- 🟡 MEDIUM PRIORITY -->
<tr><td>ING#M028</td><td align="center">-</td><td align="center">🟡</td><td>Direct URLs such as "/?map=MapName" and "/Spectate:CODE" no longer function.</td></tr>
<tr><td>ING#M029</td><td align="center">-</td><td align="center">🟡</td><td>"Hide Announcements" setting does not hide the in-game free skin notification popup.</td></tr>
<tr><td>ING#M030</td><td align="center">-</td><td align="center">🟡</td><td>Potions are not visible in matches until the player uses them once.</td></tr>
<tr><td>ING#M031</td><td align="center">-</td><td align="center">🟡</td><td>Animated texture skins (e.g., Blaze Scar, OLED Tec-9) sometimes play choppy or laggy animations.</td></tr>
<tr><td>ING#M032</td><td align="center">-</td><td align="center">🟡</td><td>Lighting does not properly affect weapons and hands in official maps; models appear flat regardless of player rotation.</td></tr>
<tr><td>ING#M033</td><td align="center">-</td><td align="center">🟡</td><td>Terrain lighting looks incorrect on bright skybox maps; shadows appear missing or too weak.</td></tr>
<tr><td>ING#M034</td><td align="center">-</td><td align="center">🟡</td><td>When a new enemy spawns and you aim at them immediately, they sometimes disappear and relocate to another spawn point.</td></tr>
<tr><td>ING#M035</td><td align="center">-</td><td align="center">🟡</td><td>Censor Username setting only hides names on the in-game leaderboard; usernames still appear in kill-feed and report lists.</td></tr>
<tr><td>ING#M036</td><td align="center">-</td><td align="center">🟡</td><td>LMG reload time does not match the on-screen reload countdown timer.</td></tr>
<tr><td>ING#M037</td><td align="center">-</td><td align="center">🟡</td><td>Crack-Hole visual effect sometimes remains floating mid-air after a player is hit with melee or throwable.</td></tr>
<tr><td>ING#M038</td><td align="center">-</td><td align="center">🟡</td><td>Lilium’s frost bomb overlay does not scale properly with higher FOV or narrower screens, leaving parts of the screen uncovered.</td></tr>
<tr><td>ING#M039</td><td align="center">-</td><td align="center">🟡</td><td>Sprays no longer appear or function during matches.</td></tr>
<tr><td>ING#M040</td><td align="center">-</td><td align="center">🟡</td><td>Ad-reward failure message is sent as a public chat message; it should be a console/system message visible only to the player.</td></tr>
<tr><td>ING#M041</td><td align="center">-</td><td align="center">🟡</td><td>HP display sometimes shows 0 HP while the player is still alive.</td></tr>
<tr><td>ING#M042</td><td align="center">-</td><td align="center">🟡</td><td>If killed while using an emote, the player cannot use emotes again for the rest of the match.</td></tr>
<tr><td>ING#M043</td><td align="center">-</td><td align="center">🟡</td><td>Map shadows use render distance instead of being static for terrain/objects, causing visual inconsistency.</td></tr>
<tr><td>ING#M044</td><td align="center">-</td><td align="center">🟡</td><td>First capture point in Sierra does not register score when standing inside it after joining a match.</td></tr>
<tr><td>ING#M045</td><td align="center">-</td><td align="center">🟡</td><td>Some map elements appear overly bright due to reflectivity issues (spinning circle, potions, grenades, etc.).</td></tr>
<tr><td>ING#M046</td><td align="center">-</td><td align="center">🟡</td><td>After dying and falling, the equipped character skin briefly switches to the default skin.</td></tr>
<tr><td>ING#M047</td><td align="center">-</td><td align="center">🟡</td><td>Glider can bug out and allow the player to glide on the ground if its collider is triggered repeatedly.</td></tr>
<tr><td>ING#M048</td><td align="center">-</td><td align="center">🟡</td><td>If weapon inspect is interrupted by dancing, shooting, or using abilities, inspect becomes unavailable for the rest of the match.</td></tr>
<tr><td>ING#M049</td><td align="center">-</td><td align="center">🟡</td><td>Suicides in GunGame are incorrectly counted as kills and the rank-kill counter increases indefinitely.</td></tr>
<tr><td>ING#M050</td><td align="center">-</td><td align="center">🟡</td><td>Players can still emote after dying once, but then permanently lose the ability to emote for the rest of the match.</td></tr>
<tr><td>ING#M051</td><td align="center">-</td><td align="center">🟡</td><td>If scoped in when the match ends, the sniper scope overlay remains above the results UI.</td></tr>
<tr><td>ING#M052</td><td align="center">-</td><td align="center">🟡</td><td>A glitchy timer audio continues playing repeatedly after death.</td></tr>
<tr><td>ING#M053</td><td align="center">-</td><td align="center">🟡</td><td>In GunGame, a rank-up kill is shown in the kill-feed as if it was made with the next weapon instead of the current one.</td></tr>
<tr><td>ING#M054</td><td align="center">-</td><td align="center">🟡</td><td>Enemies visually appear to hold the SCAR even when another weapon is equipped.</td></tr>
<tr><td>ING#M055</td><td align="center">-</td><td align="center">🟡</td><td>Ground crack, totems, and capture points always stay horizontal and do not align with sloped terrain.</td></tr>
<tr><td>ING#M056</td><td align="center">-</td><td align="center">🟡</td><td>Wall collisions/hitboxes feel inconsistent; some walls block before contact while others allow clipping close inside pillars.</td></tr>
<tr><td>ING#M057</td><td align="center">-</td><td align="center">🟡</td><td>Mistle map never appears in end-game map voting; it should be included alongside Sierra, Tundra, and Temple.</td></tr>
<tr><td>ING#M058</td><td align="center">-</td><td align="center">🟡</td><td>Kulu’s ground crack and totems remain in the match after the Kulu player leaves and cannot be destroyed.</td></tr>
<tr><td>ING#M059</td><td align="center">-</td><td align="center">🟡</td><td>When an ad-reward weapon is equipped, you cannot switch back to the default primary without switching to another slot first.</td></tr>
<tr><td>ING#M060</td><td align="center">-</td><td align="center">🟡</td><td>Assist column on end-game K/D/A is always 0 since there is no assist mechanic implemented.</td></tr>
<tr><td>ING#M061</td><td align="center">-</td><td align="center">🟡</td><td>Hackers flagged for cheating are not immediately removed; they remain until kicked for being AFK.</td></tr>
<tr><td>ING#M062</td><td align="center">-</td><td align="center">🟡</td><td>Sniper scope glitches if RMB is spammed while switching weapons at the same time.</td></tr>
<tr><td>ING#M063</td><td align="center">-</td><td align="center">🟡</td><td>Skin thumbnails sometimes fail to load on the in-game leaderboard and end-game scoreboard.</td></tr>
<tr><td>ING#M064</td><td align="center">-</td><td align="center">🟡</td><td>Objective timer is inaccurate; UI shows ~15s while actual time to next objective is often 20–30s.</td></tr>
<tr><td>ING#M065</td><td align="center">-</td><td align="center">🟡</td><td>Character rigging issues: the body can cover most of the screen while reloading, inspecting, or using throwables.</td></tr>
<tr><td>ING#M066</td><td align="center">-</td><td align="center">🟡</td><td>Match may start with SCAR even when M4/AK47 is selected as the primary loadout.</td></tr>
<tr><td>ING#M067</td><td align="center">-</td><td align="center">🟡</td><td>Ability cooldown indicators can disappear if ability keys are spammed, reappearing only after cooldown resets.</td></tr>
<tr><td>ING#M068</td><td align="center">-</td><td align="center">🟡</td><td>In-game chat filter is overly aggressive; normal words like “assumption” get partially censored.</td></tr>
<tr><td>ING#M069</td><td align="center">-</td><td align="center">🟡</td><td>"Turn off shadows" setting does not disable map shadows; they remain visible.</td></tr>
<tr><td>ING#M070</td><td align="center">-</td><td align="center">🟡</td><td>Joining at the last second can cause assets from two maps to load together (map overlap).</td></tr>

<!-- 🟢 LOW PRIORITY -->
<tr><td>ING#L080</td><td align="center">-</td><td align="center">🟢</td><td>Charms can clip into weapon models when moving, jumping, or turning at certain angles.</td></tr>
<tr><td>ING#L081</td><td align="center">-</td><td align="center">🟢</td><td>Dagger no longer displays a rank icon in Gungame mode.</td></tr>
<tr><td>ING#L082</td><td align="center">-</td><td align="center">🟢</td><td>Some skins (e.g., Valentine M4 and Sniper) appear overly reflective in-game.</td></tr>
<tr><td>ING#L083</td><td align="center">-</td><td align="center">🟢</td><td>Ammo count for AWP in Gungame sometimes displays as 0/undefined.</td></tr>
<tr><td>ING#L084</td><td align="center">-</td><td align="center">🟢</td><td>Ground terrain sometimes renders in rainbow/heatmap-like colors.</td></tr>
<tr><td>ING#L085</td><td align="center">-</td><td align="center">🟢</td><td>Birds in maps sometimes do not fly away even when players approach them.</td></tr>
<tr><td>ING#L086</td><td align="center">-</td><td align="center">🟢</td><td>Charms can clip through weapon models at certain angles or during fast movement.</td></tr>
<tr><td>ING#L087</td><td align="center">-</td><td align="center">🟢</td><td>Character hands occasionally disappear even when "Hide Hands and Weapons" is turned off.</td></tr>
<tr><td>ING#L088</td><td align="center">-</td><td align="center">🟢</td><td>Characters have no visible shadows or reflections in certain conditions.</td></tr>
<tr><td>ING#L088</td><td align="center">-</td><td align="center">🟢</td><td>Timebomb hand placement is misaligned in custom maps and can offset weapon positioning after switching.</td></tr>
<tr><td>ING#L089</td><td align="center">-</td><td align="center">🟢</td><td>Running animations sometimes freeze or stutter.</td></tr>
<tr><td>ING#L090</td><td align="center">-</td><td align="center">🟢</td><td>Default skin sometimes appears while gliding instead of the equipped one.</td></tr>
<tr><td>ING#L091</td><td align="center">-</td><td align="center">🟢</td><td>Weapon models appear positioned further forward than before, reducing realism.</td></tr>
<tr><td>ING#L092</td><td align="center">-</td><td align="center">🟢</td><td>Kulu/Shin sometimes display infinite damage numbers.</td></tr>
<tr><td>ING#L093</td><td align="center">-</td><td align="center">🟢</td><td>If a player joins right after a match ends, the map voting progress bar can visually bug out.</td></tr>
<tr><td>ING#L094</td><td align="center">-</td><td align="center">🟢</td><td>Some character skins (e.g., Egyptian Kulu) are slightly shorter, giving a minor hitbox advantage.</td></tr>
<tr><td>ING#L095</td><td align="center">-</td><td align="center">🟢</td><td>Sniper scope lens no longer appears reflective and looks static.</td></tr>

<!-- FIXED -->
<tr><td></td></tr>
<tr><td>Fixed List</td></tr> 
<tr><td></td></tr>
<tr><td>ING#H096</td><td align="center">Fixed</td><td align="center">✅</td><td>-Enemy HP bars sometimes disappeared in the next match after voting for a new map.</td></tr>
<tr><td>ING#M097</td><td align="center">Fixed</td><td align="center">✅</td><td>-Reflectivity issues where ground, rocks, and characters appeared overly reflective.</td></tr>
<tr><td>ING#M098</td><td align="center">Fixed</td><td align="center">✅</td><td>-Respawning after death previously took too long (~10 seconds).</td></tr>
<tr><td>ING#M099</td><td align="center">Fixed</td><td align="center">✅</td><td>-Bounce pad allowed higher jumps when pressing space at the moment of landing.</td></tr>
<tr><td>ING#M100</td><td align="center">Fixed</td><td align="center">✅</td><td>-Chat messages disappeared too quickly; duration was adjusted.</td></tr>
<tr><td>ING#H102</td><td align="center">Fixed</td><td align="center">✅</td><td>-AK47 Hypothermia skin texture was missing (404) and not rendering in-game.</td></tr>
<tr><td>ING#L103</td><td align="center">Fixed</td><td align="center">✅</td><td>-Controller players experienced sudden crosshair flicks after each kill.</td></tr>
<tr><td>ING#M104</td><td align="center">Fixed</td><td align="center">✅</td><td>-Gun fire-rate was incorrectly tied to FPS and varied depending on performance.</td></tr>
<tr><td>ING#L105</td><td align="center">Fixed</td><td align="center">✅</td><td>-Character skin thumbnails sometimes did not appear on the in-game leaderboard.</td></tr>
<tr><td>ING#H106</td><td align="center">Fixed</td><td align="center">✅</td><td>-Damage from weapons, throwables, and melee occasionally went unregistered.</td></tr>
<tr><td>ING#M107</td><td align="center">Fixed</td><td align="center">✅</td><td>-Only Sierra could be played even when other maps were selected.</td></tr>
<tr><td>ING#H108</td><td align="center">Fixed</td><td align="center">✅</td><td>-Valentine 2023 skins were not rendering/working in-game.</td></tr>
<tr><td>ING#H109</td><td align="center">Fixed</td><td align="center">✅</td><td>-3rd anniversary skins did not work (only charms were visible).</td></tr>
<tr><td>ING#L110</td><td align="center">Fixed</td><td align="center">✅</td><td>-Kill-feed entries sometimes got stuck on the HUD.</td></tr>
<tr><td>ING#H111</td><td align="center">Fixed</td><td align="center">✅</td><td>-Overall audio volume suddenly maxed out after leaving a game.</td></tr>
<tr><td>ING#M112</td><td align="center">Fixed</td><td align="center">✅</td><td>-Ability icons on mobile did not change per character (always showed Lilium icons).</td></tr>
<tr><td>ING#M113</td><td align="center">Fixed</td><td align="center">✅</td><td>-Camera could not be moved while dancing in-game.</td></tr>

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

<!-- 🔴 HIGH PRIORITY -->
<tr><td>HER#H001</td><td align="center">-</td><td align="center">🔴</td><td>Lilium</td><td>If Lilium dies while her grenade is still mid-air, the grenade disappears and deals no damage.</td></tr>
<tr><td>HER#H002</td><td align="center">-</td><td align="center">🔴</td><td>Echo</td><td>Echo’s grapple sometimes registers damage but the hook itself is not visually thrown, or becomes invisible mid-use.</td></tr>
<tr><td>HER#H003</td><td align="center">-</td><td align="center">🔴</td><td>Echo</td><td>Echo’s axe occasionally does no damage even when it clearly connects with the enemy.</td></tr>
<tr><td>HER#H004</td><td align="center">-</td><td align="center">🔴</td><td>Kulu</td><td>Kulu cannot be unlocked with VGs anymore and the Kulu quest does not activate until another unrelated quest is completed.</td></tr>
<tr><td>HER#H005</td><td align="center">-</td><td align="center">🔴</td><td>Kulu</td><td>Totems deactivate whenever any player dies or whenever any Kulu in the match gets a gun kill.</td></tr>
<tr><td>HER#006</td><td align="center">-</td><td align="center">🔴</td><td>Kulu</td><td>Kulu does not get upranked after a melee kill in GunGame; only the enemy gets deranked.</td></tr>

<!-- 🟡 MEDIUM PRIORITY -->
<tr><td>HER#M007</td><td align="center">-</td><td align="center">🟡</td><td>Lilium</td><td>Lilium’s grenade color appears pale pink instead of the usual darker tone and explodes slightly earlier than expected.</td></tr>
<tr><td>HER#M008</td><td align="center">-</td><td align="center">🟡</td><td>All</td><td>Grenade throw audio is too quiet unless the explosion occurs very close to the player.</td></tr>
<tr><td>HER#M009</td><td align="center">-</td><td align="center">🟡</td><td>Lilium</td><td>Grenades behave inconsistently: sometimes pass through the ground, stick to it, or bounce unpredictably.</td></tr>
<tr><td>HER#M010</td><td align="center">-</td><td align="center">🟡</td><td>Shin</td><td>Shin's hand positioning with some weapons like tec-9 and deagle is weird</td></tr>
<tr><td>HER#M011</td><td align="center">-</td><td align="center">🟡</td><td>Kulu</td><td>Kulu’s staff can be placed on any collision surface; it should only be usable on ground terrain.</td></tr>
<tr><td>HER#M012</td><td align="center">-</td><td align="center">🟡</td><td>Kulu</td><td>Kulu’s staff sometimes does not work on sloped surfaces and only functions reliably on flat ground.</td></tr>
<tr><td>HER#M013</td><td align="center">-</td><td align="center">🟡</td><td>Kulu</td><td>Totems can be spawned inside or attached to walls, roofs, rocks, water, and other collidable objects instead of only ground.</td></tr>
<tr><td>HER#M014</td><td align="center">-</td><td align="center">🟡</td><td>Kulu</td><td>Players can climb walls and reach high ground by repeatedly placing totems and spamming jump.</td></tr>

<!-- 🟢 LOW PRIORITY -->
<tr><td>HER#L015</td><td align="center">-</td><td align="center">🟢</td><td>Lilium</td><td>Lilium's dress overlaps and clips into her thigh while standing.</td></tr>
<tr><td>HER#L016</td><td align="center">-</td><td align="center">🟢</td><td>Cyborg</td><td>Cyborg skin appears fully black in-game and is not visible on the main UI.</td></tr>
<tr><td>HER#L017</td><td align="center">-</td><td align="center">🟢</td><td>Echo</td><td>Echo’s grapple can sometimes pull the player outside the map boundaries if used at certain angles.</td></tr>
<tr><td>HER#L026</td><td align="center">-</td><td align="center">🟢</td><td>Kulu</td><td>Kulu’s emission ability no longer appears to function.</td></tr>
<tr><td>HER#L027</td><td align="center">-</td><td align="center">🟢</td><td>Kulu</td><td>Only the default dance works for Kulu; other dances cannot be used.</td></tr>

<!-- FIXED -->
<tr><td></td></tr>
<tr><td>Fixed List</td></tr> 
<tr><td></td></tr>
<tr><td>HER#H028</td><td align="center">Fixed</td><td align="center">✅</td><td>Hammer</td><td>Hammer/Mallet attacks were inaccurate and hit noticeably left of the crosshair.</td></tr>
<tr><td>HER#H029</td><td align="center">Fixed</td><td align="center">✅</td><td>All</td><td>Only Hammer could de-rank enemies in GunGame, giving an unfair advantage over Echo and Kulu.</td></tr>
<tr><td>HER#H030</td><td align="center">Fixed</td><td align="center">✅</td><td>Lilium</td><td>Grenades could be spam-spawned after Lilium died, especially noticeable on mobile devices.</td></tr>
<tr><td>HER#H031</td><td align="center">Fixed</td><td align="center">✅</td><td>Shin</td><td>Shin Dash doesn't cause any damage sometimes even after intersecting with enemies.</td></tr>
<tr><td>HER#L032</td><td align="center">Fixed</td><td align="center">✅</td><td>Kulu</td><td>Egyptian Kulu had a visible tracer effect that could be seen through walls.</td></tr>
<tr><td>HER#H033</td><td align="center">Fixed</td><td align="center">✅</td><td>Kulu</td><td>Totems could be spam-spawned after Kulu died, especially noticeable on mobile.</td></tr>

</table>

<br>

<strong>Weapons</strong>

Contains problems related to weapon behavior such as firing mechanics, reload timing, positioning, textures and damage registration.

<table border="1">
  
<tr><td>WEP#M001</td><td align="center">-</td><td align="center">🟡</td><td>Deagle</td><td>The deagle's magazine is weirdly positioned sometimes.</td></tr>

<tr><td>WEP#L002</td><td align="center">-</td><td align="center">🟢</td><td>M4</td><td>The M4 starts out with 20 bullets instead of 25 when you join a game.</td></tr>

<tr><td></td></tr>
<tr><td>Fixed List</td></tr> 
<tr><td></td></tr>
<tr><td>WEP#H003</td><td align="center">Fixed</td><td align="center">✅</td><td>Kulu</td><td>Weapons start out with the same used magazine from last match if you continue to next match. It should be full-mag for every new match.</td></tr>

</table>

<br>
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
    <!-- 🔴 HIGH PRIORITY -->
<tr><td>MAP#H001</td><td align="center">-</td><td align="center">🔴</td><td>All Official Maps</td><td>Multiple advantageous/glitch spots exist across official maps that allow players to access unintended positions.</td></tr>
<tr><td>MAP#H002</td><td align="center">-</td><td align="center">🔴</td><td>All</td><td>Directional cubic lighting bug where lighting shifts in cube-like patterns based on player facing direction.</td></tr>

<!-- 🟡 MEDIUM PRIORITY -->
<tr><td>MAP#M003</td><td align="center">-</td><td align="center">🟡</td><td>All</td><td>Boxes are extremely slippery, especially in the editor, making movement and climbing inconsistent.</td></tr>
<tr><td>MAP#M004</td><td align="center">-</td><td align="center">🟡</td><td>All</td><td>Spamming jump on box edges lets players climb them unintentionally (likely tied to slippery collision).</td></tr>
<tr><td>MAP#M005</td><td align="center">-</td><td align="center">🟡</td><td>Mistle</td><td>Payload sometimes stops moving and does not progress along the route.</td></tr>
<tr><td>MAP#M006</td><td align="center">-</td><td align="center">🟡</td><td>Mistle</td><td>Cannot select teams in Mistle TDM; team selection only works in custom matches.</td></tr>
<tr><td>MAP#M007</td><td align="center">-</td><td align="center">🟡</td><td>Mistle</td><td>Teammate HP bars sometimes do not appear; when shooting teammates, the HP bar incorrectly shows as red.</td></tr>
<tr><td>MAP#M008</td><td align="center">-</td><td align="center">🟡</td><td>Mistle</td><td>Payload hitbox is too large and can trap players inside tight areas like the snake tunnel.</td></tr>
<tr><td>MAP#M009</td><td align="center">-</td><td align="center">🟡</td><td>SandstormBlitz</td><td>Players can climb large rocks by repeatedly jumping against them.</td></tr>
<tr><td>MAP#M010</td><td align="center">-</td><td align="center">🟡</td><td>GunGame</td><td>AK-47 is still missing from the GunGame weapon rotation.</td></tr>
<tr><td>MAP#M011</td><td align="center">-</td><td align="center">🟡</td><td>SandstormBlitz</td><td>Using RMB while gliding triggers the scope and slows glide movement significantly.</td></tr>

<!-- 🟢 LOW PRIORITY -->
<tr><td>MAP#L0012</td><td align="center">-</td><td align="center">🟢</td><td>All</td><td>Trees do not have hitboxes on their leaves.</td></tr>
<tr><td>MAP#L013</td><td align="center">-</td><td align="center">🟢</td><td>Mistle</td><td>Rocks near water lack proper hitboxes.</td></tr>
<tr><td>MAP#L014</td><td align="center">-</td><td align="center">🟢</td><td>Mistle</td><td>Water animation sometimes stops and appears static.</td></tr>
<tr><td>MAP#L015</td><td align="center">-</td><td align="center">🟢</td><td>Temple</td><td>Some grapple collision points flash but do not function.</td></tr>
<tr><td>MAP#L016</td><td align="center">-</td><td align="center">🟢</td><td>Tundra</td><td>Minecart tracks exist but no minecart is present; tracks may reduce performance.</td></tr>

<!-- FIXED -->
<tr><td></td></tr>
<tr><td>Fixed List</td></tr> 
<tr><td></td></tr>
<tr><td>MAP#L017</td><td align="center">Fixed</td><td align="center">✅</td><td>SandstormBlitz</td><td>Gliders were hard to control and Whirlwinds provided too little momentum.</td></tr>
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

<br>

