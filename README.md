Marcel's Starcraft II hotkeys
=============================

This is my hotkey configuration. I use a non-QWERTY keyboard layout for programming, so a more
ergonomic layout in Starcraft should follow. My goals are to reduce finger travel distance and
improve endurance without a bold total overhaul like
[TheCore](https://tl.net/forum/sc2-strategy/341878-thecore-advanced-keyboard-layout).

* [W] and [E] are used as control groups 8 and 9. This puts 7 groups on the left side of the
	keyboard which is plenty for my play.
* [Q] is idle worker.
* [Control] + number now *adds* to group and [Shift] or [Alt] + number *creates* control group,
	effectively reversing the default. This is a big change but it's the right one.
	* If you [Shift] click units out of a group you normally have to switch to [Control] to reassign
		the group.
	* If you [Control] click a type of unit or building you probably want to add them into a group.
		This is very common with Zerg eggs.
	* By switching this hotkey you don't have to jump between [Shift] and [Control] nearly as much.
* "Take away" control groups are the default. You basically never want to add one unit to two
	control groups, so this layout entirely prevents that from happening.
* [Alt] + [`] assigns to group 0, effectively creating a "trash" group. This is useful for quickly
	removing undesired units from a group.
* Side mouse button is bound to drag scroll. You should also invert drag scoll direction in
	settings, this matches the feeling of dragging on the minimap or iOS. This change is super easy to
	get used to and edge scrolling is barbaric. Disable edge scroll while you're at it.
* Camera hotkeys are [F1] - [F8] instead of [F5] - [F8]. Camera locations are set with [Control] +
	F-key. "Center camera" is bound to [Control] + [Escape] so to set a centered location you can
	press [Control] + [Escape] + F-key.
* [Comma] is "select all army" because you should be avoiding it, but sometimes you'll want it.
* [F] is attack move. Your pinky is your weakest finger so why is it responsible for the most common
	command?
* [Z] is patrol
* [Space] becomes "primary ability" instead of "jump to last event". This is great because it's big
	and easy to find and adds another finger into the mix. [R] is "secondary ability". Examples of
	primary abilities are Stim Packs, Burrow Widow Mine, Siege Mode, Abduct, Adept Shade, Research
	Yamato, Research Zergling Speed, etc. Examples of secondary abilities are Parasitic Bomb, Anti-Armor
	Missle, Research Hydralisk Speed, etc.
* [T] is usually movement based abilities: Tactical Jump, Lift Off, Uproot, etc.
* [`] is "jump to last event". I find that this feature is pretty unreliable but I still like to
	have it around.
* Every key except [A], [R] and [Space] are rapid fire. Many abilities have rapid fire and non-rapid
	fire abilities. For example, Corrosive Bile is bound to both [Space] and [C] so you can use [Space]
	for precision casting and [C] for rapid casting.
* It's still a good idea to avoid using the same hotkeys for units that are often used together. So,
	for example, Stim Packs are [Space] but Afterburners are [R]. Getting these two abilities mixed up
	would be detrimental. Sometimes this hits in surprising ways, for example, I had "Mutate Ventral
	Sacs" and "Spawn Creep Tumor" both bound to [C]. Since Overlords tend to hang out at the edge of the
	creep where I'm also spawning Creep Tumors I had the tendency to accidentally morph Overlords while
	trying to creep. This was fixed by changing "Mutate Ventral Sacs" to [T].
* [V] and [B] are "transform" hotkeys: Burrow & Unburrow, Fighter Mode & Assult Mode, Siege (also
	[Space]) & Unsiege, Load & Unload, so on.
* Common commands are unified between races. [D] always makes a worker. [F] makes a Supply Depot or
	Pylon. [B] makes a Barracks, Gateway, or Spawning Pool. [V] makes an Engineering Bay, Forge, or
	Evolution Chamber. And so on.
* Common finger bigrams are avoided. For example "Build Refinery" by default would be [B], [R]--
	both keys are pressed with the index finger. With my hotkeys it is [D] (or [Space]), [G].
* You can rapid fire building of Missle Turrets, Spine Crawlers, or Spore Crawlers by selecting a
	group of workers and holding down [C] while moving your mouse around. [X] for Spore Crawlers.
	Protoss doesn't need this trick because you can just shift click multiple cannons.
* [Tab] closes in-game dialogs. This is good because if you click the race dialog in the top right
	to remind yourself what opponent you're facing and then you accidentally hit [Escape] twice you'll
	cancel whatever you have selected. This could cause your almost-done worker to stop building, or
	explode a Hatchery that's under constuction. [Tab] is a lot safer.
* Co-op messes a lot of things up. For example, Stukov's Banshees can cloak and burrow which means
	those abilities can't share a hotkey on ladder.
* [Backspace] is bound to "mouse click" so you can mouse over annoying critters and hold backspace
	and they automatically explode.


Operating System Settings
-------------------------
Map [Caps Lock] to [Control]. This is a common trick familiar to grumpy old emacs programmers. This
really helps with ergonomics and accuracy in Starcraft II as well.

Set your key repeat delay and rate very fast. I use the following settings on OS X which are more
aggressive than Settings lets you choose. You have to logout after changing these settings. Any
shorter delay and my non-Starcraft work is affected, due to undesired repeated keys.
```
# The scale of these settings is 15ms. So 9 -> 135ms.
defaults write -g InitialKeyRepeat -int 9  # min is 15 in GUI. 
defaults write -g KeyRepeat -int 1         # min is 2 in GUI.
```

Windows has similar settings in Regedit.
