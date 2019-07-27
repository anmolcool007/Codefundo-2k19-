# Master_of_Puppets
(Codefundo++ hackathon) Project using Azure Blockchain to make election process more efficient 

## Team Members
- <a href = "https://github.com/anmolcool007">Anmol Gupta</a>
- <a href ="https://github.com/hardr0ck-CODER/">Yash Chaubey</a>

## Loopholes
- <b><u>Loophole-1:</b></u>  As the technology is advancing, we still rely on pen-paper based issue of Voter-Id card. There are also several cases where same person gets two voter Id cards of different polling booths on the other hand there are also cases where eligible citizens are not issued Voter Id Card due to repetetive and exhaustive process for the issue of Voter Id Card.
- <b><u>Loophole-2:</b></u>  There is no real time link (specially in rular areas) between Voter's presence and  him/her casting the vote, the process of casting a vote generally involves approximately 2 steps, first the verification of the voter, which is generally done by an officer. After verification, the officer lets the voter cast his/her vote. One of the drawback is that the officers in rural areas maybe corrupt and let a person impersonate another valid or dummy voter.
- <b><u>Loophole-3:</b></u>  Voters who are away from there hometown have to go through tedious process of changing there address in order to cast their vote, due to packed schedule one hesitates to go through this process which leads of low percentages of casted votes.
- <b><u>Loophole-4:</b></u>  Many times the profile of concerned candidates are not transparent to the Voters, which leads to wrong decisions finally giving precious votes to wrong person.

## Solutions
- <b><u>Solution for Loophole-1:</b></u>  After having such great sucess in creating a database linked with Adhaar, which can be used to automatically generate Voter Id card as soon as a citizen becomes eligible to vote, furtger the person can be informed and is Voter Id card sent to his doorsteps by which his physical verification can also be done.
- <b><u>Solution for Loophole-2:</b></u>  Different stages in the process of casting vote will be treated as a block, and using Azure Blockchain service even if single  stage is disrupted, concerned authorities will be notified and the vote shall not be counted. By using IOT, voter's finger print is verified from the Adhaar database and a real time unique session for that voters starts which ends when the EVM button is pressed and all these verification and stages are hashed and protected using blockchain to assure that no one (not even corrupt election officers) can breach voting process.
- <b><u>Solution for Loophole-3:</b></u>  Before giving Voter Slip and creating voters list Voters list of polling booths, a voter can fill his preference location for voting (Default location for all voters will be given nearest to their address meintioned in Voter Id Card).
- <b><u>Solution for Loophole-4:</b></u>  An online dtabase will be maintained showing information of candidates such as criminal charges, net worth, previous experience, educational qualifications etc, which can help voters to choose their perfect candidate wisely.

## Technologies Used
-Azure Blockchain Service
-Raspberry pi 3 
-Django
-Other Rest APIs

<Centre>ns in our views would enhance the Election process and make it more smooth, fun and secure. Ensuring we are not just mere puppets in the hands of few powerful Masters.</entre>




