Introduction
============

Before there was *FIRST*, there was the beloved MIT engineering course 2.70 : Introduction to Design, taught through the 70's and 80's by the extraordinary Dr. Woodie Flowers. Seeking a way to motivate his students beyond a simple grade he conceived of a competition between students' final designs. The course became so popular it was featured on national television, and caught the eye of Dean Kamen. The rest, as they say, is history.

![Dr. Woodie Flowers, Pappalardo Professor Emeritus of Mechanical Engineering at the Massachusetts Institute of Technology][woodie]

Dr. Flowers' influence on *FIRST* was much more than the robot games, his core values became *FIRST*'s core values and he coined the term Gracious Professionalism&reg; to inspire all of us to work hard, compete well, and treat our opponents with respect and kindness. His unfortunate passing in October 2019 was a sad shock to the whole *FIRST* family. He will be missed but not forgotten.

The team here at Robotique *FIRST* Quebec wishes to honour Dr. Flowers and acknowledge his enormous influence by adapting one of his classic games for this year's BetaBots challenge -- putting a round peg in a square hole before the other robot does. In our version teams will have 15 pegs and 25 holes to put them in, yet as always good strategy and good design will be keys to winning.

> The BetaBots challenge is intended as a learning vehicle for *FIRST* robotics teams, where students develop their skills and apply their knowledge in a low-stress, fun environment, in preparation for the upcoming FRC season. To this end the BetaBots team would like to encourage teams to prioritize student involvement during the strategizing, designing, building, and competing phases.

The Field
=========

![The playing field][field]

The game takes place on a **15\'** x **28.5\'** carpeted field, divided into three zones: Two Team Zones at either end and a central Neutral Zone. In the centre of the field is a rotating Pyramid with 25 square Holes at three different levels where teams will attempt to score their "pegs", in this case 8-inch diameter Tubes.

Robots retrieve their Tubes from a Tube Stand inside their Zone and carry them one at a time to the Pyramid. The Tube Stand is loaded by the Human Player while the Robot is in the Neutral Zone. The Tube Stand is designed by the team to make the transfer from Stand to Robot as quick and easy as possible. 

Fifteen tubes with point values from 1 to 5 are kept in a Tube Store next to the Human Player. They may take one tube at a time from the Store to the Stand, but must take Tubes in a specified order.

> As always, teams should consult the Field Drawings, as well as the Game Rules and the Technical Specifications below, for full details on specific game elements and their usage.

## Pyramid

![The Pyramid][pyramid]

The Pyramid in the centre of the field has 25 square Holes on three different Levels which affect the final Tube score. There are sixteen Holes on Level 1, eight on Level 2, and one on Level 3. Holes vary slightly in size and shape, but are at least 9 inches across. The entire Pyramid is approximately **52\"** on its sides, and **24\"** high from the carpet.

## Tubes and the Tube Store

There are fifteen Tubes for each Team, with point values from 1 to 5. Tubes are made from 8-inch _nominal_ concrete form tubes (e.g. Sonotube) cut to 7-7/8 inches in length and wrapped in green or yellow vinyl to indicate the team.

> Due to the way the cardboard tubes are manufactured their actual diameter varies from 7-3/4" to 8-3/4". All the 1-point Tubes will have a large diameter, the 3 and 4-point Tubes a medium diameter, and the 2 and 5-point Tubes will have a small diameter. 

![The Tube Store][tubestore]

The Tubes are kept in a Tube Store where they are stored in an inverted pyramid with five 1-point tubes at the top going down to one 5-point Tube at the bottom. _A Tube may only be taken from the rack if the two Tubes immediately above it have already been played._

![Examples of which tubes, in blue, may be used.][tubeexamples]

## Team Tube Stand and Tube Stand Base

![Cross section view of the Tube Stand Base. Refer to the CAD drawings for more detail.][tubestandbase]

The Robots retrieve the game pieces from a Tube Stand, which the teams design and build. It is very important in this game to be able to pick up and deliver the Tubes in the shortest amount of time, so an efficient design will be paramount. The Team Tube Stand is set on the Tube Stand Base, a heavy 16" diameter cylinder 10" high. There is a one inch squre hole through the Tube Stand base for teams to insert their Tube Stands.

## Human Player: Safe Zones and Safety Mat

Since the Human Players will be entering the field during play to load the Tube Stand the following **must** be obeyed:

* The Human Player must remain on the safety mat whenever their Robot is not in the Neutral Zone
* The Robot must not enter the Team Zone when the Human Player is not on the Safety Mat
* The Human Player must not go outside the marked Safe Zone while on the field
* Robots will incur a penalty if they break the line of the Team Zone while the Human Player is not on the Safety Mat
* Robots will be disabled immediately if they completely enter the Team Zone and the Human Player is not on the Safety Mat

## Robot Start Square

Robots start the match fully covering the Start Square, and can earn bonus points for finishing the match parked over it. 

## Field Walls

The field walls are not to be touched by Robots or the Human Player. Be cautious when driving or when entering or exiting the field. Penalties will be issued for hitting the walls. Severe hits can result in the robot being disabled.

The Game
========

Robots take Tubes one at a time from their Stand and score them on the Pyramid in the centre of the field. Tubes have different point values, and the Pyramid has different scoring Levels. While the Robot is in the Neutral Zone the Stand is re-loaded with a Tube chosen by the Human Player.

Tubes that are completely inside a Hole in the Pyramid may not be removed by either team. Tubes that are not fully inside a Hole may be moved by either team.

Robots may not cross into the other team's zone.

Each match lasts **3 minutes**. For the first fifteen seconds the robots run fully autonomously, then the drivers take over for the remaining time. When the field has come to rest points and penalties are evaluated.

## Pre-Match

![The human player exchanging Tubes before the match.][tubeexchange]

* Prior to the start of the match the team may elect to exchange one or two Tubes from the Tube Store for Auto Tubes and load them onto the Tube Stand on the field. The Tubes must be of different values.

> This is the only time teams may access higher value Tubes before using the Tubes above them.

* Before the match can start the Robots must be fully covering the Start Square, Human Players must be on the Safety Mat, and Drivers must be behind their line.

> Teams may not bring devices (e.g. tape measures, squares) to assist the placement of their robots on the Field.

## Autonomous

* If the Robot removes an Auto Tube from the Stand the team immediately scores the value of the Tube. Tubes must not be supported by the Team Tube Stand or the Tube Stand Base to be considered removed. Tubes that are knocked to the floor do count as removed.

* A Tube placed on the Pyramid during Auto scores additional points, however **Autonomous Tubes do not benefit from the Level Multiplier.**

* The robot must fully leave the Team Zone before picking up the (optional) second Tube. If two Tubes are removed from the stand before the robot has left the Team Zone only the higher point value Tube will be scored.

* A Robot crossing the Zone Line in Autonomous will earn two additional points.

> Auto Tubes that have not been placed on the Pyramid by the end of Autonomous are out-of-play and may not be scored during Teleop. Autonomous Tubes still on the Team Stand after Autonomous may be removed by the Human Player after Autonomous has ended – provided of course that the Robot has left the Team Zone. Tubes that have fallen in the Human Player Safe Zone may be cleared away.

## Teleoperated

* Drivers take control of the robot to score points and play defense against the opposing team. 

* Robots can rotate the Pyramid as they wish to help them score, or to hinder the other team.

* Robots may interact with the opposing robot, but may not cross into the opposing team's zone and may not cross their mid field line.

* At the end of Teleoperated teams may elect to park their robot on the Start Square to earn extra points – or they may attempt to place one last Tube!

## Evaluation

Match Points (**MP**) are used to determine the winner of the match. Ranking points (**RP**) are used to determine the overall classification for the tournament. 

### Match Points

![Examples of Match Points scored for Autonomous and Regular Tubes][mpexample]

#### Autonomous

* Each Tube removed from the stand scores MP equal to its point value.
* Each Tube placed on the Pyramid scores MP based on the Pyramid Level:
	* **1 MP** for being supported on the first Level,
	* **2 MP** for being supported by the second Level,
	* **3 MP** for being supported by the third Level.

	> Note that an Auto Tube's value has no influence on the **MP** when score on the Pyramid.
	> Note also that the Pyramid scores are only determined at the end of the Match.

* **2 MP** is scored if the robot crosses the Team Line.

#### Teleoperated

* The _Tube's value_ is multiplied by the _Pyramid Level_ to determine **MP**. For example:
	* A 3-point Tube supported by the second Level will score 6 MP
	* A 1-point Tube on the third Level scores 3 MP

* **2 MP** are scored if the robot finishes the Match covering any part of the Start Square

### Ranking Points

* **2 RP** are awarded for a win, **1 RP** for a tie, and **0 RP** for a loss.

![Example showing ranking points earned by having Tubes on all four sides of a Level.][rpexample]

* **1 RP** is awarded for each Level of the Pyramid where a team has a Tube on **each of the four sides** (corner holes count for both sides). 

	> Tubes must be fully inserted in a hole to count for RP. Both teams can score ranking points for the same level.

Match Rules
===========

1. **Seated Tubes are sacred; everything else is fair game.** Tubes that are completely in a Hole either horizontally or vertically may not be moved from their position, all others may be manipulated by either team.

	- VIOLATION: Foul (2pts) plus the value of the unseated Tube. Yellow Card if strategic.

1. **Tubes must remain off the ground.** Tubes that have touched the carpet are considered out-of-play, and may not be returned to the Tube Stand nor the Tube Store. 

	> Only unscored Autonomous Tubes still on the Stand and fallen Tubes in the Human Player Zone may be removed from the field by the Human Player.

	- VIOLATION: Yellow Card if strategic.

1. **Robots can handle only one Tube in the Team Zone.** Once inside the Neutral Zone a Robot may control more than one game piece.

1. **Human Players transfer Tubes from the Tube Store to the Tube Stand.** Teams may not dump Tubes in order to access higher value Tubes. 

	- VIOLATION: Yellow Card if strategic

	> If a Tube gets stuck in the Tube Stand, the robot must first make contact with the Tube Stand Base, then return fully into the Neutral Zone, before the Human Player can fix the jammed Tube.

	> If a Tube gets stuck in the robot the driver may bring the robot so that it is over the Human Player Safe Zone, disable the robot, go to the field to remove the Tube, then return to the driver station to re-enable the robot. **This is never likely to be allowed in a *FIRST* Robotics Competition, but BetaBots is supposed to be slightly more forgiving to teams.**

1. **The Tube Store order must be respected.** Before removing a desired Tube from the Tube Store, all the Tubes above it must have been put in play first. _This does not apply to Auto Tubes._

1. **Human players must stay safe.** If a robot is in the Team Zone, Human Players must be standing on their Safety Mat. If the Human Player is off the Safety Mat, robots must be entirely in the Neutral Zone. Human Players entering field must remain within the marked Human Player Zone.

	- VIOLATION: If the robot is entirely within the Team Zone and the Human Player is not on their Safety Mat, Disabled
	- VIOLATION: If the robot is over the Neutral Zone line and the Human Player is not on their Safety Mat, Foul (2pt)

	> The Human Player and the robot must never be in the Team Zone at the same time. It is important that the Driver and Human Player coordinate so that this never happens.

1. **Robots operate in their Team Zone and the Neutral Zone** - their wheels may not cross into the opponent’s Team Zone or over their Mid Line.

	- VIOLATION: If <5 seconds, Foul (2pts);
	- VIOLATION: If >5 seconds or completely crossing the opponent’s tape line, Disabled 

1. **Do no harm.** Do not damage the carpet, game pieces, or run into Field Walls, etc. 

	- VIOLATION: Foul (2pts) for touching a wall
	- VIOLATION: Disabled if 3 collisions are registered by a robot, or for a significant impact

	> Field Walls have collision detectors to detect contact. There are also two detectors at each field opening. Make sure Human Players are especially wary of triggering these when entering and exiting the field. 

1. **Pushing is ok, poking and grappling are not.** Initiating deliberate or damaging contact with another robot within its perimeter is not allowed; nor are strategies aimed at damaging other robots.

	- VIOLATION: Red Card.

	> Teams should be cautious when engaging directly with other robots. Robots with mechanisms outside the frame perimeter should design their robots to withstand legal contact.

1. **Keep pinning to <5 seconds.** If a team’s robot is immobilized by another, the referee will begin a five second countdown (5-count). The pinning robot must back away at least five feet from the pinned robot and wait at least three seconds to reset the referee’s 5-count. 

	- VIOLATION: Foul (2pts).

	> Pinning does not require contact between robots; e.g. a robot “blockaded” between an opponent and a field element could be considered pinned if the robot is prevented from any meaningful movement. This includes robots pinned against a Team Zone occupied by a Human Player.

1. **Gracious Professionalism at all times.** Egregious behaviour or strategic rule violations, on or off the field, may be subject to Yellow Cards as determined by the Head Referee. Particularly malicious actions may force an escalation to a Red Card, resulting in match disqualification. Teams who seek to force penalties on the opposing team will be treated as violating the spirit of the rules.

1. **Only Drivers may touch the robot controls** including the Driver Station laptop at any point during the Match. Coaches may disable the robot for a safety-related emergency.

	- VIOLATION: Red Card.

1. **Drive Teams and Coaches must remain at their station** during the entire Match.

	> The driver may leave the Driver Station to remove a stuck Tube as described above.

1. **One student, one Head Referee.** If a team has a question about a match they may  send _one_ student  to address the Head Ref. They should indicate their desire to speak with the referee, to the referee, immediately after the Match.

	> Just as in the *FIRST* Robotics Competition, Yellow Cards remain with Teams throughout the tournament. The collection of two Yellow Cards results in an automatic Red Card. Red Cards result in match disqualification; the team is awarded no points for that match.

Technical Specifications
========================

1. **There is no height limit.** Be reasonable.

1. **There is no weight limit.** That said, a maximum of two people must be able to safely lift the robot.

1. **Robot mechanisms may extend up to 30″ past the robot perimeter.** 

  ![Perimeter of a robot in red.][perimeter]

	> In this year’s BetaBots competition, a robot may begin the match outside its robot perimeter – Note that this is different from typical FRC rules.

1. **Robots must have bumpers.** Bumpers will be provided with the field in yellow and green.

	> Please note that BetaBots Bumper Rules are less restrictive than in the *FIRST* Robotics Challenge. It is strongly advised to be familiar with the Bumper Rules in Section 10.5 Bumper Rules on page XXXXX of the 2020 FRC Robot Rules.

1. **2020 *FIRST* electrical, control, and pneumatic system rules apply.** 

1. **Robots must be safe.** Robots must not pose a hazard to the Field, the internals of other robots, or people. Robot Inspectors will have the final say on robot safety.

1. **The robot must be inspected prior to its first Match** by a Robot Inspector. Any required changes must be made before a robot is allowed to compete. Any significant changes made during the competition must be re-inspected. 

	- VIOLATION: Red Card for starting a match without prior (re)inspection

	> While a non-conforming robot may participate at the discretion of the Lead Robot Inspector and the Head Referee, it will not be permitted to advance to  the playoffs, and may not be eligible for awards. A robot that doesn’t follow Technical Specifications likely won’t win any technical awards.

1. **Components from previous robots may be reused.** However _old assemblies must be completely taken apart, then reassembled,_ before use in your 2020 BetaBots Competition robot. This does not apply to bumpers, bumpers do not need to be disassembled.

	- VIOLATION: Judged on a case-by-case basis

	> BetaBots is meant to be less taxing on a team’s resources, but should still be an opportunity for students to learn.

1. **Tube Stands are for winners.** Teams are strongly encouraged to make a Tube Stand of their own design, though teams have the option of simply placing Tubes directly on the Tube Stand Base. 

	> Teams should consult the Field Drawings for details about the Tube Stand Base.

1. **The Tube Stand must fit within the footprint of the Tube Stand Base**. There is no height limit. Tubes on the Tube Stand may extend beyond the Base.

1. **The Tube Stand may have moving parts**. Any moving parts must abide by safety rules outlined by [RXXXX]

Event
=====

1. The event is divided into two parts, the **Qualification** and the **Playoff** rounds. A typical event consists of about 8 Qualification matches per team, about 20 matches total, and 4-6 Playoff matches.

1. **During Qualifications, teams compete against each other in pre-assigned Matches.** 

	> The Match schedule will be provided to teams at the beginning of the event. Teams play an equal number of qualifying Matches.

1. **Teams must send a drive team member to their Match if their robot has passed an initial, complete inspection.** If their robot is unable to compete in a match, the team must at least send a drive team member to the field for their Match.

	- VIOLATION: Red Card 

1. At the end of the qualification round, **the final ranking will determine which teams move on to the playoffs**. Ranking is determined by the teams’ cumulative Ranking Points. Tie breaks are first determined by the cumulative number of Match Points scored during Autonomous, followed by the total cumulative number of Match Points scored.

	|    Team Ranking                             ||
	|----------|-----------------------------------|
	| 1st sort | Cumulative RP                     |
	| 2nd sort | Cumulative MP scored on the Pyramid during Auto |
	| 3rd sort | Cumulative total MP scored*      |

	*Foul points are not considered for tie-breaking 

	![Playoff round structure.][playoffs]

1. **During the playoff round, Match winners are determined by the number of Match Points scored.** Tie breaks are determined using Table XX-XX below. Ranking Points are not considered, i.e. there is no bonus for scoring four sides of the Pyramid.

	|        Playoff Tie-breaking                  ||
	|---------------|-------------------------------|
	|	1st condition | Tubes scored on the Pyramid during Auto |
	|	2nd condition | Match Points scored during Auto |
	|	3rd condition | Tubes scored on Level 3 |
	| 4th condition | Tubes scored on Level 2 |
	| 5th condition | Tubes scored on Level 1 |

1. **In the semi-finals teams play head-to-head in a single deciding match.**

1. **In the finals teams play a best-of-three series.** The first team to win two matches wins the event.


[woodie]:        images/WoodieFlowers.jpg    {height=6cm}
[field]:         images/Field.png            {height=9cm}
[pyramid]:       images/Pyramid.png          {height=6cm}
[tubestore]:     images/TubeStore.png        {height=6cm}
[tubeexamples]:  images/TubeExamples.png     {height=6cm}
[tubestandbase]: images/TubeStandBase.png    {height=6cm}
[tubeexchange]:  images/AutoTubeExchange.png {height=6cm}
[mpexample]:     images/MPExample.png        {height=6cm}
[rpexample]:     images/RPExample.png        {height=6cm}
[perimeter]:     images/Perimeter.png        {height=6cm}
[extend]:        images/ExtendBeyondPerimeter.png {height=8cm}
[bumpers]:       images/Bumpers.png          {height=8cm}
[bumperzone]:    images/BumperZone.png       {height=8cm}
[playoffs]:      images/playoffs-en.eps      {height=8cm}
