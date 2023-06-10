# DBMS-I_Mini_Project

                                                     Pie-in-the-Sky
                                                  IPL Match Bidding App 
 
Pie-in-the-Sky, is a mobile app that is used for bidding for IPL matches legally. Anyregistered user can bid for any of the IPL matches listed in it. New users or the bidders need to register themselves into the appby providing their mobile phone number, email id and a password.Admin will maintain the match roster and keep updating other details in the system. 
The app shows the match details which includes the playing team, the venue of the match and current standing of the teams on the points table. It will display the winner at the end of the match and update the team standings in the tournament and bidder points table. System will send updates to the bidders whenever required. It will also generate the bidders' leader board. 

**App functionalities:**
* Predict Winner 
The app allows the user to predict the winner of the match before toss happens for the match on which the user is predicting. This is dynamic as the matches can have different start time. Start time will also be influenced by disruptions like rains and other unforeseen circumstances. User will not be able to see what others users have predicted. Users can change theteam bids only till the toss happens. Once the toss happens everything freezes for that match. 
* Point System
For every win, users get points. There are no negative points, meaning if the user loses the bid, he or she does not lose his/her points. Point system is very dynamic.  
At the start of the tournament when every team is at zero points, every user who wins the prediction, wins 2 points.
If the difference in the points between two teams playing, is <= 6,but >0, then the person who predicts: 
- Team with higher points will win, gets 2 points
- Team with lower points will win, gets 3 points 
If the difference in the points between two teams playing is > 6 , then the person who predicts: 
- Team with higher points will win, gets 2 points  
- Team with lower points will win, gets 5 points 
 
* Leader Board 
At every time the user will be able to see his/her points and his/her position in the overall user standings. He/shewill also be able to see top 3 leader positions 
 
**A bidder can do following things using this app:**
* can see all the match schedules (teams, date & time of the match, location). 
* bid on a team for a match before the start of the match 
* can predict the match winner only till its tossoccurs (Note that match start time might change due to weather conditions) 
* can bid for any number of matches 
* after bidding on a team, (s)he would be able to change his/her team before the match starts 
* bidding cannot be changed once the respective match starts 
* can cancel the bid on a match; will not lose any points 
* at any time, bidder will be able to see his/her points and his/her position in the overall bidder standings. 
* can see top 3 leader positions 
* can see team standings anytime (i.e. their points tally) 
* cannot see any details of other bidders 
 
**Admin can do following activities:**
* manage tournament (tournament id, duration, description) 
* manage teams (description of players and team) 
* schedule and reschedule matches. Each team will play only once with remaining teams 
* edit details of match and stadium 
* update match statistics (date and match result of all the earlier matches) 
* declare the result ofthe match along with their scores 
* declare winner and loser along with their points 
* update team statistics (team and player performance) 
* update overview at the end of the match 
* view all the bidders bidding on a particular team and the %age of users supporting a team 

**Instructions:**
 
1. Create these tables in the database by running the database script provided 
2. The script also has statements to insert appropriate data into all these tables 
3. Test the successful execution of the script by selecting some rows from few tables 
4. Clearly understand the structure of each table and relationships among them
5. Insert / update appropriate rows into relevant tables if you need to get more rows in the output to verify your answers 
 
**Questions** – Write SQL queries to get data for following requirements: 
 
1. Show the percentage of wins of each bidder in the order of highest to lowest percentage.
2. Display the number of matches conducted at each stadium with stadium name,city from the database. 
3. In a given stadium, what is the percentage of wins by a team which has won the toss? 
4. Show the total bids along with bid team and team name. 
5. Show the team id who won the match as per the win details. 
6. Display total matches played, total matches won and total matches lost by team along with its team name. 
7. Display the bowlers for Mumbai Indians team. 
8. How many all-rounders are there in each team, Display the teams with more than 4  all-rounder in descending order. 
 
**NOTE:** For ER Diagram,Tables, and all of the above information please refer to the DBMS-I Mini Project Info file uploaded in this repository.
