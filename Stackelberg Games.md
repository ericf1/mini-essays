# Stackelberg Games

When designing human behavior, stackelberg games is a fundemental tool in game theory. Unlike normal game theory where two players make simultaneous moves, the moves are reactive. In formality, the first player is often called the leader (L) and the second player is called the follower (F). 

More interestingly, we can look at how a subgame perfect equilibrium can be formalized in this game. And thus, model what the best course of action is for the leader. When calculating the subgame perfect equilibrium of a stackelberg game, we are now looking at the maximial utility of the leader based on all of the moves that the follower can make. 

This equilibrium an be found by:
1) Solve the best response of the follower to any given action of the leader.
2) And then assume that the follower will take the best set of these actions (maximizing utility) and optimize for the leader.

This method is known as "backwards induction" where we start at the end and work back up to the optimal first player.
