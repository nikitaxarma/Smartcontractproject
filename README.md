# Smartcontractproject
IPLMatch Smart Contract Overview
  WinningUpdate Function
1.Updates wins for a specified team (India, New Zealand, Pakistan).
2.Emits UpdationOfWinning event.
3.Requires wins to be positive using require.
4.Sets wins based on the team parameter.
 CheckCompetition Function
1.Checks if Pakistan has fewer wins than India or New Zealand.
2.Uses require to enforce competition conditions.
3.Uses assert to verify internal consistency.
4.Function is view only (public view).
 getWins Function
1.Retrieves current wins for a specified team.
2.Returns wins for India, New Zealand, or Pakistan.
3.Reverts for an unknown team.
4.Function is view only (public view).
 State Variables and Events
1.Tracks wins for India, New Zealand, Pakistan with public visibility.
2.Emits events UpdationOfWinning and examine.
3.Uses enums (Team) for team selection.
4.Solidity version pragma is ^0.8.0 for compatibility.
