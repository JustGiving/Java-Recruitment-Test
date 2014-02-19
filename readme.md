## Intro

A big part of what we do at [JustGiving](http://www.justgiving.com) is reclaim the [Gift Aid](http://en.wikipedia.org/wiki/Gift_Aid) on donations made to charities. This saves them a lot of time and processing overheads.

This assignment is a very small task to create a Gift Aid calculator.

For reference, Gift Aid is calculated as follows:

`[Donation Amount] * ( [TaxRate] / (100 - [TaxRate]) )`

- This assignment takes an average of about 30 minutes.
- Use the Maven central repository for any package dependencies

## Task requirements

- All stories to be completed with an appropriate level of testing.
- No actual database implementation is required, feel free to stub it out.
- Your code should trend towards being SOLID.
- Please [download](https://github.com/JustGiving/Java-Recruitment-Test/archives/master) the [Java-Recruitment-Test repository](https://github.com/JustGiving/Java-Recruitment-Test), complete the tasks as you see fit.
- Send us a Dropbox/Skydrive/whatever link to your zipped code but please do not attach zipped files to email.
- **OR**
- If you have a paid GitHub account, feel free to create a **private repo** (you don't want people to copy you!) and send us a pull request.

## Task Stories

Please complete each story in order.

---

### Story 1

As a **donor**  
I want **to see my gift aid calculated according to the current tax rate**  
So that **I know how much extra cash the charity will make**

#### Acceptance criteria

- Gift aid calculated at a tax rate of 20%.
- Supported by unit tests.

---

### Story 2

As a **site administrator**  
I want **to be able to change the applicable tax rate**  
So that **I don't need to change the code when the tax rate changes**

#### Acceptance criteria

- Current Tax Rate is retrieved from data store.
- Gift Aid amount is calculated based on the current amount in the data store.

---

### Story 3

As a **donor**  
I want **to see my gift aid amount rounded correctly to 2 decimal places**  
So that **I'm not confused about how much will be paid to the charity**

#### Acceptance criteria

- Gift aid amount correctly rounded to 2 decimal places (1.316 should round to 1.32).

---

### Story 4

As an **events promoter**  
I want **to supplement gift aid payments based on event type**  
So that **people will feel inspired to donate to these event types**

#### Acceptance criteria

- 5% supplement added for donations to "running" events.
- 3% supplement added for donations to "swimming" events.
- No supplement should be applied for other events.

---

Thanks for your time, we look forward to hearing from you!
- The [JG Hackers](http://twitter.com/jghackers)
