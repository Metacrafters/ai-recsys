# ai-recsys

## Q table

**…** If we use Q learning

**`Actions:`** `{`
`system functions,`
`specific messages`

* `Send a birthday/Valentine/etc card`
* `Offer to set a reminder`
* `Send message or email to family member`
  `suggestions in pings,`
  `}`


**`State:`** `{`
	`user intent {create_*,…, cancel_account, …},`
`user state {satisfied, liked, disliked, confused, request_human},`
`engagement level(derived dimension, e.g. frequency of use of ohai),`
`Day of week,`
`Places,`
`…`
`}`

**`Goal State:`** `engagement level > theng + engagement levelt>0 + satisfied +liked>thsat`
Cold start: *for similar users we can copy other Q tables (or parts of it) ??*

**`Reward`**
positive:

* 👍
* Action taken/accepted by the user

negative:

* cancel account,
* request Human,
* user confused,
* action not taken/accepted by the user


---
**Possible Elements of RL**

**Environment**

- Current date/time/weekday
-

**State**
*Questions:*

- State of what: user and or system?
- What is the goal state in our case?

Components

- User intent
- Calendar
- User profile (static)
- Memo pad / memory about user-specific information
- Time since last recommendation
- Recent conversation history

**Context**



