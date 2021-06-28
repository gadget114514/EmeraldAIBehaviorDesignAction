# EmeraldAIBehaviorDesignAction
EmeraldAI BehaviorDesigner Action

EmeraldAI Action of Behavior Designer

This is bridge software for proprietary software, Emerald AI(Black Horizon Studios) and Behavior Designer for Everyone(opsive)


https://assetstore.unity.com/packages/tools/ai/emerald-ai-2-0-40199
https://assetstore.unity.com/packages/tools/visual-scripting/behavior-designer-behavior-trees-for-everyone-15277

Behavior Designer actions are defined for each Emerald AI API.

Select Emerald AI Action from "Actions"-"EmeraldAI".


You know that, at most case, both AIs are evaluated, so tha stacking between AIs frequently would occur. 



In order to avoid conflict of twe AIs, the following figure shows usage of two AIs in different territory. 
Main enemy AI is Behavior Designer defined one. It goes to a position.
Then when the player walks to close the enemy stopping at the position, the enemy's emerald AI becomes activated.


![SimpleExample](https://user-images.githubusercontent.com/34733747/123567250-aa127980-d7fc-11eb-8bbb-bbc4525e8381.png)


Behavior Designer provides flexible AI but if you want to get instant solution, emerald AI is good for such demand.
On the other hand, emerald AI maybe is not suitable for tactic or formation, for such usecase, Behavior Designer is good solution.
