---CLLSN DOCS---

--Rules--

(r) - means something is required
(default = @datatype) - shows the default datatype the variable will be

--Functions--

init(length - @number - How long the level will be in seconds (r), invisG - @group - Defines the invisible group (default = 1g), lockG - @group - Defines the group that locks x-axis movement to the player (default = 2g), hide - @bool - Decides whether to hide the player or not (default = true), BG_RGB - @array - The RGB values of BG (default = [0,0,0]), GROUND_RGB - @array - The RGB values of GROUND (default = [0,0,0]), GROUND2_RGB - @array - The RGB values of ground (default = [0,0,0]), LINE_RGB - @array - The RGB values of LINE (default = [0,0,0])) - Initiates the level

setup_kill(spike_group - @group - The group of the spike that kills the player (r), controls - @bool - Whether the player has used the button controls in there program, leave blank if you have used gamescene.button (default = true)) - Sets up a spike to kill the player when the kill() function is called

kill(spike_group - @group - The group of the spike that kills the player, this is the same group as setup_kill (r)) - Kills the player if setup_kill() has been called
