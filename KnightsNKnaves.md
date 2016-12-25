Knights and Knaves logic puzzle were made populate by the logician and mathematician Raymund Smullyan. In the puzzle Knights will always answer truthfully and knaves will always answer falsely. The aim of the puzzle is to deduct from the statements provided, who is a knight and who is a knave.

A very special island is inhabited only by knights and knaves. Knights always tell the truth, and knaves always lie.

1. You meet two inhabitants: Zoey and Mel. Zoey tells you that Mel is a knave. Mel says, “Neither Zoey nor I are knaves.”

2. You meet two inhabitants: Peggy and Zippy. Peggy tells you that “of Zippy and I, exactly one is a knight'. Zippy tells you that only a knave would say that Peggy is a knave.

3. You meet two inhabitants: Sue and Zippy. Sue says that Zippy is a knave. Zippy says, “I and Sue are knights.”

4. You meet two inhabitants: Sally and Zippy. Sally claims, “I and Zippy are not the same.” Zippy says, “Of I and Sally, exactly one is a knight.”

5. You meet two inhabitants: Homer and Bozo. Homer tells you, “At least one of the following is true: that I am a knight or that Bozo is a knight.” Bozo claims, “Homer could say that I am a knave.”

6.  You meet two inhabitants: Marge and Zoey. Marge says, “Zoey and I are both knights or both knaves.” Zoey claims, “Marge and I are the same.”kk3. You meet two inhabitants: Sue and Zippy. Sue says that Zippy is a knave. Zippy says, “I and Sue are knights.”

7. You meet two inhabitants: Mel and Ted. Mel tells you, “Either Ted is a knight or I am a knight.” Ted tells you that Mel is a knave.

8. You meet two inhabitants: Zed and Alice. Zed tells you, “I am a knight or Alice is a knave.” Alice tells you, “Of Zed and I, exactly one is a knight.”

9. You meet two inhabitants: Ted and Zeke. Ted claims, “Zeke could say that I am a knave.” Zeke claims that it's not the case that Ted is a knave.

10. You meet two inhabitants: Ted and Zippy. Ted says, “Of I and Zippy, exactly one is a knight.” Zippy says that Ted is a knave.

In the situation where there are only 2 individuals, there are only 4 possibilities

1. Person A is a knight and person B is a knight === P ^ Q
2. Person A is a knight and person B is a knave ===== P ^ ~Q
2. Person A is a knave and person B is a knight ==== ~P ^ Q
4. Person A is a knave and person B is a knave ==== ~P ^ ~Q

The possibilities can also be explained in the logic tables below:

|  A   |  B  |Validity|
|:----:|:---:|:------:|
|  T   |  T  |        |
|  T   |  F  |        |
|  F   |  T  |        |
|  F   |  F  |        |

For example take the first question:
You meet two inhabitants, Zoey and Mel. Zoey tells you that Mel is a knave. Mel says, “Neither Zoey nor I are knaves.”

In this case Zoey will be A and Mel will be B. If you are able to deduce that one of the above possibilities in the table are invalid, you mark through that possibility and try to deduce which of the others are invalid until only one possibility or none are left.

1. Is it possible both A and B are telling the truth? **No** because their statement contradict one another
2. Is it possible that A is true and B is false? **Yes**
3. Is it possible that A is false and B is true? **No**, because if B was true then A wouldn't be able to say B was a Knave.
4. Is it possible that A is false and B is false? **No**, because if A were a Knave and B were a knave then A woulnd't be able to say B is a knave because it would be telling the truth.





Logic table to could be expanded exponentially to accomadate more than Knights and/or knaves. Bear in mind, your table will double in size for each new player you include. The truth tables however do save space and simplify the process over writing out each possible permutation of events.

|  A  |  B  |  C  |  D  |Validity|
|:---:|:---:|:---:|:---:|:------:|
|  T  |  T  |  T  |  T  |        |
|  T  |  T  |  T  |  F  |        |
|  T  |  T  |  F  |  T  |        |
|  T  |  T  |  F  |  F  |        |
|  T  |  F  |  T  |  T  |        |
|  T  |  F  |  T  |  F  |        |
|  T  |  F  |  F  |  T  |        |
|  T  |  F  |  F  |  F  |        |
|  F  |  T  |  T  |  T  |        |
|  F  |  T  |  T  |  F  |        |
|  F  |  T  |  F  |  T  |        |
|  F  |  T  |  F  |  F  |        |
|  F  |  F  |  T  |  T  |        |
|  F  |  F  |  T  |  F  |        |
|  F  |  F  |  F  |  T  |        |
|  F  |  F  |  F  |  F  |        |




