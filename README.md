# ElectionRevamp
Using Azure Blockchain for building secure online voting system using biometric and revamping election model

OVERVIEW

Hey! Our project focuses on revamping the current election system. Basically we are trying to solve these 2 problems in our system-
1)  In recent past, there has a been a major debate about EVMs and polling booth. At present, many parties have questioned reliability of EVM as well as these static polling booth system make it compulsory for the voter to be present at the location on the election day.
2)  In present process of electing the candidate, all the voters have to vote for 1 candidate and th candidate with most number of votes win the election. Major flaw with this system is that it does have the same share of representation of a party as its share in vote. Secondly, a voter is forced to vote for one of popular candidate and not his best preference as it wont be of any use.

So, our solution to this will include -
1)  We will make a secured online voting app using BlockChain. In this there will be an app connected with UID, which means every voter can vote only once. For those who dont have a phone, EC will facilitate voting centre at which any voter can vote from any part of the country using their UID. Security will checked by a secured biometric app. Once,a vote is casted on the app,changing it discard the vote and his chance to vote in that election. Moreover since the system is online, this will save transportation expenditure and publish the result immediately which makes the gap for corruption infinitesimally small.
Here is the flowchart of our system-

<img src="screenshot(56).PNG"> 

2)  We will make the election of the candidate a preference and point system. Algorithm of the process is-
  The voter will have to choose their order of preference of candidates. From all the top preferences, best 3 performing candidates will choosen. Rest will be eliminated. Now these 3 will get their relative preference points.Here the 1st preference of each voter will get 5 points and 2nd prefenrence will get 2 points. There will be no points for the 3rd(standby) preference. Now, if there are 'n' number of voters then to win election candidate should get least integer greate than '3.5 * n' number of points. If there is no such candidate, the candidate having the least number of non-zero points will be eliminated and the preference order and its relative points will be shifted and now the standby preference will come into picture. So, it will become a 2 cndidate system and 1 will get the majority. If only 2 candidates participate automatically winner will have majority. In this none of the candidate will act as vote cutter and not the media popular choices will have biased chance.
  
  This is how we want to develop our system.
