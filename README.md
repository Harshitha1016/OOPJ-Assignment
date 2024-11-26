 *Software Requirements:*  
   - spring tool
   - Text editor for input/output files
   - *Classes*
1. *Voter*  
   - Attributes:  
     voterID (int), name (String), hasVoted (boolean)  
   - Methods:  
     setVoterDetails(), markAsVoted(), displayVoterDetails()  

2. *Candidate*  
   - Attributes:  
     candidateID (int), name (String), votes (int)  
   - Methods:  
     setCandidateDetails(), incrementVotes(), displayCandidateDetails()  

3. *VotingSystem*  
   - Attributes:  
     votersList (ArrayList<Voter>), candidatesList (ArrayList<Candidate>)  
   - Methods:  
     registerVoters(), registerCandidates(), castVote(), displayResults()  

4. *TestClass*  
   - Methods:  
     main() (driver method for testing all functionalities)  

