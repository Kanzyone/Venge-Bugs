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
    <td>🔴 High Priority</td>
    <td>71</td>
  </tr>

  <tr>
    <td>🟡 Medium Priority</td>
    <td>106</td>
  </tr>

  <tr>
    <td>🟢 Low Priority</td>
    <td>51</td>
  </tr>

  <tr>
    <td>✅ Confirmed Fixed</td>
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

<strong>Main UI</strong>

Covers issues related to the main interface outside of gameplay, including menus, shop, inventory, login systems, quests, notifications and general user interaction elements.

Aşağıdaki satırları mevcut tablonun altına aynı formatta ekleyebilirsin:

<table>
  <tr> 
    <th>ID</th> 
    <th>Status</th> 
    <th>Priority</th> 
    <th>Description</th> 
  </tr>

  <!-- 🔴 HIGH PRIORITY (ACTIVE) -->
  <tr><td>#MUI-001</td><td>Active / Pending</td><td>🔴 High Priority</td><td>After every match an advert tries to play but doesn't. This also causes the cursor to lock automatically on the UI and disappear.</td></tr>
  <tr><td>#MUI-008</td><td>Active / Pending</td><td>🔴 High Priority</td><td>Clan chat shows message senders' name as "Guest" instead of the actual username.</td></tr>
  <tr><td>#MUI-013</td><td>Active / Pending</td><td>🔴 High Priority</td><td>Language settings in general settings don't work.</td></tr>
  <tr><td>#MUI-015</td><td>Active / Pending</td><td>🔴 High Priority</td><td>There is no delete clan button in clan settings for newly made clans. Only a leave button which is useless since owners cannot leave their own clan.</td></tr>
  <tr><td>#MUI-019</td><td>Active / Pending</td><td>🔴 High Priority</td><td>On the Shop UI if you don't have enough VGs but try to open a crate, it gives you option to watch ads to get VGs. After watching those ads no VGs are added to your account.</td></tr>
  <tr><td>#MUI-024</td><td>Active / Pending</td><td>🔴 High Priority</td><td>New accounts log out on their own very frequently and randomly.</td></tr>
  <tr><td>#MUI-028</td><td>Active / Pending</td><td>🔴 High Priority</td><td>Custom match issue: if you don't join within 10 seconds of creating a match, you get the alert "Session is not available!".</td></tr>
  <tr><td>#MUI-030</td><td>Active / Pending</td><td>🔴 High Priority</td><td>Sometimes the loader on the play button spins infinitely after it is clicked.</td></tr>
  <tr><td>#MUI-038</td><td>Active / Pending</td><td>🔴 High Priority</td><td>"An error occurred" alert appears even after completing a quest.</td></tr>

  <!-- 🟡 MEDIUM PRIORITY (ACTIVE) -->
  <tr><td>#MUI-004</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Multiple dances can be selected in the Shop inventory at once.</td></tr>
  <tr><td>#MUI-006</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Cannot see if message sender is online/offline.</td></tr>
  <tr><td>#MUI-007</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Emojis before name are not removed after selling.</td></tr>
  <tr><td>#MUI-010</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Inbox system not live; must reopen to see messages.</td></tr>
  <tr><td>#MUI-014</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Unfavoriting item shows blank alert popup.</td></tr>
  <tr><td>#MUI-020</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Same quests give different rewards; Kulu repeats.</td></tr>
  <tr><td>#MUI-023</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Free skin notification causes visible lag.</td></tr>
  <tr><td>#MUI-025</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Quest claim button doesn't work.</td></tr>
  <tr><td>#MUI-027</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Ad rewards should pop after 15 minutes.</td></tr>
  <tr><td>#MUI-029</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Free skin popup doesn't disappear.</td></tr>
  <tr><td>#MUI-033</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>"Already claimed reward" alert repeats.</td></tr>
  <tr><td>#MUI-037</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>Irrelevant alerts after refresh.</td></tr>
  <tr><td>#MUI-039</td><td>Active / Pending</td><td>🟡 Medium Priority</td><td>LMG can't be unlocked from loadout.</td></tr>

  <!-- 🟢 LOW PRIORITY (ACTIVE) -->
  <tr><td>#MUI-011</td><td>Active / Pending</td><td>🟢 Low Priority</td><td>Character animations on main UI are static.</td></tr>
  <tr><td>#MUI-016</td><td>Active / Pending</td><td>🟢 Low Priority</td><td>Equipped skin sometimes not applied after navigation.</td></tr>
  <tr><td>#MUI-018</td><td>Active / Pending</td><td>🟢 Low Priority</td><td>No lock icons over M4 and AK47.</td></tr>
  <tr><td>#MUI-021</td><td>Active / Pending</td><td>🟢 Low Priority</td><td>Register button logs user in.</td></tr>
  <tr><td>#MUI-026</td><td>Active / Pending</td><td>🟢 Low Priority</td><td>Friend list shows account age instead of last online.</td></tr>
  <tr><td>#MUI-032</td><td>Active / Pending</td><td>🟢 Low Priority</td><td>Must log in separately across subdomains.</td></tr>
  <tr><td>#MUI-035</td><td>Active / Pending</td><td>🟢 Low Priority</td><td>Kulu quest appears as regular quest.</td></tr>
  <tr><td>#MUI-042</td><td>Active / Pending</td><td>🟢 Low Priority</td><td>Multi quick-sell doesn't sell multiple skins.</td></tr>

  <!-- ✅ FIXED (EN ALT) -->
  <tr><td>#MUI-002</td><td>✅ Fixed</td><td>🟡 Medium Priority</td><td>Ad rewards popup limit issue.</td></tr>
  <tr><td>#MUI-003</td><td>✅ Fixed</td><td>🟢 Low Priority</td><td>Skin equip delay.</td></tr>
  <tr><td>#MUI-005</td><td>✅ Fixed</td><td>🟢 Low Priority</td><td>Resolution range mismatch.</td></tr>
  <tr><td>#MUI-009</td><td>✅ Fixed</td><td>🟢 Low Priority</td><td>Spinner sound plays without enough VGs.</td></tr>
  <tr><td>#MUI-012</td><td>✅ Fixed</td><td>🟡 Medium Priority</td><td>Favorite delay issue.</td></tr>
  <tr><td>#MUI-017</td><td>✅ Fixed</td><td>🔴 High Priority</td><td>Inventory not scrollable.</td></tr>
  <tr><td>#MUI-022</td><td>✅ Fixed</td><td>🔴 High Priority</td><td>Can't block users in inbox.</td></tr>
  <tr><td>#MUI-031</td><td>✅ Fixed</td><td>🟡 Medium Priority</td><td>Daily rewards skins missing.</td></tr>
  <tr><td>#MUI-034</td><td>✅ Fixed</td><td>🔴 High Priority</td><td>Claim rewards without watching ads.</td></tr>
  <tr><td>#MUI-036</td><td>✅ Fixed</td><td>🟡 Medium Priority</td><td>Lighting bug after match.</td></tr>
  <tr><td>#MUI-040</td><td>✅ Fixed</td><td>🔴 High Priority</td><td>Password change requires email change.</td></tr>
  <tr><td>#MUI-041</td><td>✅ Fixed</td><td>🟡 Medium Priority</td><td>Cannot update clan info.</td></tr>

</table>


<br>

<strong>In-game</strong>

Includes bugs that occur during active gameplay such as HUD problems, animations, audio, performance issues, mechanics and player interactions.

<table border="1">
    <tr>
        <th>ID</th>
        <th>Status</th>
        <th>Priority</th>
        <th>Description</th>
    </tr>
    <tr>
        <td>IG-001</td>
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

